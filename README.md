# java-calculator-precourse

## 구현할 기능 목록

1. 숫자 덧셈 (기본 구분자)
   - 입력된 문자열에 쉼표(`,`)와 콜론(`:`)을 구분자로 하여, 숫자들을 분리하고 그 합을 계산한다.

2. 커스텀 구분자 처리
   - 문자열이 "//커스텀 구분자\n" 형식일 때, 커스텀 구분자를 사용하여 숫자를 분리하고 그 합을 계산한다.

3. 예외 처리
   - 입력된 문자열이 잘못된 형식일 경우 `IllegalArgumentException`을 발생시킨다.

4. Console API 사용
   - `camp.nextstep.edu.missionutils.Console`의 `readLine()`을 사용하여 사용자로부터 입력을 받아 계산하는 기능을 구현한다.
