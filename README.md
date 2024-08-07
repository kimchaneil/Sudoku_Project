### 스도쿠 게임
---
스도쿠는 가로,세로,그리고 3x3의 작은 정사각형 안에서 1~9까지의 숫자를 중복되지 않게 채원 넣는 논리 퍼즐 입니다. 채워 넣을 숫자는 주어진 힌트와 숫자의 법칙을 따라 채워져야 합니다.

**규칙**

- 각 행에는 1~9까지의 숫자가 중복되지 않게 채워져야 합니다.
- 각 열에는 1~9까지의 숫자가 중복되지 않게 채워져야 합니다.
- 3x3의 작은 정사각형 안에는 1~9까지의 숫자가 중복되지 않게 채워져야 합니다

  **함수들 설명**

 - initialize_board : 빈 스도쿠 보드를 생성합니다.
 - print_board : 현재 스도쿠 보드를 출력합니다.
 - solve_sudoku : 주어진 스도쿠 퍼즐을 해결합니다.
 - generate_sudoku : 빈 칸이 채워지지 않은 완성된 스도쿠 퍼즐을 생성합니다.
 - play_sudoku : 사용자에게 스도쿠 게임을 플레이할 기회를 제공합니다. 게임은 사용자가 잘못된 이동을 하거나 스도쿠를 완성할 때 까지 진행됩니다.
 -  
