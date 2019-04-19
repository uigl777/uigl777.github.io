---
title: "스위프트 상속 예제"
date: 2019-04-19 12:44:00 -0400
categories: iOS
---
SavingsAccount라는 BankAccount의 하위 클래스를 생성하기 위해<br>
새로운 클래스를 선언하고 부모 클래스로 BankAccount를 지정<br>
<br>
class SavingsAccount : BankAccount { //class 자식:부모
}
<br>
<br>
아직은 어떠한 인스턴스 변수나 메서드를 추가하지 않았지만, 이<br>
클래스는 부모인 BanckAccount 클래스의 모든 메서드와 속성을 상속받음
<br>
<br>
SavingsAccount 클래스의 인스턴스를 생성하고,<br>
변수를 설정하고 메서드를 호출할 수 있음
