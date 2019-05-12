---
title: "스위프트 딕셔너리"
date: 2019-05-12 17:10:00 -0400
categories: iOS
---
배열처럼 빈 딕셔너리를 생성할 수도 있다.
- var 변수 이름 = [키 타입 : 값 타입]\(\)
- var myDictionary = [Int : String]\(\)

딕셔너리의 항목 개수는 count 속성에 접근하여 얻을 수 있다.
<br>
<br>
특정 값은 해당 키를 참조하기 위하여 키 첨자 구문을 이용하면<br>
접근, 수정 가능
<br>
<br>
딕셔너리에 있는 키를 참조하며 해당 값을 출력
<br>
<br>
특정 키와 연관된 값을 갱신 가능
<br>
<br>
updateValue(forKey:) 메서드에 변경된 값과 해당 키를 전달
<br>
<br>
딕셔너리에 항목을 추가
- 딕셔너리 변수[키] = 값

어떤 키-값 쌍을 딕셔너리에서 제거할 때는 nil 값을 그 항목에<br>
할당하거나 딕셔너리 인스턴스의 removeValueForKey 메서드를<br>
호출
![dictionary3](/img/dictionary3.png)
