---
title: "클로저 표현식"
date: 2019-04-12 16:22:00 -0400
categories: iOS
---
클로저 표현식은 매개변수를 받거나, 값을 반환하도록 만들 수도 있음<br>
{(\<매개변수 이름\>:\<메게변수 타입\>, ...) -> \<반환 타입\> in<br>
  //클로저 표현식 코드<br>
 }
 <br>
 <br>
 클로저 표현식 구문은 함수를 선언하는 것과 비슷
 <br>
 <br>
 다만, 클로저 표현식은 이름을 따로 갖지 않으며, 매개변수와 반환타입은 중괄호 안에 들어가고, in 키워드는 클로저 표현식 코드가<br>
 시작함을 가리키는 데 사용 
 <br>
 <br>
 사실, 함수는 이름이 있는 클로저 표현식임
 <br>
 <br>
 클로저 표현식은 비동기 메서드 호출을 위한 완료 핸들러를 선언할 때 종종 사용됨
 ![closure](/img/closure.png)