battlecook
============

> 주소 : 대한민국 서울<br>
> 메일 : battlecookresume@gmail.com <br>
> 깃헙 : [https://github.com/battlecook](https://github.com/battlecook) <br>
> 스택오버플로 : [https://stackoverflow.com/users/13429399/battlecook](https://stackoverflow.com/users/13429399/battlecook)

요약
---------

모바일 게임회사에서 게임서버개발을 하였고, 3~4개의 게임을 프로젝트 초기부터 런칭, 라이브 업데이트까지 진행하여, 전체 수명주기에서 개발/트러블슈팅 역량을 가지고 있습니다.
머신러닝 기법을 활용한 유저 군집화를 통해 게임 내 어뷰저를 탐지할 수 있는 시스템과  광학문자인식(ocr) 을 활용한 QA 다국어 업무 자동화 시스템을 개발 했습니다.
최근에는 현대자동차 AIRS의 speech 팀에서 음성 인식/합성 서버 플랫폼 개발 및 유지보수와 유틸리티 툴들을 개발하고 있습니다.
"언제나 처음 왔을 때보다 깨끗하게 해놓고 캠프장을 떠날 것" 이라는 보이스카웃 규칙을 따르며 업무에 임하고 있습니다.


경력 요약
----------

[현대자동차](https://airsc.ai/)

* 2022-2022 : 관리도구 개발 - 음성 인식 word-dict 관리도구 개발
* 2021-2022 : 플랫폼서버개발 - 음성 인식/합성 서버 플랫폼 개발
 
[컴투스](https://www.com2us.com)

* 2020-2021 : 선행 R & D (머신러닝) <br>
* 2019-2020 : 단스짱 <br>
* 2015-2019 : 댄스빌 <br>
* 2014-2015 : 타워디펜스 : 끝없는 전쟁 <br>
* 2013-2013 : 꼬꼬마 유랑단 <br>
* 2011-2013 : 더비데이즈, 말랑말랑 목장 <br>

기술
--------------------

* 언어 : dart, php, go, c#(for unity), python(for ml and flask)
* 운영체제 : linux(centos)
* 데이타베이스 : mysql, bigquery
* 사용해본 캐시 솔루션 : redis, memcached
* 웹서버 : nginx + phpfpm , [workerman](https://github.com/walkor/Workerman), [reactphp](https://reactphp.org/)
* 테스트 : phpunit, dbunit 
* 배포 : capistrano, rsync
* 로그 : scribe, fluentd
* 툴 : jetbrains Tools (phpstorm, goland, datagrip, rider etc)
* 개발환경 : docker
* 형상관리 툴 : git, svn
* 의존성 관리 도구 : composer
* 지속적 통합 : travis
* 클라우드 서버 : aws, gcp, heroku, ncloud(네이버클라우드) 
* 사용해 본 프레임웍 : [flutter](https://flutter.dev/), [flask](https://palletsprojects.com/p/flask/)
* 사용해 본 게임엔진 : 유니티
* 기계 학습 : 군집화, 이상탐지
* 추천 도서, 글 : 피플웨어, 자유와 책임(넷플릭스), 신규입사자 가이드(벨브)
* 기타 : grpc, 프로토콜 버퍼, 플랫버퍼

오픈 소스
--------------------

### DataCooker

[https://github.com/battlecook/DataCooker](https://github.com/battlecook/DataCooker)

- nginx, php-fpm  환경에서 io 를 줄이고 컨텐츠 개발에 집중할 수 있도록 php 라이브러리를 개발
- php 패키지 레포지터리인 [packagist 에 배포](https://packagist.org/packages/battlecook/datacooker)

### **Astar**

[https://github.com/battlecook/AStar](https://github.com/battlecook/AStar)

- 최단 경로 알고리즘인 [AStar 알고리즘](https://ko.wikipedia.org/wiki/A*_%EC%95%8C%EA%B3%A0%EB%A6%AC%EC%A6%98)을 구현한 라이브러리
- 개인프로젝트 진행 중 서버에서 사용했던 AStar 로직을 오픈소스로 전환
- 데모페이지를 Paas 인 [Heroku](https://ko.wikipedia.org/wiki/%ED%97%A4%EB%A1%9C%EC%BF%A0) 클라우드 플랫폼에 운영
- 데모 페이지 : [https://battlecook.herokuapp.com/test/Simulation.php](https://battlecook.herokuapp.com/test/Simulation.php)

### **php-kmeans**

[https://github.com/bdelespierre/php-kmeans](https://github.com/bdelespierre/php-kmeans)

- v2 : kmeans++ 초기화 함수 구현 및 기타 마이너 수정 [공헌](https://github.com/bdelespierre/php-kmeans/graphs/contributors)
- v3 : 인터페이스 초안 설계 참여

### **보이스카우트 규칙**

"언제나 처음 왔을 때보다 깨끗하게 해놓고 캠프장을 떠날 것" 이라는 보이스카우트 룰에 의거한 오픈소스 공헌

오픈소스 사용시 잘못되어 있는 코드, 문서 등을 보면 작업이 작든 크든 PR을 보내 깨끗이 하려고 노력함

공헌 목록 

- kmeans 알고리즘 [https://github.com/bdelespierre/php-kmeans/graphs/contributors](https://github.com/bdelespierre/php-kmeans/graphs/contributors)
- 선형대수 [https://github.com/mcordingley/LinearAlgebra/graphs/contributors](https://github.com/mcordingley/LinearAlgebra/graphs/contributors)
- 이벤트 에미터 [https://github.com/igorw/evenement/graphs/contributors](https://github.com/igorw/evenement/graphs/contributors)
- nginx + phpfpm 도커파일 [https://github.com/wyveo/nginx-php-fpm/graphs/contributors](https://github.com/wyveo/nginx-php-fpm/graphs/contributors)
- 플루터 검색 위젯 [https://github.com/apgapg/search_widget/graphs/contributors](https://github.com/apgapg/search_widget/graphs/contributors)
- 플루터 이미지 [https://github.com/fluttercandies/extended_image/graphs/contributors](https://github.com/fluttercandies/extended_image/graphs/contributors)
- 플루터 파이토치 [https://github.com/fynnmaarten/flutter_pytorch_mobile/graphs/contributors](https://github.com/fynnmaarten/flutter_pytorch_mobile/graphs/contributors)
- 케라스 코리아 컨트리뷰톤 [https://github.com/KerasKorea/KEKOxTutorial/graphs/contributors](https://github.com/KerasKorea/KEKOxTutorial/graphs/contributors)

그 외 다수 공헌 및 PR

개인 프로젝트
--------------------

## 플러터웹을 이용한 웹 사이트 개발

*(2022.2 - 2022.3)*

즉석 복권 스피또 구매시 현재 어떤 즉석복권을 사아햐는지 알기 위해 개발

- [https://eyedealists.net/](https://eyedealists.net/) 운영
- [let's encrypt](https://letsencrypt.org/ko/)  을 이용한 ssl 대응
- 호스팅업체 [가비아](https://www.gabia.com/) 에서 도메인 구입 후 dns 적용
- gcp cloud function 을 이용한 crawling & api 구현
- gcp cloud artifact registry & cloud run 을 이용한 배포시스템 구축
- github action 을 이용해 push, pr 시 자동으로 test case 실행하도록 작업

## 플러터와 다트를 이용한 모바일 앱 개발

*(2019.7 - 2020.9)*

모바일 어플리케이션 개발 역량 강화를 위해 개인적으로 진행했던 프로젝트

개발 당시 구글에서 출시한지 얼마 안된 플러터를 사용함으로써 스택오버플로에서 많은 도움을 주고 받는 경험을 함

- 클라이언트 flutter, 서버 dart 를 이용해 dart 언어의 이해도 증가
- grpc를 사용하여 서버/클라간 통신
- firebase 를 사용한 auth 구현
- chips input field 위젯 구현 및 github gist 에 공개[https://gist.github.com/battlecook/2afbc23e17d4d77069681e21c862b692](https://gist.github.com/battlecook/2afbc23e17d4d77069681e21c862b692)
- ui 와 business logic 을 분리하는 ReactiveX 패러다임 이해 ( rxdart 사용 )
- adobe xd to flutter 를 활용
- **google cloud platform**를 이용해 서버 운영 (현재 운영중)
- 플러터2.0 null safety 마이그레이션

플러터 관련 스택오버플로 활동

- [https://stackoverflow.com/questions/65613148/flutter-unhandled-exception-filesystemexception-creation-failed-path-dire/65613322#65613322](https://stackoverflow.com/questions/65613148/flutter-unhandled-exception-filesystemexception-creation-failed-path-dire/65613322#65613322)
- [https://stackoverflow.com/questions/64834702/why-build-function-gets-called-twice-when-hot-restarting](https://stackoverflow.com/questions/64834702/why-build-function-gets-called-twice-when-hot-restarting)
- [https://stackoverflow.com/questions/61699351/flutter-the-index-value-i-asked-to-remove-is-different-from-the-index-value-tha](https://stackoverflow.com/questions/61699351/flutter-the-index-value-i-asked-to-remove-is-different-from-the-index-value-tha)

그 외 다수

## 모바일 게임 서버 개발

*(2017.1 - 2019.2)*

업무로 해보지 못했던 tcp 서버 개발과 클라우드 서버 환경을 개인적으로 경험 해보기 위해 진행 

- 프로토콜버퍼, 플랫버퍼, json 등 의 성능 비교 테스트
- **aws** 를 이용해 서버운영 (무료기간 만료로 현재 운영하지 않음)
- 무료 https  ( [let's encrypt](https://letsencrypt.org/ko/) ) 적용
- php 를 이용한 소켓서버 구현 [workerman](https://github.com/walkor/Workerman) 라이브러리 사용
- 연결지향 프로토콜 tcp 에 대한 이해
- bitbucket 이용
- 서버에서 AStar 로직 구현 및 [오픈소스화 진행](https://github.com/battlecook/AStar)
- 클라이언트 로직을 서버 구현을 위해 벡터 기능 구현 및 [선형대수 오픈소스](https://github.com/mcordingley/LinearAlgebra) 공헌


## 유니티를 이용한 모바일 게임 개발

*(2018.1 - 2018.6)*

모바일 게임 클라이언트 역량 강화를 위해 개인적으로 진행했던 프로젝트

- 유니티 코루틴 동작방식 이해
- 간단한 게임 클라이언트 구현

개발 블로그 
--------------------

[battlecook.github.io](https://battlecook.github.io/)

학력
---------

[국민대학교](https://www.kookmin.ac.kr/home.php) 컴퓨터 공학과 (2005-2011)




<details>
<summary>show / hide</summary>
<div markdown="1">

*****
R&D Team ( 2020.7 - 2021.3 )
*****

* Development environment
    * python
    * pycharm
    * bigqueryml, tensorflow

* Main task
    * user clustering for abuser detection using ml kmeans
    * anomaly detection using autoencoder

***** 
Dancechan ( 2019.6 - 2020.7 ) <br>
DanceVille ( 2015.2 - 2019.6 )
*****

* Development environment
    * centos, nginx + phpfpm, memcached, redis, mysql, golang
    * scribe, fluentd
    * docker
    * git(bitbucket)
    * phpstorm, goland

* Main task
    * Lead Programmer
    * Modern php
        * apply php7
        * using composer
        * using phpunit
        * implement acceptance test tool (using dbunit)

    * Web server design
        * implementation of multiple repository transactions at the application level
        * database load balancing implementation

    * Apply code review culture to team
    * Game contents implementation (Quest and many)
    * Game contents implementation with golang in tcp server (Pet and many)

* Major Achievements
    * service launching

*****
Tower Defense (Infinite War) ( 2013.10 - 2014.6 ) <br>
Kokoma Travel ( 2013.2 - 2013.9 ) <br>
Derbydays ( 2011.9 - 2013.1 )
*****

* Development environment
    * centos, nginx + phpfpm, memcached, mysql
    * scribe
    * svn
    * eclipse

* Main task
    * total game contents implementation
    * all communication necessary for game server (development, hardware infrastructure, etc.)
    * write unit test

* Main Achievements
    * kakao platform launching
    * global service launching



</div>
</details>
