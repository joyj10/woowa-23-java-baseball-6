# 야구 게임 구현 기능
1. 게임 시작 안내 출력
   1. 숫자 야구 게임을 시작합니다.

2. 게임 숫자 3자리 수 랜덤 추출
   1. camp.nextstep.edu.missionutils.Randoms의 pickNumberInRange()로 숫자 추출

3. 사용자에게 숫자 입력 받는 기능 구현
   1. camp.nextstep.edu.missionutils.Console의 readLine() 사용하여 사용자 입력 받음
   2. 예시) 출력안
      1. 숫자를 입력해주세요 : 123

4. 사용자 입력 받은 수와 기존 지정된 숫자 비교 및 결과 출력
   1. 규칙
      1. 스트라이트 : 같은 수가 같은 자리에 있는 경우
      2. 볼 : 같은 수가 다른 자리에 있는 경우
      3. 같은 수가 전혀 없으면 낫싱
   2. 예시) 출력안
      1. 1볼 1스트라이크<br>낫싱

5. 3개 숫자가 모두 동일한 경우 안내 멘트 출력 후 게임 종료 처리
   1. 예시) 출력안
      1. 3스트라이크<br>
         3개의 숫자를 모두 맞히셨습니다! 게임 종료

6. 게임 새로 시작 및 종료 문구 출력
   1. 예시) 출력안
      1. 게임을 새로 시작하려면 1, 종료하려면 2를 입력하세요.

7. 게임 새로 시작 또는 종료 기능 구현
   1. 사용자 1 입력 시 : 게임 재 시작
   2. 사용자 2 입력 시 : 게임 종료 처리
