카운팅 비트
음수가 아닌 정수 번호로 지정된다. 0 ≤ i num num 범위의 모든 숫자에 대해 이항 표현에서 1의 수를 계산하여 배열로 반환한다.

예 1: 입력: 2

출력: [0,1,1]

예 2: 입력: 5

출력: [0,1,1,2,1,2]

후속 조치:

런타임 O(n*sizeof(integer))안으로 솔루션을 고안하는 것은 매우 쉽다.
하지만 선형 시간 O(n) 또는 한번의 패스로 구현할 수 있을까? 공간 복잡성은 O(n)이어야 한다. c++ 또는 다른 언어로 _builtin_popcount와 같은 기본 제공 기능을 사용하지 않고 실행하십시오.

Source::LeetCode