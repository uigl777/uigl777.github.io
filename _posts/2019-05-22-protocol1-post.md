---
title: "스위프트 프로토콜(protocol)"
date: 2019-05-22 23:54:28 -0400
categories: iOS
---
클래스: 인터페이스 + 구현
<br>
<br>
프로토콜: 인터페이스
- 구현 불가 -> 단독 사용 불가
- 클래스, 구조체와 함께 사용
- 메소드, 프로퍼티 구현 약속

프로토콜 정의
<br>
protocol ProtocolName{<br>
}
<br>
<br>
프로토콜 채택<br>
class ClassName : ProtocolName{<br>
}
<br>
<br>
부모 클래스는 첫 번째, 프로토콜은 두 번째부터
