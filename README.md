# Programmers
문제 풀면서 얻은 풀이법
=======================
1.순서대로 더하기. O(n) -> O(1)로
--------------------------------
### 1.1. 1부터 n까지 더하기.
    #### 1 부터 n까지 순서대로 더한 것은 n(n+1)/2 이다. Ex) 1~10 더한 것 -> (10+11)/2 = 55
### 1.2. n부터 m까지 더하기. (단, n<m , n>1 인 정수)
    #### 1.1번을 활용하여 서로 빼 주면 된다. m(m+1)/2 - n(n+1)/2 
