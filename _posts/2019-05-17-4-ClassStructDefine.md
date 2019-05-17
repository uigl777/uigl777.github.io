---
title: "클래스/구조체 정의하기"
date: 2019-05-17 17:30:28 -0400
categories: iOS
---
클래스 정의하기
- class 이름{...}

구조체 정의하기
- struct 이름{...}

타입 문자 이름에는 Upper camel를 사용한다.
- 대문자로 시작

클래스/구조체 안의 프로퍼티나 메서드는 lower Camel Case를 사용한다<br>
struct Resolution {<br>
      var width = 0<br>
      var height = 0<br>
}<br>
<br>
class VideoMode {<br>
    var resolution = Resolution()<br>
    var interlaced = false<br>
    var frameRate = 0.0<br>
    var name : String?<br>
 }
