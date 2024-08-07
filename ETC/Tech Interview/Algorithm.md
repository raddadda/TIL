
## DP

> 동적 계획법
- 주어진 문제를 풀기 위해 문제를 여러 하위문제로 나누어 푸는 방법
- 조건 : 중복되는 작은 부분문제 -> 메모이제이션 기법을 통해 중복 계산을 없앤다.
-> 메모이제이션 : 동일한 계산을 반복 수행 할 때 이전의 계산한 값을 재사용함으로써 동일한 계산 반복수행을 제거하여 프로그램 실행속도를 빠르게하는 기술
> 버블 정렬
- 서로 인접한 두 원소를 비교해서 정렬하는 알고리즘. 
- 시간복잡도 : O(n^2)

> 선택 정렬
- 선택 정렬은 첫 번째 값을 두 번째 값부터 마지막 값까지 차례대로 비교하여 최솟값을 찾아 첫번째에 놓고,
두번째 값을 세번째값부터 마지막까지 비교해 두번째 위치에 최소값을 두는 방식을 반복해 정렬하는 알고리즘
- 시간복잡도 : O(n^2)

> 삽입 정렬
- 삽입 정렬은 오름차순이라면 두번째 값부터 시작해 그 앞에 존재하는 원소들과 비교해 더 작은값이 왼쪽에 오도록 정렬하는 방법이다.
- 시간복잡도 : O(n^2)

> 힙 정렬
- 힙 정렬은 주어진 데이터를 힙 자료구조로 만들어 최댓값 또는 최솟값부터 하나씩 꺼내서 정렬하는 알고리즘

> 병합 정렬
- 병합 정렬은 주어진 배열을 크기가 1인 배열로 분할하고 합병하면서 정렬을 진행하는 분할(divide)/정복(conquer) 방식
- 시간복잡도 : O(nlogn)

> 퀵 정렬
- 퀵 정렬은 피봇을 설정하고 피봇보다 큰값과 작은 값으로 분할해 정렬한다.
- 시간복잡도 : O(nlong)

> 허프만 코딩

- 문자의 빈도수를 가지고 압축하는 과정

> 재귀 알고리즘

함수 내부에서 함수가 자기 자신을 호출하여 문제를 해결하는 알고리즘
자기 자신을 계속해서 호출하기때문에 중단할 조건이 반드시 필요하다.