---
title: "스위프트 클래스 익스텐션2"
date: 2019-04-30 21:42:00 -0400
categories: iOS
---
표준 Double 클래스에 두 배와 세 배의 값을 반환하는 속성을 추가
<br>
<br>
이 기능은 다음의 익스텐션 선언부를 이용하여 추가할 수 있다.<br>
extension Double {<br>
var squared : Double {<br>
 return self * self<br>
 }<br>
 var cubed : Double {<br>
 retrun self * self * self<br>
  }<br>
 }
 <br>
 <br>
  
이제는 다음과 같이 이용할 수 있다.
- let myValue : Double = 3.0
- print(myValue.squared)  //9.0
<br>
<br>
myValue 상수를 선언할 때 Double형이 되도록 선언하고 익스텐션 속성을<br>
사용했는데  이 속성은 하위 클래스를 사용하는 것이 아니라 익스텐션으로 추가된<br>
것이므로, 우리는 Double 값에서 직접 이 속성에 접근할 수 있다.
- print(3.0.squared)
- print(3.0.cubed)

<br>
<br>
익스텐션은 하위 클래스를 사용하지 않고 클래스에 기능을 혹장할 수 있는 빠르고<br>
편리한 방식을 제공한다.
<br>
<br>
익스텐션을 이용해서는 클래스에 있는 기존의 기능을 오버라이드할 수 없으며<br>
익스텐션은 stored property를 포함할 수도 없다.
![extension2](/img/extension2.png)
