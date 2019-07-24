# 메신저 만들기

## 1. 요구사항

* 반응형으로 개발

* 하나의 아이디에 여러 클라이언트 메시지 동기화 기능

* 파일이나 이미지도 업로드 가능하면 좋겠음

* 모바일에서는 앱처럼 사용가능

  

## 2. 적용기술

* PWA 활용

  * React나 Vue를 사용하여 개발

  [구글 PWA 가이드]: https://developers.google.com/web/fundamentals/codelabs/your-first-pwapp/?hl=ko
  [PWA란?]: https://altenull.github.io/2018/02/25/%ED%94%84%EB%A1%9C%EA%B7%B8%EB%A0%88%EC%8B%9C%EB%B8%8C-%EC%9B%B9-%EC%95%B1-Progressive-Web-Apps-%EB%9E%80/

* 웹푸시를 통한 브라우져 알림 기능

  [webPush]: https://developers.google.com/web/fundamentals/codelabs/push-notifications/?hl=ko

* polling 서버와 메시지 수신 서버는 모두 비동기서버로 개발
  + spring-boot과 jetty 기반으로 서버 구성
  + 고객정보 및 토큰 관리는 RDB
    + MySql 또는 MairaDB
  + 메시지는 NOSQL
    * 어떤 DB를 사용할지 고민중



## 3. 개발환경

* CI & CD 환경 구축

  [CI & CD 구축기]: http://woowabros.github.io/experience/2018/06/26/bros-cicd.html

* Docker 사용

  [도커란]: https://subicura.com/2017/01/19/docker-guide-for-beginners-1.html

* 구글클라우드 서버 사용

  * 100 달러 무료라는 이야기를 들음. 

