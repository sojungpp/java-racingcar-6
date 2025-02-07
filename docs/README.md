# 📌 우테코 2차 미션 - 자동차 경주

## 📍구현할 기능 목록


1. 경주할 자동차 이름을 입력 받는다.
    - `IllegalArgumentException`
        - 이름이 5자 이하가 아닌 경우
      

2. 시도할 횟수를 입력 받는다.
    - `IllegalArgumentException`
        - 숫자 외의 문자를 입력한 경우
      

3. 횟수 1번마다 각 자동차마다 경주를 진행하고(0~9 사이 무작위 값을 구한다.) 실행 결과를 보여준다.
    - 전진: 무작위 값이 4 이상인 경우
    - 멈춤: 무작위 값이 4 미만인 경우


4. 입력 받은 횟수 만큼 경주를 진행한다.


5. 가장 많이 전진한 우승자를 출력한다.
   - 우승자가 한 명 이상일 경우 `이름, 이름` (쉼표로 구분)


## 🚩추가 요구사항

- indent(인덴트, 들여쓰기) depth 3이 넘지 않도록 구현
- 3항 연산자 쓰지 않기
- 함수를 최대한 작게 만들기 (한 가지 일만 하도록)


## 💬 코드 컨벤션

```
feat: 새로운 기능 추가
fix: 버그, 오류 등으로 인한 수정
chore: src 또는 test 파일 외 파일 수정
refactor: 기능에 대한 수정 없는 코드 변경 (구조 변경 등)
docs: 문서 수정
comment: 주석 추가 및 수정
```