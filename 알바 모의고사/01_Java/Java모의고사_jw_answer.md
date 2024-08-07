# Java 모의고사_답안지_jw

## Day01_기초문법

### 1번
```java
// #1: 10100
// #2: 11110
// #3: 10100
// #4: 11110
// #5: 1010
// #6 11111111111111111111111111101011
// #7: -31
// #8: 101000
// #9: 10
```

### 2번
논리 연산자를 사용하여 연산할 때, 앞 연산자의 결과에 따라 뒤 연산자의 실행 여부가 결정되는 계산 방식
* OR(||)의 경우 앞 연산자가 true이면, 이후 연산자는 실행하지 않음
* AND(&&)의 경우 앞 연산자가 false이면, 이후 연산자는 실행하지 않음

### 3번
#결과1: true
#1: 20 , 10
#결과2: true
#2: 20 , 20
이유: 첫 번째 연산은 비트 연산자(|)를 사용한 연산으로, 두 표현식을 모두 실행한 이후에 OR 연산을 수행하였기 때문에 value7, value8의 값이 모두 변하였다.
그러나 두 번째 연산자는 논리 연산자(||)를 사용한 연산으로, 앞에서부터 표현식이 true가 나오면, 이후에 나오는 표현식은 실행하지 않고 true를 반환하는 short-circuit evaluation을 수행하였기 때문에 value8의 경우 값이 변하지 않았다.

### 4. 
개수: 2개
위치: 3번 아래, 7번 아래

### 5.
개념: JVM이란, 자바 바이트코드를 실행할 수 있는 주체로, 자바 바이트코드를 기계어로 번역하여 특정 플랫폼의 실제 하드웨어에서 실행하는 것을 담당한다.
장점: 플랫폼 독립성을 가능하게 한다.

### 6. 
정답: 메인 메서드(main method)

### 7. 
정답: 4, 5

### 8.
%d
%f
%c
%s

### 9. 
1. X
2. O
3. X
4. O
5. X
6. O
7. O
8. X
9. X

### 10. 
정답: instanceof

### 11.
정답: !

### 12.
A: `:`
B: `;`


## Day02_배열

### 1. 
해시코드 값을 비교하기 위한 메서드로, A에 공통으로 들어갈 메서드: hashCode()
numberList2의 인덱스 값: 100

### 2. 
정답: toString()

### 3. 
주소 비교: false

### 4.
1번: X
2번: O
3번: X
4번: O
5번: O

### 5.
1. X
2. X
3. X
4. X



## Day03_클래스

### 1.
정의: 객체지향프로그래밍이란, 객체 단위로 코드를 작성하며, 객체 간의 상호작용으로 프로그램을 설계하는 것을 의미한다.
장점: 코드의 재사용성, 유지보수성, 유연성과 확장성

### 2. 
객체 모델링

### 3. 
상속
다형성

### 4.
class

### 5. 각 설명에 대하여 OX로 답하세요.
1. X, 클래스를 가리키는 게 아니라 현재 인스턴스를 가리키는 것!
2. O

### 6. 
정답: 메서드 체이닝

---

## Day04_객체 배열 관리

### 1.
1번: X, protected <br>
2번: O
<br><br>

### 2.
1. O
2. X
3. X

<br><br>



## Day05_상속

### 1.
1. 연관
2. 양방향 연관
3. 집합
4. 구성
5. 의존
<br><br>

### 2.

Object
<br><br>

### 3. 
1. O
2. X
3. X

## Day06_다형성
### 1. 

1. O
2. O
3. O
4. O
5. O
6. X

<br><br>

### 2.
O, 메모리에는 올라가지만 접근 범위가 달라지는 것.(접근 범위에 제한이 생기는 것)

<br><br> 

### 3.
O, 명시적 형변환을 했지만 에러가 안 나는 경우는! 자손 객체를 만든 다음에 부모 객체로 형 변환했다가 다시 돌아올 때 !!이다.



<br><br>

### 4. 
1. O
2. O
3. O
4. O
5. X
6. O
7. O
8. O, Object class를 모두 상속받는 걸 생각하면 됨! 


### 5. 
1.  parent x
2.  child x
3.  child method
4.  child method
5.  parent static method 
6.  child static method
<br><br>


### 6.
동적 바인딩

<br><br>

### 7.
클래스명 앞에 abstract, 추상 메서드에 마지막 ; 붙이기

<br><br>

### 8. 
상속 관계에 있을 때, 조상 클래스의 타입으로 자식 클래스를 참조할 수 있는 것


## Day07_다형성, 인터페이스

### 1. 
1. X
2. X
3. X
4. X, 클래스는 여러 개의 인터페이스를 다중 구현 가능

<br><br> 

### 2. 
default

<br><br> 

### 3. 
static


## Day_08_컬렉션 프레임워크

### 1. 
1. Set
2. Queue
3. Deque
4. Collection
5. List


### 2. 

1. Collections
2. Arrays


## Day09_예외처리

### 1. 
컴파일은 성공적으로 진행되었으나, 프로그램 실행 중에 발생하는 오류
<br><br>

### 2. 
1. (A) : 언체크 예외
7. (B) : 예외
8. (C) : 에러
9. (D) : throw
10. (E) : finally
11. (F) : printStackTrace()
12. (G) : getMessage() 


