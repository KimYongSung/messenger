# 메신저 만들기

## 1. 요구사항

* 반응형으로 개발

* 하나의 아이디에 여러 클라이언트 메시지 동기화 기능

* 파일이나 이미지도 업로드 가능하면 좋겠음

* 모바일에서는 앱처럼 사용가능

## 2. 적용기술

* React + typescript

* 웹푸시를 통한 브라우져 알림 기능

  webPush: [https://developers.google.com/web/fundamentals/codelabs/push-notifications/?hl=ko](https://developers.google.com/web/fundamentals/codelabs/push-notifications/?hl=ko)

* 메시지 브로커 구성 및 메시지 수신 서버 비동기서버로 개발
  + 메시지 브로커 사용
     * [RabbitMQ](https://ko.wikipedia.org/wiki/RabbitMQ)
     * [kafka](https://kafka.apache.org/)
  + spring-webflux
  + 고객정보 및 토큰 관리는 RDB
    + MySql 또는 MairaDB
  + 메시지는 NOSQL
    * redis 사용

## 3. 개발환경

* CI & CD 환경 구축

  CI & CD 구축기: [http://woowabros.github.io/experience/2018/06/26/bros-cicd.html](http://woowabros.github.io/experience/2018/06/26/bros-cicd.html)

* Docker 사용

  도커란 : [https://subicura.com/2017/01/19/docker-guide-for-beginners-1.html](https://subicura.com/2017/01/19/docker-guide-for-beginners-1.html)

* 구글클라우드 서버 사용

  * 100 달러 무료라는 이야기를 들음. 

