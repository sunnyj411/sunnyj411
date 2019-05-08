---
title: "http cache control"
date: 2017-11-21 23:14:00 -0400
---
# 11/21 기록
##Cache-Control :
cache-request-directive=
"no-cache" 캐시 하지 않는다.
"no-store" 신속히 넘긴 후에 정보를 제거한다.
"max-age = seconds" seconds에 지정한 것보다 오래된 entry는 캐시하지 않는다.
"max-stale [=seconds]" 만료된 데이터를 보낸다. 만약 seconds가 지정되어 있다면 지정한 숫자보다 적은 만료된 데이터를 보낸다.
"min-fresh [=seconds]" 명시된 seconds의 수 이후의 변경된 새 데이터만 보낸다.
"only-if-cached" 새로운 데이터를 검색하지 않고 캐시에 있는 데이터만 반환한다.

## Cache-Control :
cache-response-directive=
"public" 어떠한 캐쉬라도 캐싱할 수 있다.
"private" 공유된 캐쉬는 캐시하지 않는다.
"no-cache" 캐쉬하지 않는다.
"no-transform" 데이터를 변환하지 않는다.
"must-revalidate" 클라이언트는 데이터를 재확인 해야 한다.
"proxy-revalidate" 개인적인 클라이언트 캐시를 제외하고 데이터를 재확인 해야한다.
"max-age"="delta-seconds" 문서는 지정된 seconds만큼 변화가 없는 상태라고 생각