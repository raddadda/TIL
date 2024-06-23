## 자료구조

> Array
- 특징 : 순차적으로 데이터를 저장한다.
- 장점 : 인덱스가 존재하여 데이터에 순서가 있고, 이를 이용해 특정 요소를 검색하고 수정하는 것이 가능하다.
- 단점 : 순차적으로 존재하는 데이터의 중간에 요소가 삽입 또는 삭제되면 뒤의 모든 요소들을 한칸씩 당겨줘야한다. 


> Stack
- 특징 : 후입선출, 나중에 들어간 원소가 먼저 나오는 구조
- 사용 예 : 자바의 Stack 메모리 영역 , 지역 변수와 매개변수 데이터값이 저장되는 공간, 메소드 호출시 메모리에 할당되고 종료되면 메모리가 해제된다. 
> Queue
- 특징 : 선입선출 , 먼저 들어간 원소가 먼저 나오는 구조
- 사용 예 : OS의 스케쥴러 , 메모리에 적재된 다수의 프로세스 중 어떤 프로세스에게 자원을 할당할 것인가 그 순서를 결정하는 것이 중요한데 이때 가장 단순한 형태의 스케쥴링 정책으로 Queue가 있다.
> Tree
- 특징 : 비선형 자료구조, 계층적 관계를 표현하기 좋음

> Heap
- 특징 : 최댓값, 최솟값을 찾아내는 연산에 좋음, 각 노드의 키값이 자식의 키값보다 작지 않거나(최대힙),
자식의 키값보다 크지않은 (최소힙) 완전 이진 트리


## Array와 ArrayList의 차이점

Array는 크기가 고정적이고 , ArrayList는 크기가 가변적이다.
Array는 초기화 시 메모리에 할당되어 ArrayList보다 속도가 빠르다.
ArrayList는 데이터 추가 및 삭제 시 메모리를 재할당하기 때문에 속도가 Array보다 느리다.

## Array와 LinkedList의 장,단점

Array는 인덱스로 해당 원소에 접근할 수 있어 찾고자하는 원소의 인덱스값을 알고있으면 O(1)에 해당 원소로 접근할 수 있다.
하지만 삽입,삭제과정에서 각 원소들을 shift해줘야 하는 비용이 생겨 이 경우는 O(n)이 된다는 단점이 있다.

LinkedList는 각각의 원소들은 자기 자신 다음에 어떤 원소인지만을 기억하고 있기 때문에 이 부분만 다른 값으로 바꿔주면 삽입과 삭제를 
원하는 위치에 한번에 접근할 수 없다는 단점이 있다.
원하는 위치에 삽입을 하고자하면 원하는 위치를 Search 과정에 있어서 첫번째 원소부터 다 확인해야한다.

## 해시 테이블과 시간 복잡도

해시테이블은 (Key,Value)로 데이터를 저장하는 자료구조 중 하나로 빠르게 데이터를 검색할 수 있는 자료구조다.
검색속도가 빠른 이유는 내부적으로 배열을 사용하여 데이터를 저장하기 때문이다.
각 Key값은 해시함수에 의한 고유한 index를 가지게 되어 바로 접근할 수 있어 시간복잡도가 평균 O(1)이다.

## Hash Map 과 Hash Table의 차이점

해시 테이블 : 병렬 처리를 할때 (동기화를 고려해야하는 상황) Thread-safe하다.
Null 값을 허용하지 않는다.
해시 맵 : 병렬 처리를 하지 않을 때 (동기화를 고려하지 않는 상황) Thread-safe하지 않는다.
Null 값을 허용한다.

## 이진탐색트리와 이진 트리

이진트리는 자식 노드가 최대 두 개인 노드들로 구성된 트리
이진 탐색 트리는 이진 탐색과 연결리스트를 결합한 자료구조
이진 탐색의 효율적인 탐색 능력을 유지하면서 빈번한 자료입력과 삭제가 가능하다는 장점이 있다.
이진 탐색 트리는 왼쪽 트리의 모든 값은 반드시 부모 노드보다 작아야하고 오른족 트리의 값은 부모 노드보다 커야한다는 특징이 있다.
이진 탐색 트리의 시간복잡도는 O(h)이다.
이진 ㅌ