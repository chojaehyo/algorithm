## Bubble Sort

- 서로 인접한 두 원소의 대소를 비교하고 조건에 맞지 않으면 자리를 교환하면서 정렬을 진행하는 알고리즘

### 시간 복잡도
(n-1) + (n-2) + (n-3) + ... + 1 => n(n-1)/2 이므로 O(n^2)

### 공간 복잡도
주어진 배열 안에서 교환을 통해 정렬을 수행하기 때문에 O(n)

### 장점 
- 구현이 간단하고 소스코드가 직관적이다.
- 정렬하고자 하는 배열 안에서 교환하는 방식이므로 다른 메모리 공간이 필요하지 않다.
- 안정 정렬이다.

### 단점
- 시간복잡도가 최악, 최선, 평균 모두 O(n^2)으로 비효율적이다.
- 정령 되어있지 않은 원소가 정렬되었을 때 자리로 가기 위해서 교환이 많이 일어난다.

[c++ 소스코드](https://github.com/chojaehyo/algorithm/blob/master/C%2B%2B/Bubble%20Sort)<br>
[python 소스코드](https://github.com/chojaehyo/algorithm/blob/master/Python/Bubble%20sort.ipynb)
