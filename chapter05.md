## 표현식과 문

지금까지 살펴본 내용에서 "값"이라는 용어가 자주 등장했다. <br>
"값"이라는 용어를 알고 있다고 생각하겠지만, 막상 설명하려 하면 난감할 수 있다.

#### 개념을 이해한다는 것은 바로 용어를 정확히 이해하고 설명할 수 있다는 것이다.

<br>

## 값
값은 식이 평가되어 생성된 결과를 말한다. <br>
평가란 식을 해석해서 값을 생성하거나 참조하는 것을 의미한다. <br>

```
10 + 20;
```

<br>

변수는 하나의 값을 저장하기 위해 확보한 메모리 공간 자체 또는 그 메모리 공간을 식별하기 위해 붙인 이름이라고 했다.
##### 따라서 변수에 할당되는 것은 값이다.

<br>

```
var sum = 10 + 20;
```

위 예제의 sum 변수에 할당되는 것은 10 + 20이 아니라 10 + 20이 평가된 결과인 숫자 값 30이다.

<br>

## 리터럴
리터럴은 사람이 이해할 수 있는 문자 또는 약속된 기호를 사용해 값을 생성하는 표기법을 말한다. <br><br>

```
3
```

위 예제의 3은 단순한 아라비아 숫자가 아니라 숫자 리터럴이다.

<br>

## 표현식
표현식은 값으로 평가될 수 있는 문이며, 평가되면 새로운 값을 생성하거나 기존 값을 참조한다. <br><br>

```
var score = 100;
```


위 예제의 100은 리터럴이며, 자바스크립트 엔진에 의해 평가되어 값을 생성하므로 리터럴은 그 자체로 표현식이다. <br><br>

```
var score = 50 + 50;
```

50 + 50은 리터럴과 연산자로 이뤄져 있다. <br>
하지만 50 + 50도 평가되어 숫자 값 100을 생성하므로 표현식이다. <br><br>

표현식은 쉽게 말하면, 값으로 평가될 수 있는 문은 모두 표현식이다.

```
10
'Hello'

sum
person.name
arr[1]

10 + 20
sum = 10
sum !== 10

square()
person.getName()

```

<br>

## 문
앞으로 자바스크립트를 설명할 때 문과 표현식이라는 용어가 자주 등장할 것이다. <br>

#### 문은 프로그램을 구성하는 기본 단위이자 최소 실행 단위이다. <br>
#### 토큰이란 문법적인 의미를 가지며, 더 이상 나눌 수 없는 코드의 기본 요소를 의미한다. <br>
