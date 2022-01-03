URI와 웹 브라우저 요청 흐름 정리

URI(Uniform Resource Identifier)

URL(Resource Locator)

URN(Resource Name)

URI > URL, URN

URN은 거의 안쓰임 

URL

scheme 

- 주로 프로토콜 사용

userinfo

host

PORT

path

query

쿼리 파리미터, 쿼리 스트링

fragment



**웹 브라우저 요청 흐름**

https://www.google.com:443/search?q=hello&hl=ko

DNS 조회 

HTTP 요청 메시지

GET /search?q=hello&hl=ko HTTP/1.1

Host: www.google.com

1. 웹 브라우저가 HTTP 메시지 생성

2. SOCKET 라이브러리를 통해 전달

   A: TCP/IP 연결(IP, PORT)

   B: 데이터 전달

3. TCP/IP 패킷 생성, HTTP 메시지 포함





