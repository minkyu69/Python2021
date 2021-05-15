# (박민규)파이썬 기초 공부하기
## 05.13 파이썬 기초 (python01.ipynb)
### 입력 : input() => 정수(int), 실수(float)를 입력할 경우 형변환
### 출력 : print() => f-string
### 조건문 : if문
  * if ... : 명령문 elif ... : 명령문 else :
### 반복문 : for문, while문 
  * for문 => rnage()
## 05.14 컬렉션 자료형 (python02.ipynb)
### ※ 컬렉션 자료형
  * 여러 요소를 묶어서 처리할 수 있는 자료형 
  * 각 요소에 접근하는 방법이 제공
### 문자열(str)
#### 문자열 인덱싱
  * 문자열의 각 문자는 0부터 시작되는 인덱스를 가짐
  * [인덱스]를 이용하여 인덱스위치의 문자 추출 : 처음위치 [0], 마지막위치 [-1]
#### 문자열 슬라이싱
  * [인덱스1:인덱스2]: 인덱스1 위치에서 인덱스2 -1 위치까지 잘라냄
  * [인덱스1:] : 인덱스1 위치에서 끝까지 잘라냄
  * [: 인덱스2] : 처음부터 인덱스2 -1 위치까지 잘라냄
#### 문자열 연산
  * 문자열 더하기(+)
  * 문자열 곱하기(*)
#### 문자열 메소드
  * len() : 문자열 길이 구하기
  * count() : 문자의 개수 구하기
  * find() : 문자가 처음 나오는 위치 반환 , 없으면 -1
  * index() : 문자가 처음 나오는 위치 반환, 없으면 오류
  * join() : 문자열 사이에 문자 삽입, 삽입문자’.join(문자열)
  * upper() :소문자를 대문자로 변환
  * lower() : 대문자를 소문자로 변환
  * replace() : 문자열 바꾸기
  * replace(원본, 변환문자)
  * split() : 문자열 나누기
  * 인수가 없으면 공백(스페이스, 탭, 엔터 등)을 기준
### 리스트(list)
  * 요소에는 숫자, 실수, 문자열, 리스트 ... : 여러가지 자료형을 가질 수 있다.
  * 각 요소에 접근하는 방법 : 인덱싱 => 요소의 위치 0부터 시작 (X[0])
  * 일부 요소를 추출하는 방법 : 슬라이싱 => 범위 지정 x[0:3] = 0,1,2
  * 전체 요소 접근 방법 : for .. in 컬렉션형
#### 리스트 변경
##### ○ 추가 
  * 리스트명.append(추가요소) : 마지막에 추가
  * 리스트명.insert(인덱스, 추가요소) : 해당 인덱스에 요소 추가
##### ○ 삭제
  * 리스트명.pop() : 마지막 요소 삭제
  * 리스트명.pop(인덱스) : 해당 인덱스 요소 삭제
  * 리스트명.remove(요소값) : 해당 요소값 삭제, 해당 값이 없으면 오류
##### ○ 수정
  * 리스트명[인덱스]=변경값
  * (참고) isinstance()함수 : 특정 객체가 특정 타입인지에 대해서 확인할 수 있는 방법
#### 리스트 메소드
##### 리스트명.index(요소값) : 해당 요소값의 위치를 반환
  * 여러 개 요소가 존재하면 첫번째 위치 반환하고 없으면 오류
##### 리스트명.count(요소값) : 리스트 요소 개수 구하기
##### 리스트명.sort() : 오름차순 리스트 정렬
  * 리스트명.sort(reverse=True): 내림차순
##### 리스트명.reverse() : 요소를 역순으로 뒤집어 줌
#### 리스트 내장함수
  * sum() : 리스트의 합을 반환
  * min() : 리스트 최소값 반환
  * max() : 리스트 최대값 반환
  * len() : 리스트 개수 반환
### 튜플(tuple)
  * 튜플의 각 요소는 순서를 가지고 있음
  * 괄호(())로 작성되며 각 요소는 쉼표(,)로 구분
  * 요소를 추가, 수정, 삭제 불가능
  * 한번 결정된 요소는 변경 불가능
  * 인덱싱과 슬라이싱은 리스트와 동일
  * + 와  ∗ 연산은 리스트와 동일
  * 각 요소에 변수 할당 가능
    * x, y = (10, 20)
# 재현아 안녕
