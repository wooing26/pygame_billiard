# pygame_billiards
 
## 개요
    - 학교 수업에서 진행한 프로젝트입니다.
    - 물리와 프로그래밍을 합친 부분을 고려하다 pygame으로 당구 게임을 제작하는 것이 좋다고 생각하여 제작하게 되었습니다.

## 제작
    - 각종 물리 법칙을 사용하여 공의 부딪침과 움직임을 작성해 주었습니다. 
    - 다른 파이썬 프로젝트와는 다르게 당구공의 스핀 값을 추가하여 실제 당구를 치는 것과 같게 제작하였습니다.
    - 각종 마찰과 반발 상수들은 직접 게임을 시도하며 적절한 값으로 설정해 주었습니다.
    - 공의 초기 속력은 제한을 두어 특정 값보다 크게 입력되면 최대값을 입력받게 하였습니다.

## 시작
    - 전체 파일을 .zip 파일로 다운로드 받아 main.py 파일을 실행시키세요.
    - main menu 창이 열리면 settig을 클릭하여 스크린 사이즈를 조절하세요. (초록색 사각형이 스크린 사이즈입니다.)
    - back을 눌러 main menu 창으로 돌아가고, play 버튼을 눌러 게임을 실행시키세요.
    - 게임 진행 방법
        1) 해당 공을 클릭하여 드래그해서 초기 속도 값을 설정하세요.
        2) 그다음 좌측 위쪽에 흰색 공에 큐대로 어디를 칠 것인지 선택하세요. (직접 칠 때 위치로 생각하세요.)
        3) 점수가 오르면 한 번 더 치고, 아니라면 다음 사람이 치게 됩니다.
        4) 다시 play 하고 싶으면, x 버튼을 누른 후 다시 play 하세요.

## 규칙
    - 실제 당구 규칙을 적용하였습니다.
    - 자신의 공으로 다른 두 공을 모두 맞혀야 합니다.
    - 두 공을 모두 부딪치기 전에 당구대 벽에 최소 3번 부딪쳐야 합니다.

## 협업 (물리학과)
    - 안창민 [chanamon2]https://github.com/chanamon2
