---
layout: article
title: 소프트웨어 개발 툴
subtitle: 오픈소스 기반 소프트웨어 개발 도구 조사
key: 20180603
tags:
- SoftwareEngineering
- DevTools
published : true
---

Software Development Life Cycle 전체에 걸쳐서 사용되는 도구들에 대해서 알아보겠습니다.

<!--more-->

# 1. 개발

## 화면(UI/UX)
### Pencil Project
> An open-source GUI prototyping tool that's available for ALL platforms.
> Pencil is built for the purpose of providing a free and open-source GUI prototyping tool that people can easily install and use to create mockups in popular desktop platforms. - [https://pencil.evolus.vn/][1]

오픈소스 GUI 프로토타이핑 툴로써 모든 플랫폼에서 사용 가능합니다.
UI를 개발할 때 쉽게 설치 및 사용할 수 도록 하는 것을 목표로 개발된 와이어프레임 툴입니다.

#### 특징
- Firefox 애드온으로 설치하여 Web어플형으로 사용하거나, 독립적인 어플로 설치도 가능
- HTML, PNG, Openoffice, Word, PDF로 내보내기

## 업무

### Eclipse
> 자바 개발자들에게 가장 친숙한 프로그램. 이클립스는 Windows, macOS, 리눅스 중 어디서든 자유롭게 이용 및 수정, 재배포가 가능하다.

#### 장점
- 운영체제의 제한 없이 어디서든 사용이 가능합니다.
- 풍부한 플러그인이 존재하기 때문에 확장석이 뛰어납니다.

#### 단점
- 순수한 버전에서는 다른 IDE에 못 미치는 수준이다.
- 너무 많은 플러그인이 존재하기 때문에 최적화 문제가 있다.

### IntelliJ
> IntelliJ IDEA는 JetBrains사에서 제작한 상용 자바 통합 개발 환경이다. 줄여서 IntelliJ 혹은 IDEA로도 불린다.
> 이클립스 재단 의 이클립스와 썬 마이크로시스템즈의 넷빈즈로 대표되는 무료 자바 통합개발환경에서 볼랜드(/코드기어)의 제이빌더(JBuilder)와 함께 얼마 안 되는 상용 개발 도구 가운데 하나이다.

#### 특징
- Java IDE 환경 제공
- 모바일 및 엔터프라이저 개발을 위한 프레임워크 제공
- 형상관리도구 및 빌드도구와 호환 가능

#### 장점
- 이클립스에 비해 높은 안정성을 가지고 있습니다.

#### 단점
- 프로젝트 기반의 워크스페이스
- 더 많은 기능을 사용하기 위해서는 유료인 Ultimate버전을 사용해야합니다.

## DB
> 데이터베이스(영어: database, DB)는 체계화된 데이터의 모임이다. 즉, 작성된 목록으로써 여러 응용 시스템들의 통합된 정보들을 저장하여 운영할 수 있는 공용 데이터들의 묶음이다.

### MySQL(Maria DB)
> MySQL은 세계에서 가장 많이 쓰이는 오픈 소스의 관계형 데이터베이스 관리 시스템(RDBMS)이다. 다중 스레드, 다중 사용자 형식의 구조질의어 형식의 데이터베이스 관리 시스템으로서 MySQL AB가 관리 및 지원하고 있으며, Qt처럼 이중 라이선스가 적용된다. 하나의 옵션은 GPL이며, GPL 이외의 라이선스로 적용시키려는 경우 전통적인 지적재산권 라이선스의 적용을 받는다.

### CUBRID
> CUBRID은 관계형 데이터베이스 관리 시스템의 이름이며, 오픈 소스 소프트웨어이다. DBMS 엔진 부분은 GPL v2 라이선스가 적용되고 인터페이스 부분은 BSD 라이선스가 적용되었으며, 국제표준화기구의 표준 구조화 조회 언어를 지원한다. 2008년 11월 CUBRID 2008이 출시되었고, 2013년 CUBRID 9이 출시되었다.

### Oracle DB
> 오라클 데이터베이스(Oracle Database 또는 Oracle RDBMS)는 미국 오라클(Oracle)사의 관계형 데이터베이스 관리 시스템의 이름이다. 현재 유닉스 환경에서 가장 널리 사용되는 RDBMS이다. 검색이나 업데이트용 언어로는 국제표준화기구의 표준 구조화 조회 언어와 PL/SQL을 지원한다.

### PostgreSQL
> PostgreSQL은 확장 가능성 및 표준 준수를 강조하는 객체-관계형 데이터베이스 관리 시스템(ORDBMS)의 하나이다. BSD 허가권으로 배포되며 오픈소스 개발자 및 관련 회사들이 개발에 참여하고 있다. 데이터베이스 서버로서 주요 기능은 데이터를 안전하게 저장하고 다른 응용 소프트웨어로부터의 요청에 응답할 때 데이터를 반환하는 것이이다. 소규모의 단일 머신 애플리케이션에서부터 수많은 동시 접속 사용자가 있는 대형의 인터넷 애플리케이션(또는 데이터 웨어하우스용)에 이르기까지 여러 부하를 관리할 수 있으며 macOS 서버의 경우 PostgreSQL은 기본 데이터베이스이다. 마이크로소프트 윈도우, 리눅스(대부분의 배포판에서 제공됨)용으로도 이용 가능하다.

## WEB
> 웹 서버(Web Server)는 HTTP를 통해 웹 브라우저에서 요청하는 HTML 문서나 오브젝트(이미지 파일 등)을 전송해주는 서비스 프로그램을 말한다.

### Apache
> 아파치 HTTP 서버(영어: Apache HTTP Server)는 아파치 소프트웨어 재단에서 관리하는 HTTP 웹 서버이다. BSD, 리눅스 등 유닉스 계열 뿐 아니라 마이크로소프트 윈도우나 노벨 넷웨어 같은 기종에서도 운용할 수 있다.

## WAS
> 웹 애플리케이션 서버(Web Application Server, 약자 WAS)는 인터넷 상에서 HTTP를 통해 사용자 컴퓨터나 장치에 애플리케이션을 수행해 주는 미들웨어(소프트웨어 엔진)이다. 웹 애플리케이션 서버는 동적 서버 콘텐츠를 수행하는 것으로 일반적인 웹 서버와 구별이 되며, 주로 데이터베이스 서버와 같이 수행이 된다. 한국에서는 일반적으로 "WAS" 또는 "WAS S/W"로 통칭하고 있으며 공공기관에서는 "웹 응용 서버"로 사용되고, 영어권에서는 "Application Server" (약자 AS)로 불린다.

### 기본 기능
- 프로그램 실행 환경과 데이터베이스 접속 기능을 제공한다.
- 여러 개의 트랜잭션을 관리한다.
- 업무를 처리하는 비즈니스 로직을 수행한다.

### Tomcat
> 아파치 톰캣(Apache Tomcat)은 아파치 소프트웨어 재단에서 개발한 서블릿 컨테이너(또는 웹 컨테이너)만 있는 웹 애플리케이션 서버이다.

### JBoss -\> WildFly
> 와일드플라이(WildFly, 이전 이름: JBoss)는 자바를 기반으로 하는 오픈 소스 미들웨어의 총칭이다. 대표적으로 Java EE 스펙을 지원하는 제이보스 애플리케이션 서버가 있다. 현재 40개 이상의 다양한 프로젝트가 있으며, Jboss.org 커뮤니티에 의해 개발 및 운영되고 있다.

## BUILD/RELEASE

### 등장배경
프로그래밍 개발이 발전하며 프로젝트 생성에 필요한 라이브러리들이 많아졌습니다. 이렇게 많아진 라이브러리들을 직접 다운로드 받아 시스템에 추가하는 것은 어려운 일이 아닐 수 없습니다.

빠른 기간동안에 계속해서 늘어나는 라이브러리의 추가하고 프로젝트를 진행하며 라이브러리의 버전을 동기화하는 것을 편리하게 제공하기 위해 등장했습니다.

### Apache Ant
> 아파치 앤트(영어: Apache Ant)는 자바 프로그래밍 언어에서 사용하는 자동화된 소프트웨어 빌드 도구이다. 유닉스나 리눅스에서 사용되는 make와 비슷하나 자바언어로 구현되어 있어 자바 실행환경이 필요하며 자바 프로젝트들을 빌드하는데 표준으로 사용된다.
> make와 눈에 띄는 가장 다른 부분은 빌드를 위한 환경구성을 XML 파일을 사용한다는 점이다. 기본적인 빌드 파일명은 build.xml 이다.
> 로고는 이름(ANT)에 따라 개미 모양으로 만들어졌으나 이는 Another Neat Tool의 약어이다.
> *위키피디아*

High flexibility but hard to understand.

### Maven
> 아파치 메이븐(Apache Maven)은 자바용 프로젝트 관리 도구이다. 아파치 앤트의 대안으로 만들어졌다. 아파치 라이선스로 배포되는 오픈 소스 소프트웨어이다.

Strong convention but hard to implement custom logic

라이브러리들이 서로 종속성을 가지는 경우 XML이 복잡해진다.

### Gradle
> Gradle은 Groovy를 이용한 빌드 자동화 시스템이다. Groovy와 유사한 도메인 언어를 채용하였으며, 현재 안드로이드 앱을 만드는데 필요한 안드로이드 스튜디오의 공식 빌드 시스템이기도 하다. Java, C/C\++, Python 등과 같은 여러 가지 언어를 지원한다.

|---
|  | Ant | Maven | Gradle
|-|:-:|:-:|:-:
| **build script format** | XML | XML | Groovy / DSL
| **dependencies** | with Ivy | built-in | built-in
| **multi-module builds** | complex | simple | simple
| **pre-defined structiure** | absent | present | present
| **custom structure** | N/A | complex | simple
| **verbosity** | high | average | low
| **learning curve** | shallow | steep | average
| **build order** | depends-on | lifecycles | directed acyclic graph

# 2. 테스팅

## 테스트 관리

### TestLink
> TestLink 는 소프트웨어 품질 보증 을 용이하게 하는 웹 기반 테스트 관리 시스템입니다 . Teamtest에서 개발 및 유지 관리합니다. 이 플랫폼은 테스트 사례, 테스트 스위트, 테스트 계획, 테스트 프로젝트 및 사용자 관리는 물론 다양한 보고서 및 통계를 지원합니다.

TestLink는 웹을 기반으로 테스트를 관리한다. 또한 테스트 명세서와 계획, 리포팅, 요구사항 트래킹 기능을 가지고 있 으며 버그 트래킹 시스템들과 연동이 가능하다.

#### 특징
- Web 환경의 인터페이스(사용자는 인스톨 없이 어디서든지 접근가능)
-  테스트의 우선순위부여기능 및 사용자의 활동영역 정의(리더, 테스터)
-  다양한 종류의 DB를 지원 (MySQL, PostgreSQL, MS-SQL등)
-  트리 구조를 이용한 테스트케이스 작성기능
-  다양한 언어 지원(English, French, German, Italian, Spanish등)
-  다양한 버그 시스템들과 직접 연동 가능(Bugzilla, Mantis, Jira, TrackPlus, Eventum, Trac, Seapine)
-  다양한 형식의 보고서 제공(HTML, MS-Word, MS-Excel) 및E-mail에 직접 보고서를 보낼 수 있는 기능 제공

#### 주요기능
- 요구사항 트래킹 기능 제공, 다양한 형식의 보고서 작성 기능

## 형상관리

### Subversion
> 서브버전(Subversion)은 자유 소프트웨어 버전 관리 시스템이다. 명령행 인터페이스에서 사용하는 명령어를 따서 “SVN”이라고 줄여서 부르기도 한다. 제한이 있던 CVS를 대체하기 위해 2000년부터 콜랩넷에서 개발되었다. 현재는 아파치 최상위 프로젝트로서 전 세계 개발자 커뮤니티와 함께 개발되고 있다.

CVS의단점을보완하여작성된중앙집중형방식의형상관리도구

#### 특징
- 파일이나 디렉터리를 이동해도 이력 보존
-  gzip압축을통한저장공간절약
- CVS에비해빠른속도
- 다양한써드파티GUI도구존재

#### 주요기능
- checkout/checkin, update/commit 등 서버 저장소와 클라이언트의 변경 사항 전송
- diff를통한파일내용비교
- 바이너리문서형상관리
- 작업단위의변경사항관리
- atomic commit
- svn:ignore를 통한 형상 관리 배제 자원 지정 기능

### Git
> 깃(Git)은 프로그램 등의 소스 코드 관리를 위한 분산 버전 관리 시스템이다. 기하학적 불변 이론을 바탕으로 설계됐고, 빠른 수행 속도에 중점을 두고 있는 것이 특징이다. 최초에는 리누스 토르발스가 리눅스 커널 개발에 이용하려고 개발하였으며, 현재는 다른 곳에도 널리 사용되고 있다.

리누스 토발즈가 만든 분산형 버전 관리 시스템으로 대부분의 공개SW가 Git을 이용해서 관리되고 있습니다. GitHub, BitBucket, GitLab 등 웹 기반의 다양한 소스 저장소 서비스의 기반이며 대부분의 IDE에서 Git을 지원합니다.

#### 특징
- 분산형 버전관리시스템으로 Git사용자가 Git 저장소를 보유하고 원격과 동기화
- 거의 모든 명령을 로컬에서 수행하며, branch의 생성/전환/폐기가 빠르다
- 파일별 변화를 저장하는 다른 버전관리시스템과 달리 파일 시스템 스냅샷을 관리

#### 주요기능
- 소스및문서버전관리서버및클라이언트기능
- add, commit, reset, branch, checkout, merge, rebase 등 로컬에서의 작업
- push, pull. fetch 등 원격 작업

## 결함관리

### Redmine
> 레드마인(Redmine)은 오픈 소스 프로그램으로 웹 기반의 프로젝트 관리 와 버그 추적 기능을 제공하는 도구이다. 화면기반의 프로젝트 관리에 도움이 되도록 달력과 간트 차트를 제공하고 일정관리 기능을 제공한다. 또한 레드마인은 통합된 프로젝트관리 기능과 이슈추적, 여러가지 형상 관리 기능을 제공한다.
> 레드마인의 디자인은 비슷한 기능을 가지는 오픈 소스 프로그램인 Trac에 영향을 많이 받았으며 루비 온 레일즈에 기반하여 작성되었고 멀티 플랫폼을 지원하며 여러가지 종류의 데이터베이스 및 34개의 언어를 지원한다.

#### 특징
- 유연한이슈및버그추적
- 간트차트와달력기능제공
- 다중프로젝트지원
- 형상관리 소프트웨어와의 통합

#### 주요 기능
- 프로젝트 관리, 이슈관리, 간트 차트
- 이메일알림
- 다중프로젝트관리,프로젝트별위키페이지
-  형상관리 소프트웨어 연동

### Bugzilla
> 버그질라(Bugzilla)는 원래 모질라 프로젝트가 개발하여 사용한 웹 기반의 일반 목적의 버그 추적기 및 테스트 도구이다. 현재 모질라 공용 허가서로 사용권이 제공된다.
> 1998년에 넷스케이프 커뮤니케이션스가 오픈 소스 소프트웨어로 공개하였으며 다양한 단체가 버그 추적 시스템으로 채택하였다. 버그질라는 자유 및 오픈 소스 소프트웨어와 사유의 프로젝트 및 제품 전반에 모두에 쓰인다.

#### 주요 기능
- 버그 신고, 확인, 처리 등 버그 추적 관리
- 버그 관련 검색, 이메일 통지
- 중복 버그 탐지, 버그 관련 통계, 보고서 및 차트

#### 특징
- 버그를 지속적으로 관리/참조 가능
-  버그의 심각도와 우선순위 지정 가능
- 엑셀 변환 가능

### Mantis
웹 기반의 버그 및 이슈 관리 시스템. 프로젝트 관리 및 소프트웨어 설계 시, 단위별로 사용자가 작업한 내용을 기록할 수 있으므로 버그 추적까지도 유용하게 사용 가능

#### 주요 기능
- 이슈 보고
- 이슈 상태 변경
- 이슈 알림 메일 보내기

#### 특징
- 각각의 작업이나 전체 프로젝트에 대해서 작업 진행 상태를 도식화 가능
- 프로젝트 변경 이력에 대한 추적/관리 및 유지보수
- 프로젝트 참여자들의 작업 내용을 추가/보고/관리

## 단위테스트

### JUnit
> JUnit은 Java기반 테스팅을 위한 프레임워크로, 단위모듈(ex: Method)이 정확히 구현되었는지를 확인할 수 있는 도구

#### 특징
- 메소드와 같은 단위 모듈별 테스팅을 가능케 함으로써 코드 품질을 보장
- 정확한 단위 테스팅을 가능케 함으로써 통합 테스팅 시 회귀결함(모듈통합에 의해 발생하는 결함)을 줄임
- 다른 모듈에 의존하지 않고, 원하는 모듈만 임의의 순서대로 수행할 수 있다.
- JFeature(요구사항개발도구)와 통합되어 요구사항의 정확한 구현 비율을 알 수 있다.

### CppUnit
> CppUnit는 C++용 testing Framework로 Java의 Junit을 C++로 구현
> C++ 언어에서 사용할 수 있도록 개발된 Open Source 프로젝트로, source code의 특정 Module이 의도하는 방향으로 정확히 작동하는지 검증할 수 있도록 하는 Unit test Library Framework.

#### 주요기능
- C++ 프로그램의 unit testing

#### 특징
-  다양한 Platform 및 지원도구가 많다(Visual Studio, Eclipse 등)
-  Source Code 수정 없이 Source가 제대로 실행되는지 간단한 설정을 통하여 쉽게 알아낼 수 있다.

## 성능/부하 테스트

### Jmeter
부하 테스트 및 성능 측정을 위해서 개발된 100% 순수 자바 애플리케이션
HTTP를 사용하여 사이트의 부하를 테스트할 수 있도록 정적이거나 동적인 자원(파일, 서블릿, 자바 객체들, 데이터베이스 등)에 대해서 테스트하는데 사용

#### 주요기능
- 정적,동적인웹페이지부하및성능테스트 • Response Assertion
- Duration Assertion
- Size Assertion

#### 특징
- HTTP, FTP, SMTP, POP3, LDAP, JMS, SOAP, TCP 등 다양한 프로토콜 지원
- 완벽한 Multi Threading 프레임 워크 지원
- 다수의 Thread가 동시에 테스트 데이터를 추출
- 2.12 버전부터 Java 8 지원

## 정적분석

### PMD
정해진 규칙에 따라 소스코드를 검사해 주고 이에 대한 결과를 report하게 함으로서 코딩 효율을 높여주는 도구

#### 주요기능
- Code Check
- Reporting

#### 특징
- 작성한 코드에 대한 위반사항(위반되는 코딩 스타일, 불필요한 코드)를 찾음
- 위반 사항을 명시한 report파일(pmd.xml, cpd.xml file)에 대한 수정이 쉬움
- 한 번의 클릭으로 수많은 규칙에 대한 수정이 가능

### Splint
C언어의 source code를 분석하여 programming 오류나 보안상 취약점들을 검출

#### 주요기능
- Compile 전 잠재적 오류 검출
- Source code 내의 기본적 오류사항 및 위험사항을 보여줌

#### 특징
아래와 같은 결과를 출력하여 C code의정적code 분석에 사용 • Unused Variables
- Buffer overflow Vulnerabilities
- Dynamic Memory Errors

# 3. 프레임워크

### Spring - server
> 스프링 프레임워크(Spring Framework)는 자바 플랫폼을 위한 오픈소스 애플리케이션 프레임워크로서 간단히 스프링(Spring)이라고도 불린다. 동적인 웹 사이트를 개발하기 위한 여러 가지 서비스를 제공하고 있다. 대한민국 공공기관의 웹 서비스 개발 시 사용을 권장하고 있는 전자정부 표준프레임워크의 기반 기술로서 쓰이고 있다.

#### 특징
- 경량 컨테이너로서 자바 객체를 직접 관리한다.
- 기존에 존재하는 라이브러리 등을 지원하기에 용이하고 객체가 가볍다.
- 스프링은 의존성 주입을 지원한다.
- 스프링은 관점 지향 프로그래밍을 지원한다.

### iBATIS - database
> iBATIS(아이바티스)는 SQL에 기반한 데이터베이스와 자바, 닷넷(.NET), 루비(Ruby) 등을 연결시켜 주는 역할을 하는 영속성 프레임워크(Persistence Framework)이다. 이러한 연결은 프로그램의 소스코드에서 SQL 문장을 분리하여 별도의 XML 파일로 저장하고 이 둘을 서로 연결시켜주는 방식으로 작동한다.

### Hibernate - database
> 하이버네이트 ORM(Hibernate ORM)은 자바 언어를 위한 객체 관계 매핑 프레임워크이다. 객체 지향 도메인 모델을 관계형 데이터베이스로 매핑하기 위한 프레임워크를 제공한다. 하이버네이트는 GNU LGPL 2.1로 배포되는 자유 소프트웨어이다.

## Reference
- [https://www.slideshare.net/HannoEmbregts/migrating-25k-lines-of-ant-scripting-to-gradle][2]
- [http://www.sw-eng.kr/member/00000000000000032236/Cms/BoardView.do][3]

[1]:	https://pencil.evolus.vn/
[2]:	https://www.slideshare.net/HannoEmbregts/migrating-25k-lines-of-ant-scripting-to-gradle
[3]:	http://www.sw-eng.kr/member/00000000000000032236/Cms/BoardView.do
