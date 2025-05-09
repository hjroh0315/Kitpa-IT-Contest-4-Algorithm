# 문제

중국에서는 $8$을 행운의 숫자로 여깁니다.

십진법으로 표현했을 때 모든 자릿수가 $8$인 수를 **$8$-넘버**라고 합시다. 예를 들어, $8$, $88$, $88\ 888\ 888$ 등이 $8$-넘버라고 할 수 있습니다.

어떤 양의 정수를 $8$개 이하의 $8$-넘버의 합으로 표현할 수 있다면, 이 정수를 **행운의 수**라고 합시다.

예를 들어, 정수 $64$는 $8+8+8+8+8+8+8+8$이므로 $8$개 이하의 $8$-넘버의 합으로 표현할 수 있습니다. 따라서 $64$는 행운의 수입니다.

하지만, 정수 $72$는 어떻게 해도 $8$개 이하의 $8$-넘버로 표현할 수 없습니다. 따라서 $72$는 행운의 수가 아닙니다.

양의 정수 $N$이 주어질 때, $N$이 행운의 수인지 판단하는 프로그램을 작성해 주세요.

## 입력

첫 번째 줄에 테스트 케이스의 개수 $T$가 주어집니다.

그다음 줄부터 $T$개의 테스트 케이스가 주어집니다. 각 테스트 케이스는 한 줄로 구성되며, 각각 양의 정수 $N$이 한 줄에 주어집니다.

## 출력

주어진 정수 $N$이 행운의 수라면 `Yes`를, 아니라면 `No`를 출력합니다. `Yes`, `No`는 대소문자를 구분하지 않습니다. 예를 들어 `Yes`가 답일 경우, `YES`나 `yES`도 정답으로 인정됩니다.

## 제한


*  $T \le 100\ 000$
*  $1 \le N \le 1\ 000\ 000\ 000\ 000\ 000\ 000$

## 서브태스크

  **번호**  |**배점**  |**제한**
  ----------|----------|----------------------------
  1         |19        |$N < 88$
  2         |33        |정답이 `Yes`인 경우, $N$은 $2$개 이하의 $8$-넘버로 표현할 수 있습니다.
  3         |48        |추가 제약 조건이 없습니다.
