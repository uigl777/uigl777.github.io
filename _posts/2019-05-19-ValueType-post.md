---
title: "구조체나 열거형은 값 타입(value type), 클래스는 참조 타입(reference type)"
date: 2019-05-19 14:10:00 -0400
categories: iOS
---
값 타입은 호출, 대입 등이 일어날 때 복사를<br>
한다는 뜻이다.
<br>
<br>
아래의 예에서, aa는 a와 같은 인스턴스를<br>
가리키는 것이 아니고, 내용을 복사한 새<br>
인스턴스를 만들어 가리킨다.
<br>
<br>
따라서 aa의 프로퍼티를 변경해도 hd에는<br>
영향을 끼치지 못한다.
![ValueType](/img/ValueType.png)
