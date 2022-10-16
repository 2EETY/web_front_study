# Web Front Study
## 스터디 목표
> * 약 9 ~ 10주에 걸친 노마드 코더의 ["바닐라 JS로 크롬 앱 만들기"](https://nomadcoders.co/javascript-for-beginners/lobby) 강의 수강


## 일정
> ### **진도 계획**
> 
* **09/19(월) ~ 09/25(일)**
  * #1.0 Welcome ~ # 1.6 Online IDE
  
* **09/26(월) ~ 10/02(일)**
  * #2.0 First JS Project ~ #2.8 Function part Two
  
* **10/03(월) ~ 10/09(일)**
  * #2.9 Recap ~ #2.16 Recap
  
* **10/10(월) ~ 10/16(일)** 
  * #3.0 The Document Object ~ #3.8 CSS in Javascript part Three
  
* **10/17(월) ~ 10/23(일)** 
  * #4.0 Input Values ~ #4.7 Super Recap
  
* **10/24(월) ~ 10/30(일)**
  * #5.0 Intervals ~ #5.3 Recap
  
* **10/31(월) ~ 11/06(일)**
  * #6.0 Quotes ~ #7.3 Saving To Dos
  
* **11/07(월) ~ 11/13(일)**
  * #7.4 Loading To Dos part One ~ #8.2 Conclusions


## 정리
* **09/19(월) ~ 09/25(일)**
  
  * #1.0 : JS 공부 시작
  * #1.1 : JS를 이용해 앞으로 할 것들
  * #1.2 : HTML과 CSS와 같은 지식적 요구사항
  * #1.3 : 최소한의 소프트웨어적 요구사항
  * #1.4 : JS의 역사 및 장점, 필요성
  * #1.5 : JS가 활용된 예시, JS의 실용성
  * #1.6 : 환경적으로 VScode를 사용할 수 없는 사람을 위한 Replit 소개
 
* **09/26(월) ~ 10/02(일)**

  * #2.0 : JS, CSS, HTML의 관계
  * #2.1 : 데이터 타입의 기초(`int`, `float`, `string`)
  * #2.2 : Variable(변수) 소개, Constant(상수) 인 변수 활용
  * #2.3 : `const` 와 `let`의 차이, `var` 소개
    * `const` - 변수 재할당 불가능
    * `let` - 변수 재할당 가능
    * ! `const` 와 `let` 은 변수 재선언 불가능하지만 `var`은 가능
  * #2.4 : 데이터타입 `boolean` 소개, `null`, `false`, `undefined`의 차이
    * `boolean`은 `ture` 혹은 `false` 값을 가짐
    * `null`은 데이터가 존재하지 않음(비어있음) / `false`는 데이터 값이 `false` / `undefined`는 정의되지 않음(메모리상으로 인식되지만 값이 없음) 
  * #2.5 : Array(배열)`[]` 소개, `array` 활용
    * ex) `const Num = ["1", "2", "3"]'`
    * `funtion` 중 `push`로 추가 가능
  * #2.6 : Object(객체)`{}` 소개, `object' 활용
    * ex) `const Person = {name: "Lee", ...};`
  * #2.7 : Function(함수)`()` 소개, `function` 제작 및 활용
    * ex) `function Hi() {console.log("Hello");} Hi();`
  * #2.8 : `function`의 활용 , Argument(인수)에 대한 이해
    * ex) `funtion Person(name, age) {console.log(name + " and " + age);} Person("Lee", 23)`

* **10/03(월) ~ 10/09(일)**

  * #2.9 : #2.0 ~ #2.5 복습
  * #2.10 : #2.6 ~ 2.8 복습, `object`와 `funciton`을 이용해 계산기 제작
  * #2.11 : `return` 소개
    * 특정 작업을 수행하고 결과값을 `return`함
    * `function`과 `return`의 관계 - `function` 내부에 `return`을 사용할 경우 해당 `function`을 호출한 코드의 값은 `return` 값을 받아옴
    * `function` 내부에서 `return` 을 하면 `function`이 종료됨
  * #2.12 : #2.11 복습
  * #2.13 : Conditionals(조건문)`if`, `else` 소개
    * 사용자에게 메시지를 보내고 값을 입력받는 `prompt()`
    * `parseInt` - String을 Number로 바꿔줌
  * #2.14 : 조건문 활용
    * `isNaN` - Number값을 인자로 받아 number 인지 아닌지 `boolean`값으로 return함 (number값이 아니면 true, number 값이면 false)
    * `if(condition) { //condition === true } else { //condition === false }`
  * #2.15 : `else if` 소개
    * `if(condition) { //condition === false } else if { //condition === false } else { //condition === true }`
    * Condtion에서 Operator(연산자) :  AND의 역할 `&&`, OR의 역할 `||`
  * #2.16 : #2.15 복습
    * Condtion에서 Operator(연산자) : 같다 혹은 IS의 역할 `===`, IS NOT 의 역할 `!==`
    
 **10/10(월) ~ 10/16(일)**
 
  * #3.0 : JS를 이용해 HTML과 상호작용 가능, HTML의 요소들을 JS로 읽거나 변경이 가능함. 콘솔창을 통해 HTML 코드를 JS의 관점으로 확인이 가능함.
  * #3.1 : document로 JS에서 HTML로 접근 가능
    * `document.getElementById()`로 `string`을 전달 받음
    * JS는 HTML의 element를 가져오지만 HTML 자체를 보여주진 않음
    * HTML의 항목들을 가져와 JS를 통해 변경할 수 있음
  * #3.2 : 한번에 많은 element를 가져와야 하는 경우 `getElementsByClassName()` 사용
    * `querySelector`는 element를 CSS방식으로 가져 올 수 있음 
         `ex) const title = document.querySelector("h1');` -> 특정 클래스 내부의 h1을 가져옴 
    * `querySelectorAll`은 
  * #3.3 : 
  * #3.4 : 
  * #3.5 : 
  * #3.6 : 
  * #3.7 : 
  * #3.8 : 
  
  
  
