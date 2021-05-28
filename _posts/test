--- 
layout: single 
title: "조건문" 
toc: true 
toc_sticky: true 
toc_label: "페이지 주요 목차" 
categories: "형성평가"
--- 
### 01. 이 달은 며칠까지 있을까? 
![callenderl](/assets/images/형성평가.png) 
~~~c 
#include <stdio.h> 
int main(void) 
{ int year, month; 
  
 printf("연도와 월을 입력하세요 : "); 
 scanf("%d%d", &year, &month); 
 printf("%d년 %d월의 마지막날은 ", year, month); 
  
 if(month==1||month==3||month==5||month==7||month==8||month==10||month==12)  printf("31일"); 
 else if(month==4||month==6||month==9||month==11) 
 printf("30일"); 
 else 
 { 
 if((year%4==0 && year%100!=0) || year%400==0)
 printf("29일"); 
 else 
 printf("28일"); 
 } 
 printf("입니다.\n"); 
 return 0; 
}
~~~ 
