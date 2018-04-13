# Python 기본문법

Python study by codingdojang 2018.04

## List and Tuple

**list**와 **tuple**은 어떠한 데이터 타입도 받아올 수 있다. 
이런 이유로 어떤 데이터가 들어 올 지 예상하기 힘든 빅데이터에 파이썬이 적합하다 볼 수 있다. 

## Sequence slicing 
[start:end:step] 형태로 데이터를 가공하기가 훨씬 편리하다.

## Packing / Unpacking 
Info = 'James', 'male', 27 라고 입력하면 info 의 type 은 자동적으로 **tuple** 이 된다. 

## Dictionary 
**d = dict()** 으로 생성한 후, d[여기!] 여기에 왠만하면 숫자는 넣지말고 문자열로 하는 것이 좋다. 예) d['key'] 

## Set 
list와 tuple 과 마찬가지로 자료형이지만 중복을 허용하지 않는다. 

## 함수
##### 위치인자(Positional arguments)
> 장점 : 몇개의 매개변수가 들어올지 제한을 두지 않아도 된다. 
데이터형에도 제한이 없는 것은 물론.

##### 키워드인자(Positional arguments)
> 매개변수를 딕셔너리로 묶는다.

##### 컴프리헨션 
> 긴 반복문을 리스트 컴프리헨션을 통해 간략하게 조건문과 반복문을 결합할 수 있도록 한다.
[x for x in range(10) if x%2==0]

##### 시간을 측정하는 Dacorator 함수 예시
![MacDown logo](/Users/choibowon/Desktop/Decorator.png)

#### Iterable Iterator 
> * **Iter()** 는 파이썬에 내장된 메소드로 어떤 리스트를 iterator 로 만들어준다.
 
> * 데이터를 한번에 쌓아놓고 계속 사용하는 것이 아니라, 필요할 때마다 **next()** 를 통해서 
호출하기 때문에 메모리 효율을 좋게 한다. 메모리 적재량을 줄인다.

> * **Interator 는 interable 하고 interator 이다.**
 

##### 예시
![MacDown logo](/Users/choibowon/Desktop/Iterable Iterator.png)
