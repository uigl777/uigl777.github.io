---
title: "Any와 AnyObject"
date: 2019-05-28 20:27:28 -0400
categories: iOS
---
AnyObject
- AnyObject can represent an instance of any class type.
- 범용타입이다
- 상속관계가 아니라도 타입 캐스팅 가능한 타입이다
- 어떤 클래스의 객체도 저장 가능하다
- 가장 추상화된 최상위 클래스(Obj-C의 NSObject)
- 클래스만 허용하며 구조체나 열거형은 허용하지 않는다


Any
- Any can represent an instance of any type at all, including function types.
- 클래스, 구조체, 열거형, 함수타입도 가능하다
![Any1](/img/Any1.png)
