# 자기소개

안녕하세요.

백엔드 개발자 박용순 입니다.

넷마블, 스타트업 회사 모비두에 다녔으며 현재는 컴투스에 재직 중 입니다.

평소 다양한 기술에 관심이 많고, 책임감이 강하여 맡은 업무를 일정안에 수행해냅니다.

이전에 다녔던 회사에서 우수사원상도 받았습니다.

테스트, 클린 코드, 체크 스타일을 적용하여 개발완료 후 나중에 코드를 보더라도 알아보기 쉽게 유지하려고 노력합니다.

소나 린트를 사용하여 버그가 발생할 수 있거나 보안적으로 취약한 코드를 사전에 제거하면서 개발하고있습니다.

클라이언트 개발자분들과 커뮤니케이션이 원활하여 업무 중 커뮤니케이션으로 이슈가 됐던적은 없습니다.

개발이 좋아서 개인 프로젝트도 진행하고, 평소 적용해보고 싶었던 기술들을 개인 프로젝트에 적용 해보고 있습니다.

감사합니다.


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

* JavaScript
  * HTML, Vue.js에서 JavaScript를 사용하였습니다.

* TypeScript
  * JavaScript를 사용하다가 객체지향적인 개발을 하고싶어서 TypeScript를 사용했습니다.

* Socket.IO
  * 게임빌 프로야구 슈퍼스타즈 프로젝트에서 실시간 대전 컨텐츠를 개발할 때 Socket.io를 사용했습니다. 서버가 Crash가 나는 이슈가 있었는데 쿼리 튜닝으로 잘 해결하였습니다.

* Docker
  * apache, redis, Elasticsearch 등 개발에 필요한 어플리케이션을 container로 만들어서 사용했습니다.

* Elasticsearch
  * 게임빌 프로야구 슈퍼스타즈 프로젝트에서 API Request, Response 로그를 쌓을 때 사용했습니다. Vue.js로 만든 웹페이지에서 로그를 검색하여 CS 처리할 때 유용하게 사용했습니다.

* Logstash
  * 게임빌 프로야구 슈퍼스타즈 프로젝트에서 API Request, Response 로그를 Elasticsearch로 전송할 때 사용했습니다.

* Git
  * 간단한 프로젝트는 main, develop 브랜치만 사용하고, 규모가 있는 프로젝트는 main, develop, release, review 등으로 나누어서 사용했습니다. rebase를 사용하여 최대한 커밋을 깔끔하게 유지하였습니다

* Redis
  * 세션, 캐싱 또는 빠른 데이터 접근이 필요할 때 사용하였습니다. 마구마구2 프로젝트에서 sentinel을 구성하여 failover를 처리하였습니다.

* PHP
  * Java를 사용하기전에 PHP를 주로 사용하였고, PHP7 버전을 마지막으로 사용했습니다.

* C#
  * 게임빌 프로야구 슈퍼스타즈 프로젝트에서 기획자, 벡앤드 개발자분들이 여러 리전에 쿼리를 적용할 때 한번에 적용 가능하도록 데스크탑 앱을 C# MFC로 만들었습니다.

* Python
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

* 게임빌 프로야구 슈퍼스타즈
  * 풀3D 모바일 캐주얼 판타지 야구 게임
  * 개발사
    * 컴투스 홀딩스 (게임빌)
  * 개발 기간
    * 2018년 10월 ~ 2019년 06월 (09개월)
  * 담당 업무
    * Spring Boot 프레임워크로 API 서버 처음부터 직접 개발
    * 라이브 최대 동접자
      * 국내: 2019년 11월 26일 23시 30분 (21,513명)
      * 일본: 2020년 08월 27일 23시 02분 (5,452명)
      * 글로벌: 2020년 09월 12일 14시 02분 (91,661명))
    * 안정적인 라이브 서비스 운영
    * 주도적인 서비스 코드의 전반적인 리팩토링
    * Vue.js로 웹 어플리케이션 개발
    * 코드 리뷰 시스템 gerrit 도입
    * ELK Stack을 도입하여 라이브 서버 로그를 쉽게 볼 수 있도록 개선
    * Jira, Confluence 이슈 관리
    * 자발적인 세미나 진행
    * 팀원들에게 sonarlint를 소개하고 IDE에 적용하도록 하여 코드 품질을 높임
    * 기획자들이 쿼리를 개발 DB에 적용할 수 있도록 Query Scripter (C#) 개발
    * Kibana로 자주 호출하는 API, 응답시간이 높은 API 등 분석
    * Netty를 이용하여 채팅 서버 직접 개발. 이전에 사용하던 채팅 서버 미사용으로 비용 절감
    * 라이브 서버의 한국, 일본, 글로벌 리전의 서버 통합 스크립트를 만들어서 성공적으로 3개의 리전 통합
    * 코드 저장소를 gerrit에서 GitHub Enterprise로 마이그레이션
    * PR시 메신저에 알림이 가도록 설정, Submit시 자동 배포 기능 적용


# 경력

  * 넷마블블루
    * 근무 기간
      * 2013년 08월 ~ 2016년 10월 (3년 3개월)
    * 프로젝트
      * 토이토이
       
  * 넷마블앤파크
    * 근무 기간
      * 2016년 11월 ~ 2017년 08월 (10개월)
    * 프로젝트
      * 마구마구2
       
  * 모비두
    * 근무 기간
      * 2017년 12월 ~ 2019년 06월 (1년 7개월)
    * 프로젝트
      * 소스라이브
       
  * 컴투스
    * 근무 기간
      * 2019년 6월 ~ 현재 근무 중
    * 프로젝트
      * 게임빌 프로야구 슈퍼스타즈


# 학력

  * 인천전자마이스터고등학교
    * 멀티미디어전자과
    * 2006년 03월 ~ 2009년 2월
    
  * 인하공업전문대학
    * 컴퓨터시스템과
    * 2009년 03월 ~ 2014년 02월
    
</br>

[![Badge](https://widget.realdeveloper.pro/api/badge?title=Languages%20and%20Framework&badges=Java,Spring,Vue.js,JavaScript,jQuery,Node.js,Express.js,Socket.io,Bootstrap&theme=dark)](https://github.com/webgori)
[![Badge](https://widget.realdeveloper.pro/api/badge?title=Database%20and%20DevOps&badges=MSSQL,MySQL,Git,GitHub,Bitbucket&theme=dark)](https://github.com/webgori)
![webgori github stats](https://github-readme-stats.vercel.app/api?username=webgori&show_icons=true)

![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=webgori&show_icons=true&layout=compact)

[![Repository Card](https://widget.realdeveloper.pro/api/card?user=webgori&repo=lolien-web)](https://github.com/webgori/lolien-web)
[![Repository Card](https://widget.realdeveloper.pro/api/card?user=webgori&repo=lolien-discord-bot)](https://github.com/webgori/lolien-discord-bot)
[![Repository Card](https://widget.realdeveloper.pro/api/card?user=webgori&repo=LolienClient)](https://github.com/webgori/LolienClient)
[![Repository Card](https://widget.realdeveloper.pro/api/card?user=webgori&repo=webgori-web)](https://github.com/webgori/webgori-web)
