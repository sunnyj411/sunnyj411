---
title: "2/1 javascript 객체, 배열"
date: 2016-02-01 23:24:00 -0400
---
# 2/4 javascript

 - javascript 에서 부동소수점을 사용할 때 더 메모리를 사용하기 때문에 1.0을 '1' 정수로 저장함.
 - NaN => Not a Number
 ex) 
	 - 1/a  => NaN
	 - NaN/10 => NaN
	 - NaN == NaN => false
	 - 'a' => "a" (string)

## javascript 객체

 - object.freeze() : java 의 final과 비슷하고, 값을 변경할 수 없지만 접근은 가능
 - object.seal : 값만 수정 가능, 프로퍼티 추가 X
 - object.assign : 객체 복사 or 합침
 - 객체 생성
	 - 생성자  ex) var obj = new Object();
	 - 리터러리 ex) var obj = { }; 

## 배열
 - push : 크기를 return 하고 뒤에 값을 넣음 <-> pop
 - unshift : 값을 앞에 넣음 <-> shift

## etc..
WAS : 동적 페이지 처리 ex) php, jsp, asp
Webserver : HTML 같은 정적 페이지 처리, 별도로 구성하기 위해 Tomcat, Apache 연동