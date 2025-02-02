## 전체 흐름
1. 사용자가 경주 할 자동차들의 이름을 입력
2. 사용자가 몇 번의 이동을 할 것인지 입력
3. 지정된 횟수만큼 각 자동차들을 이동
   - 자동차 별로 0이상 9이하 난수를 생성 후, 4 이상일 때만 이동
   - 한 턴 이동 후에는 실행 결과를 가로 막대그래프 형태로 출력
4. 이동 종료 후 최종 우승자를 출력
   - 최종 우승자가 다수일 경우 `,` 로 구분

## 구현 기능 목록
### 자동차 이름 입력
- [x] 자동차 이름 입력 안내 문구를 출력하는 기능
- [x] 사용자로부터 자동차들의 이름을 입력받는 기능
- [x] 입력된 이름들을 `,`로 구분하여 저장하는 기능
- [x] 각 자동차들의 이름이 유효한지 확인하는 기능
  - [x] 이름이 5자 초과라면 예외처리
  - [x] 이름이 알파벳과 숫자(`[a-zA-Z0-9]`)로만 이루어져 있지 않다면 예외처리

### 이동할 횟수 입력
- [x] 이동할 횟수 입력 안내 문구를 출력하는 기능
- [x] 이동할 횟수를 입력받는 기능
- [x] 이동할 횟수가 유효한 숫자인지 확인하는 기능
  - [x] 자연수가 아닌 입력이 전달되는 경우 예외 처리

### 게임 진행
- [x] 실행 결과 안내 문구를 출력하는 기능
- [x] 각 자동차별로 `0` 이상 `9` 이하의 난수를 생성하는 기능
- [x] 난수값이 `4` 이상인지 확인하는 기능
- [x] 난수값이 `4` 이상인 자동차의 위치를 `1` 증가시키는 기능
- [x] 각 라운드의 실행 결과를 출력하는 기능
- [x] 입력된 횟수 만큼 라운드를 반복하는 기능

### 진행 결과
- [x] 우승자(가장 이동 거리가 큰 자동차)를 정하는 기능
- [x] 우승자를 출력하는 기능
  - [x] 우승자가 여러 명이면 `,`로 구분하여 출력
