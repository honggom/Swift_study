# day-01 (2021-02-21)
- 상수 선언 === let 상수명: 타입 = 값 
- 변수 선언 === var 변수명: 타입 = 값 
---
### swift 기본(primitive)타입 
 - Bool : true, false
 - Int : 정수
 - UInt : 양의 정수
 - Float : 실수 32비트 
 - Double : 실수 64비트 
 - Chracter
 - String<br>
 기본적으로 swift는 서로 다른 타입과 자료 교환은 암시적으로 불가능 
 ---
 ### Any, AnyObject, nil 
  - Any : 모든 타입을 지칭하는 키워드 
  - AnyObject : 모든 클래스 타입을 지칭하는 프로토콜
  - nil : 없음을 의미하는 키워드 
 ---
 ### Array, Dictionary, Set
  - Array : 순서가 있는 리스트 컬렉션<br>
     >.append() : 요소 추가 
     >.contains() : 해당 요소가 있나 확인 true, false 리턴 
     >.remove(at :0) : 0번째 방의 요소 삭제 
     >.removeLast() : 마지막 요소 삭제 
     >.removeAll() : 전체 요소 삭제 
     >.count() : 개수 확인 
     >Array[0] : 0번째 변수로 접근 
  - Dictionary : 키와 값의 쌍으로 이루어진 컬렉션<br>
     >anyDic["someKey"] = "someVal" ... 이런식으로 할당 
     > - anyDic.removeValue(forKey: "someKey")
     > - anyDic["someKey"] = nil 
  - Set : 순서가 없고, 멤버가 유일한 컬렉션
