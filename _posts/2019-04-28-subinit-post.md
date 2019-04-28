---
title: "하위 클래스 초기화하기"
date: 2019-04-28 12:10:00 -0400
categories: iOS
---
현재 SavingsAccount 클래스는 부모 클래스인 BackAccount의<br>
init 초기화 메서드를 상속하고 있다.
<br>
<br>
이 메서드는 클래스의 계좌 번호 속성과 잔고 속성 모두를 초기화하는 데 필요한 처리를 한다.
<br>
<br>
하지만 SavingsAccount 클래스는 이자율에 대한 속성이 추가로 있으므로 클래스의<br>
인스턴스가 생성될 때 interestRate 속성이 초기화되도록 해야 한다.
<br>
<br>
SavingsAccount의 init 메서드는 이자율을 초기화하는 작업을 한 다음에 부모<br>
클래스의 init 메서드를 호출하여 모든 변수가 초기화되도록 한다.
![ChildInit](/img/ChildInit.png)
<br>
초기화 과장에서 발생할 수 있는 잠재적인 문제를 피하기 위해서 상위 클래스의 init<br>
메서드는 항상 하위 클래스의 초기화 작업이 완료된 후에 호출되도록 해야 한다.
