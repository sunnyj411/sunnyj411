---
title: "2/11 HTML header"
date: 2016-02-11 23:57:00 -0400
---
# 2/11 HTML header
 ## Setcookie
 - 서버에서 쿠키를 생성하면 헤더를 통해 SetCookie라는 정보를 클라이언트에 전송
 - 클라이언트 reponse 에 쿠키가 있으면 browser 에 쿠키 정보를 설정함
 - 클라이언트에서 갖고있는 쿠키는 browser가 매번 서버에 헤더에 넣어서 보냄
## expires
 - data 의 형식으로 문서가 변경될수도 있을 때 시간 또는 그 정보가 유효하지 않을 때의 시간을 명시
 - 설정된 시간 이후, 문서는 변경 또는 삭제가 되지 않을 수 있음 
## strict-transport-security
- HTTP 보안 연결에 사용하는 것
- 해당 헤더를 사용하면 http:// 를 사용해도 항상 https:// 로 접속 함
- SSL Strippping 공격 차단
