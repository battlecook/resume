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

### Astar

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

* 2019-2021 : 플러터를 이용한 모바일 어플리케이션 개발
* 2017-2019 : 유니티를 이용한 미니게임


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
