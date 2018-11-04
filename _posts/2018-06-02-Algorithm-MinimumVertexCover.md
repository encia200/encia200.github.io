---
layout: article
key: 20180602
title:  "최소버텍스커버(MinimumVertexCover)"
author: "위준영"
tags:
  - BOJ
  - MinimumVertexCover
---

# 최소버텍스 커버란?
**버텍스커버(Vertex Cover)** : 정점 **집합 S**가 있을 때, 모든 간선은 **양 끝점중 적어도 하나가 S에 포함**되는 것을 말합니다.

<!--more-->
![](/assets/images/posts/algorithm/vertexcovergraph.png){: .imargin width="40%" height="40%"}

위 그래프에서 버텍스 커버는 어떤 것일까요? 임의의 버텍스커버를 찾아보겠습니다.

![](/assets/images/posts/algorithm/vertexcovergraph_max.png){: .imargin width="40%" height="40%"}

임의로 찾아본 위 그래프는 선택된 정점 집합을 S라고 했을 때 **모든 간선이 버텍스커버의 정의에 부합하므로 A,B,C,D,E는 버텍스커버라고 할 수 있습니다.**

![](/assets/images/posts/algorithm/vertexcovergraph_not.png){: .imargin width="40%" height="40%"}

위 그래프의 경우 B, E를 정점 집합 S라고 했을 때 **간선 A-D의 양끝점 중 어느 하나도 S에 속하지 않으므로 버텍스 커버라고 할 수 없습니다.**

이제 위의 그래프에서 **최소버텍스커버**를 찾아보겠습니다.

![](/assets/images/posts/algorithm/vertexcovergraph_min.png){: .imargin width="40%" height="40%"}

최소한의 정점을 가지고 버텍스커버를 만들어보았습니다.
특별한 조건이 없다면 최소버텍스커버는 여러개가 될 수 있을 것 같습니다.

<br/>
<br/>

## König's Theorem
원래 최소버텍스 커버문제는 NP-Problem(풀 수가 없는 문제)으로 퀴닉의 이론에 따르면 **Bipartite Graph**에서 **Maximum Matching**은 **Minimum Vertex Cover**와 같습니다.

<br/>

### BOJ 1867번 돌멩이제거
돌멩이 제거 : [링크](https://www.acmicpc.net/problem/1867)

N행 N열에 K개의 돌멩이가 한 칸에 하나씩 존재할 때 한 사람이 **한번 움직이면 한 행 또는 한 열에 있는 돌멩이를 모두 주울 수 있다**고 가정합니다. 이때 최소한으로 움직이면서 돌멩이를 줍는 것이 문제입니다. 최소 움직임 횟수를 출력하면 됩니다.

예제 입력
```bash
3 4
1 1
1 3
2 2
3 2
```

예제 출력
```bash
2
```

![](/assets/images/posts/algorithm/BOJ1867_ex_image.png "돌멩이제거예제"){: .imargin width="30%" height="30%"}

예제를 위의 그림과 같이 나타낼 수 있습니다. 이 그림을 행과 열로 나누어 이분그래프로 모델링 해보겠습니다.

![](/assets/images/posts/algorithm/BOJ1867_ex_graph.png "돌멩이제거그래프"){: .imargin width="30%" height="30%"}

이분그래프로 나타낸 위의 그래프에서 1번행과 2번열을 선택하면 최소버텍스커버를 만족하는 정점 집합을 구할 수 있습니다. 우리는 **이분그래프에서 최소버텍스커버 문제가 최대매칭과 동치**인 것을 이용해 이 문제를 해결할 수 있습니다.

#### 소스코드
```cpp
#include <stdio.h>
#include <iostream>
#include <vector>
#include <algorithm>

using namespace std;

int N,K;
int n, match, step;
vector<vector<int>> G;
vector<int> A, B, visit;

bool dfs(int a){
	visit[a] = step;

	for(auto b:G[a])
		if(B[b]==-1||(visit[B[b]]!=step&&dfs(B[b]))){
			A[a] = b;
			B[b] = a;
			return true;
		}

	return false;
}

int main(){
	cin>>N>>K;

	G = vector<vector<int>>(N+1);
	A = vector<int>(N+1, -1);
	visit = vector<int>(N+1, 0);
	B = vector<int>(N+1, -1);

	for(int i=1;i<=K;i++){
		int u,v;
		cin>>u>>v;
		G[u].push_back(v);
	}

	step=1, match=0;

	for(int i=1;i<=N;i++){
		if(A[i]==-1&&dfs(i)) match++;
		step++;
	}

	cout<<match;
	return 0;
}
```
