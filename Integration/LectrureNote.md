# LectureNote

## DE01

학습 내용
- 데이터엔지니어링 배경
- 데이터엔지니이렁 소개

자바로 실습

- 데이터
  - 수집 가공 저장의 형태로 진행

- 데이터 저장을 위한 형태로 데이터 처리
  - 추상화, 파싱, 검증, 정제

- 데이터를 특정 목적의 서비스를 만들기 적절한 형태로 유지
  - 메모리, 데이터베이스(강좌에서 메모리 사용)

  - 이클립스, JDK, 메이븐 라이브러리 설치내용

실제 코딩 조금

## DE02

코드 조금..

Array에 관한 이야기

## DE03

Collection Framework

조직 관리 저장을 추상화하여 작업

최상위 인터페이스 Collection

- Collection
  - List
    - ArrayList
    - LinkedList
  - Set
    - HashSet
    - TreeSet

## DE04

MyarrayList를 구현

## DE05

### LinkedList

#### 데이터 추가

- add는 데이터를 추가하고 성공 여부를 반환
- offer는 데이터를 추가하고 성공 여부를 반환

사실 add와 offer는 같은 기능을 수행 (linkedList에서 list에선 다름)

#### 첫 번째 데이터 가져오기

- Peek은 데이터가 없을 때 null을 반환
- element는 데이터가 없을 때 NoSuchElementException을 반환

#### 데이터 제거

Queue에서 작동 (linkedList에서 자체가 queue로 구현, 실제는 덱)

deque에 해당하는 연산

- remove는 첫 번재 요소를 반환하고 제거, 데이터가 없을 때 NoSuchElementException을 반환 (추출)
- poll은 첫 번째 요소를 반환하고 제거, 데이터가 없을 때 null을 반환 (추출)

## DE06

## DE07

### LinkedList

- contains
  - 데이터가 있는지 확인
- get(index)
  - 특정 위치의 인스턴스 추출
- indexOf
  - 특정 인스턴스의 위치 확인 앞에서 부터
- lastIndexOf
  - 특정 인스턴스의 위치 확인 뒤에서 부터

## DE09

hashSet

- 중복을 허용하지 않음
- 순서가 없음

## DE10

