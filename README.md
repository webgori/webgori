# 기술

* JAVA
  * JDK 11을 주로 사용하며 JDK 8까지의 대부분의 기능들을 (Lambda Expression, Stream, try-with-resources 등…) 적재적소에 사용하여 개발합니다.

* Spring Boot
  * API 서버를 구현할 수 있으며, JSON Web Token (JWT)을 활용하여 세션을 적용할 수 있습니다. JPA를 사용하여 Database 또는 Multiple Database와 연결할 수 있으며, 트랜잭션 처리를 할 수 있습니다.

* Vue.js
  * 웹 페이지를 만들 때 Vue.js를 사용했습니다. JWT를 사용하여 로그인, 로그아웃 기능을 구현하였고, vuex를 사용하여 상태를 관리하였습니다.

* Netty
  * 실시간 컨텐츠를 개발할 때 사용하였습니다.

* Microsoft SQL Server
  * SQL 및 에이전트를 사용하여 데이터를 조회하고 조작할 수 있습니다. 라이브 서비스 중 직접 CS 처리도 진행하였습니다.

* JAVASCRIPT
  * HTML, Vue.js에서 JavaScript를 사용하였습니다.

* TYPESCRIPT
  * JavaScript를 사용하다가 객체지향적인 개발을 하고싶어서 TypeScript를 사용했습니다.

* SOCKET.IO
  * 게임빌 프로야구 슈퍼스타즈 프로젝트에서 실시간 대전 컨텐츠를 개발할 때 Socket.io를 사용했습니다. 서버가 Crash가 나는 이슈가 있었는데 쿼리 튜닝으로 잘 해결하였습니다.

* DOCKER
  * apache, redis, Elasticsearch 등 개발에 필요한 어플리케이션을 container로 만들어서 사용했습니다.

* ELASTICSEARCH
  * 게임빌 프로야구 슈퍼스타즈 프로젝트에서 API Request, Response 로그를 쌓을 때 사용했습니다. Vue.js로 만든 웹페이지에서 로그를 검색하여 CS 처리할 때 유용하게 사용했습니다.

* LOGSTASH
  * 게임빌 프로야구 슈퍼스타즈 프로젝트에서 API Request, Response 로그를 Elasticsearch로 전송할 때 사용했습니다.

* GIT
  * 간단한 프로젝트는 main, develop 브랜치만 사용하고, 규모가 있는 프로젝트는 main, develop, release, review 등으로 나누어서 사용했습니다. rebase를 사용하여 최대한 커밋을 깔끔하게 유지하였습니다

* REDIS
  * 세션, 캐싱 또는 빠른 데이터 접근이 필요할 때 사용하였습니다. 마구마구2 프로젝트에서 sentinel을 구성하여 failover를 처리하였습니다.

* PHP
  * Java를 사용하기전에 PHP를 주로 사용하였고, PHP7 버전을 마지막으로 사용했습니다.

* C#
  * 게임빌 프로야구 슈퍼스타즈 프로젝트에서 기획자, 벡앤드 개발자분들이 여러 리전에 쿼리를 적용할 때 한번에 적용 가능하도록 데스크탑 앱을 C# MFC로 만들었습니다.

* PYTHON
  * 간단한 기능을 스크립트로 만들 때 Python을 활용하였습니다.

# 프로젝트

* 토이토이
  * 모바일 캐주얼 아케이드 게임
  * 개발사
    * 넷마블블루
  * 개발 기간
    * 2014년 01월 ~ 2015년 10월 (1년 10개월)
  * 담당 업무
    * 목표 동시접속자 50,000명. 최고 동시접속자 약 10,000명, 게임 서버 5대 사용
    * Spring Framework를 사용
    * 서버 failover 처리
    * Redis를 사용하여 랭킹 구현
    * Kakao API를 사용하여 게임 플레이 시 이모티콘 지급하도록 개발
    * KT API를 사용하여 게임 플레이 시 특정 아이템을 모으면 모바일 데이터로 바꿔주는 기능 개발
    * 무중단 배포 방식으로 운영

* 마구마구2
  * 모바일 캐주얼 야구 게임
  * 개발사
    * 넷마블블루, 넷마블앤파크
  * 개발 기간
    * 2014년 03월 ~ 2017년 08월 (3년 06개월)
  * 담당 업무
    * 국내 및 대만 서비스. 목표 동시접속자 50,000명. 최고 동시접속자 약 35,000명, 게임 서버 5대 사용
    * Spring Framework를 사용
    * 서버 failover 처리
    * Redis를 사용하여 랭킹 구현
    * Spring Session을 사용하여 API 요청 필터링 기능 개발
    * PHP7을 사용하여 운영툴 개발 및 기능 추가(DB 작업 병행)
    * PHP7을 APK, IPA 빌드 배포 사이트 개발
    * JavaScript 및 jQuery를 사용하여 API 문서 개발
    * Elasticsearch, logstash, Kafka를 사용하여 지표 사이트 개발
    * 서버 세팅시 자동화 스크립트로 편리하게 세팅
    * Kakao API를 사용하여 게임 플레이 시 이모티콘 지급하도록 개발
    * Freetds 사용
    * 여러 서버 설치 및 스크립팅 등 전반적인 리눅스 작업
    * 대만 서비스시 대만 법인과 커뮤니케이션 하며 운영
    * 무중단 배포 방식으로 운영
    * Git 사용

* 소스라이브
  * 라이브로 즐기는 쇼핑 엔터테인먼트 플랫폼
  * 개발사
    * 모비두
  * 개발 기간
    * 2018년 10월 ~ 2019년 06월 (09개월)
  * 담당 업무
    * Spring Boot 2.x, JPA, QueryDSL, Multiple Datasource, Redis, Spring Security
    * Jenkins
    * Docker
    * Naver Cloud Platform 사용
    * Naver Cloud Platform의 OS Security Chekcer
    * Naver Cloud Platform의 WAS Security Chekcer
    * Naver Cloud Platform의 Object Storage
    * 2 Way SSL Authentication 적용
    * Firebase 동적 링크를 사용하여 공유 링크 기능 개발
    * API 명세서로 api-doc 사용
    * Elasticsearch, logstash, Grafana를 사용하여 지표 사이트 개발
    * Git
    * 통합 테스트 작성, 외부 서비스의 경우 Mock Server 사용



[![Badge](https://widget.realdeveloper.pro/api/badge?title=Languages%20and%20Framework&badges=Java,Spring,Vue.js,JavaScript,jQuery,Node.js,Express.js,Socket.io,Bootstrap&theme=dark)](https://github.com/webgori)
[![Badge](https://widget.realdeveloper.pro/api/badge?title=Database%20and%20DevOps&badges=MSSQL,MySQL,Git,GitHub,Bitbucket&theme=dark)](https://github.com/webgori)
![webgori github stats](https://github-readme-stats.vercel.app/api?username=webgori&show_icons=true)

![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=webgori&show_icons=true&layout=compact)

[![Repository Card](https://widget.realdeveloper.pro/api/card?user=webgori&repo=lolien-web)](https://github.com/webgori/lolien-web)
[![Repository Card](https://widget.realdeveloper.pro/api/card?user=webgori&repo=lolien-discord-bot)](https://github.com/webgori/lolien-discord-bot)
[![Repository Card](https://widget.realdeveloper.pro/api/card?user=webgori&repo=LolienClient)](https://github.com/webgori/LolienClient)
[![Repository Card](https://widget.realdeveloper.pro/api/card?user=webgori&repo=webgori-web)](https://github.com/webgori/webgori-web)
