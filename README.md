# 🧮 문자열 덧셈 계산기

## 📋 기능 목록

1. **빈 문자열을 입력했을 때 0을 반환한다.**

   - 입력: `""`
   - 출력: `0`

2. **쉼표(,) 또는 콜론(:)을 구분자로 가지는 문자열을 입력하면 구분자를 기준으로 분리한 숫자의 합을 반환한다.**

   - 입력: `"1,2"`
   - 출력: `3`
   - 입력: `"1,2:3"`
   - 출력: `6`

3. **커스텀 구분자가 지정된 경우 해당 구분자를 사용하여 숫자의 합을 계산한다.**

   - 입력: `"//;\n1;2;3"`
   - 출력: `6`

4. **⚠️ 음수가 포함된 경우 `[ERROR]`로 시작하는 메시지를 출력하고 예외를 발생시킨다.**

   - 입력: `"-1,2,3"`
   - 출력: `[ERROR] 음수는 입력할 수 없습니다.`

5. **⚠️ 구분자를 기준으로 분리한 값이 숫자가 아니면 `[ERROR]` 메시지를 출력한다.**

   - 입력: `"1,A,3"`
   - 출력: `[ERROR] 숫자 형식이 잘못되었습니다.`

6. **하나의 숫자만 입력했을 경우 그 숫자를 반환한다.**

   - 입력: `"1"`
   - 출력: `1`

7. **구분자를 여러 번 사용한 경우도 올바르게 처리한다.**
   - 입력: `"1,,2"`
   - 출력: `3`
   - 입력: `"1::2"`
   - 출력: `3`

## 🚀 사용 방법

1. `npm install`을 통해 필요한 패키지를 설치한다.
2. `npm run start`를 통해 프로그램을 실행한다.
3. 콘솔에 덧셈할 문자열을 입력하고 결과를 확인한다.

## 🛠️ 테스트 방법

1. `npm run test`를 통해 테스트를 실행한다.
2. 모든 테스트 케이스가 통과하는지 확인한다.