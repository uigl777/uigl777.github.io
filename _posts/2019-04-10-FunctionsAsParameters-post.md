---
title: "매개변수로 함수를 사용(Functions as Parameters)"
date: 2019-04-10 19:03:00 -0400
categories: iOS
---
스위프트는 함수를 데이터 타입처럼 처리할 수 있음
<br>
<br>
다음과 같이 함수를 상수 또는 변수에 할당하는 것이 가능
![FunctionsAsParameters](/img/FunctionsAsParameters.png)
inchesToFeet라는 이름의 함수를 선언하고, 그 함수를 toFeet이라는 이름의 상수에 할당
<br>
<br>
함수를 호출하려면 원래의 함수 이름 대신에 상수 이름을 이용하여 호출 가능
<br>
<br>
어떤 함수에 다른 함수를 인자로 넘겨주거나 함수의 반환 값으로 함수를 넘겨줄 수 있음
<br>
<br>
함수의 데이터 타입은 매개변수들과 반환 타입의 조합으로 결정
<br>
ex) Int와 Double형을 매개변수로 받아서 String을 반환하는 함수의 데이터 타입 (Int,Double) -> String
