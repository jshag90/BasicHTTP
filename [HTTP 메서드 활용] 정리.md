[HTTP 메서드 활용] 정리

클라이언트에서 서버로 데이터 전송 4가지 상황

- 정적 데이터 조회

  - 이미지, 정적 텍스트 문서

- 동적 데이터 조회

  - 주로 검색, 게시판 목록에서 정렬 필터(검색어)

- HTML Form을 통한 데이터 전송

  - 회원 가입, 상품 주문, 데이터 변경

- HTTP API를 통한 데이터 전송

  - 회원 가입, 상품 주문, 데이터 변경

  - 서버 to 서버, 앱 클라이언트, 웹 클라이언트(Ajax)

HTTP API 데이터 전송 정리

- 서버 to 서버

  - 백엔드 시스템 통신

- 앱 클라이언트

  - 아이폰, 안드로이드

- 웹 클라이언트

  - HTML에서 Form 전송 대신 자바 스크립트를 통한 통신에 사용(AJAX)

  - 예) React, VueJS 같은 웹 클라이언트와 API 통신

- POST, PUT, PATCH: 메시지 바디를 통해 데이터 전송

- GET : 조회, 쿼리 파라미터로 데이터 전달

- Content-Type: application/json을 주로 사용(사실상 표준)

  - TEXT, XML, JSON 등등



HTTP API 설계 예시

- HTTP API - 컬렉션

  - POST 기반 등록

  - 예) 회원 관리 API 제공
  - 서버가 리소스 URI 결정

- HTTP API - 스토어

  - PUT 기반 등록

  - 예) 정적 컨텐츠 관리, 원격 파일 관리
  - 클라이언트가 리소스 URI 결정

- HTML FORM 사용

  - GET, POST만 지원
  - 예) 웹 페이지 회원 관리

  - 순수 HTML+HTML form 사용

