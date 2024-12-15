# X보다 작은 수

날짜: 2024년 11월 27일

## 코드

```cpp
#include <iostream>
using namespace std;
 
int main()
{
    ios_base::sync_with_stdio(false);	
    cin.tie(NULL);	
 
    int n, x;
    cin >> n >> x;
    int a[n];
    
    for(int i=0; i<n; i++)
    {
        cin >> a[i];
        if(a[i] < x) cout << a[i] << ' ';
    }
 
    return 0;
}

```

## 설명

첫째 줄에 주어진 n과 x를 받아, 수열 a를 담을 1차원 정수배열 생성

For문으로 수열 돌려서 x보다 작으면 출력