---
title: "guard문(조건식이 거짓이면 실행)"
date: 2019-04-03 18:36:28 -0400
categories: iOS
---
guard문은 스위프트 2에 도입된 구문이다.
<br>
<br>
guard문은(Boolean) 표현식을 포함하며, 참(true)인지를 판단하는 이
<br>
표현식은 실행될 코드 다음에 온다.
<br>
<br>
guard문은 표현식이 거짓(false)으로 판단될 경우에 수행될 else 절을 반드시 포함해야 한다.
<br>
- else 절에 속한 코드는 현재의 코드 흐름을 빠져 나갈 수 있는 구문(즉, return, break, continue, throw 구문)을 반드시 포함해야 한다.
- 또는 자기 자신을 반환하지 않는 다른 함수를 else 코드 블록 안에서 호출할 수도 있다.
<br>
<br>
guard <불리언 표현식> else{
<br>
// 표현식이 거짓일 경우에 실행될 코드
<br>
<코드 블록을 빠져 나갈 구문>
<br>
}
<br>
// 표현식이 참일 경우에 실행되는 코드는 이곳에 위치
<br>
<br>
guard문은 기본적으로 특정 조건에 맞지 않을 경우에 현재의 함수나
<br>
반복문에서 빠져 나갈수 있도록 하는 '조기 출구(early exit)' 전략을
<br>
제공한다.
![guard](/img/guard.png)
