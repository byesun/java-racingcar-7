# 구현 기능 목록 🔥

---

저번 1 주차 기능 구현 목록을 확인 했을 때, 제 자신이 보기에 난해한 부분이 많다고 느껴지게 되어 이번에는 입력, 기능, 출력으로 3가지로 나누어 구현 기능을 정리 했으며, 구현 이후 아래에는 1주차에 했던 코드를 설명하는 글을 작성하겠습니다.

---

## **1️⃣ 입력**

- 자동차 이름을 쉼표(,)로 구분하여 이름을 분리한다.
- 시뮬레이션 횟수를 입력 받는다.
- 예외 처리 :
    - 자동차의 이름이 분리 된 경우 자동차의 이름이 5자를 넘어가는 경우
    - 입력 값이 null 또는 “” 일 경우
    - 자동차의 이름이 중복이 있을 경우
    - 횟수가 음수 일 경우

## **2️⃣ 자동차 게임 기능**

- 각 자동차에 무작위 값을 준다.
    - 해당 무작위 값이 4 이상일 경우 이동 거리를 1 증가 시키며, 전진한다.
- 시뮬레이션 횟수가 종료 이후에 이동 거리가 가장 큰 자동차 이름을 반환한다.

## **3️⃣ 출력**

- 시뮬레이션 횟수 만큼 반복을 하여, 각 회 당 실행 결과를 출력한다.
    - 이동 거리는 ‘-’로 표현하여 1이 증가되면 ‘-’를 붙여서 출력한다.
- 이동 거리가 가장 큰 자동차의 이름을 출력한다.
    - 공동 우승일 경우 쉼표(,)를 기준으로 구분하여 출력한다.


---
---

## Message explanation
🤓 1주차에 적용을 하지 않았던 MVC패턴을 적용하여 2주차를 진행하겠습니다.

### 📜 feat: 입력 및 예외 처리 (+테스팅 완료)
구현 기능 목록 중 `1️⃣입력`에 대한 처리에 입력에 대한 `글자 수`, `빈 값`, `중복`, `횟수 음수` 예외에 대한 처리
를 구현하여 분류 하였습니다.

### 📜 feat: 인게임 자동차 객체 고유 무작위 번호 할당
구현 기능 목록 중  `2️⃣자동차 게임 기능`에 기능인 무작위 값 매칭을 구현하여 
분류하였습니다.

### 📜 feat: 고유 무작위 번호를 통해 자동차 전진 상황 구현
중첩된 점수를 통해서 전진 상황을 '-'로 표현하였습니다.

