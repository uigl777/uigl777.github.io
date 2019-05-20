---
title: "call by value VS call by reference"
date: 2019-05-20 20:22:00 -0400
categories: iOS
---
Swift에서 제공하는 Int, String, Array, Dictionary<br>
등 기본 자료형들은 구조체로 만들어져 있어서<br>
call by value방식이다.
<br>
<br>
enum도 call by value방식이다.
<br>
<br>
클래스는 call by reference방식이다.
<br>
<br>
언제 클래스를 쓰고 언제 구조체를 쓰나?
- 구조체는 간단한 데이터 값들을 한데 묶어서 사용하는<br>
경우
- 전체 덩어리 크기가 작은 경우, 복사를 통해 전달해도<br>
좋은 경우 구조체
- 구조체는 기존 타입의 특성을 상속할 필요가 없다.
