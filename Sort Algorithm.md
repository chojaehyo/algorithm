## Insertion Sort

- 자료 배열의 모든 요소를 앞에서부터 차례대로 이미 정렬된 배열 부분과 비교하여, 자신의 위치를 찾아 삽입함으로써 정렬을 완성하는 알고리즘

### 시간 복잡도
최악일 땐 O(n^2), 최선일 땐 O(n)

### 공간 복잡도
O(n)

### 장점 
- 알고리즘이 단순하다.
- 대부분의 원소가 이미 정렬되어 있을 경우, 매우 효율적이다.
- 정렬하고자 하는 배열 안에서 교환하는 방식이므로 다른 메모리 공간이 필요하지 않다.
- 안정 정렬이다.

### 단점
- 시간복잡도가 최악, 평균의 O(n^2)으로 비효율적이다.
- 배열의 길이가 길어질수록 비효율적이다.

[c++ 소스코드](https://github.com/chojaehyo/algorithm/blob/master/C%2B%2B/Insertion%20Sort)<br>
[python 소스코드](https://github.com/chojaehyo/algorithm/blob/master/Python/Insertion%20sort.ipynb)

<br>


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

## Selection Sort

- 해당 순서에 원소를 넣을 위치는 이미 정해져 있고, 어떤 원소를 넣을지 선택하는 알고리즘
