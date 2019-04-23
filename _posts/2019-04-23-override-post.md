---
title: "상속받은 메서드 오버라이딩 하기"
date: 2019-04-23 20:13:00 -0400
categories: iOS
---
상속받은 메서드를 오버라이드(override)하여 하위 클래스 내에 새로운 버전의 메서드를 만듦
<br>
<br>
메서드 오버라이딩을 할 때 반드시 따라야 할 두 가지 규칙

- 하위 오버라이딩 메서드는 오버라이딩되는 부모 클래스 메서드의 인자 개수와 타입이 정확하게 일치해야 한다.
- 부모 클래스 메서드가 반환하는 타입과 일치해야 한다.

BankAccount 클래스에는 은행 계좌 번호와 현재 잔고를 표시하는<br>
displayBalance라는 이름의 메서드가 있다.
<br>
<br>
하위 클래스인 SavingsAccount에서는 계좌에 할당된 현재 이자율도 출력하고 싶다.
<br>
<br>
이를 위하여 override 키워드가 앞에 붙은 displayBalance 메서드의 새로운 버전을<br>
SavingsAccount 클래스에 선언한다.
[override1](/img/override1.png)

