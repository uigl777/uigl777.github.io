---
title: "In-Out 매개변수로 작업하기"
date: 2019-04-13 01:36:00 -0400
categories: iOS
---
Swift는 기본적으로 call by value
<br>
<br>
Objective-C는 기본적으로 call by reference
<br>
<br>
함수가 값을 반환한 후에도 매개변수에 일어난 변화를 유지하려면,<br>
함수의 선언부에서 매개변수를 입출력 매개변수(in-out parameter)로<br>
선언해야 함
<br>
<br>
Swift에서 call by reference를 구현하는 방법<br>
함수를 호출할 때 입출력 매개변수는 앰퍼샌드(&)를 앞에 붙여주어야 한다.
![inout](/img/inout.png)
