---
layout: single
title:  "C언어 built-in function 1. printf 함수"
toc: true
toc_sticky: true
toc_label: "예제"
categories: "c언어"
---

**안녕하세요!

**오늘은 c언어의 내장함수 중의 기본인 printf 함수에 대해 배워 보겠습니다.**
printf 함수는 원하는 값 또는 문자(열)를 출력할 때 사용합니다.

사용 형식: printf(" (출력 정보) ", (출력할 값))

### **ex1. "Hello World" 출력하기**
문자열(string)은 " "로 표현합니다.*여기서 ''는 단일 문자를 표현하는 것이니 주의합니다.*

그러면 출력해봅시다.
~~~c
#include <stdio.h>
int main(){
printf("Hello World");
return 0;
}
~~~
### **ex2. 정수 출력하기**
%d 연산자를 사용하면 프린트문에서 원하는 값은 %d 자리에 출력이 가능합니다.

printf("%d",10) 이 구문에서 10이라는 값이 %d 자리에 출력되게 되는 것입니다.

*printf 사용 형식을 꼭 지키도록 합시다. printf("%d ,10") 형태로 사용하면 %d에 출력할 값이 없으므로 에러

그 외 연산자

%f- 실수

%c- 단일 문자

%s- 문자열

...
이상으로 c언어 내장함수 printf에 대한 설명이었습니다.^^
