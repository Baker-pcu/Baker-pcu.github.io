## 1. 2주차 개발 내용 영상

<br>

<iframe width="1253" height="705" src="https://www.youtube.com/embed/_VmQ3L9GYZc" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

<br>

- 시작화면 제작 100%
- 새 게임 기능 구현 100%
- 저장 기능 테스트 100%
- 맵 제작 90% (반죽, 빵, 밀가루, 이스트, 식빵팬 3D모델 제작 x)

## 2. 키보드 마우스 조작으로 변경

- 화면 중간의 크로스헤어(점)으로 사물에 ray를 쏴서 일정 거리내이면 상호작용 가능
- 좌클릭 : 들기
- 휠 : 들고 있는 사물 밀기(위로 굴림), 당기기(아래로 굴림)
- E : 상호작용(재료 넣기, 반죽기 돌리기, 오븐조작)
- 오븐 조작은 E키 입력 시 UI를 띄우고 프로그래스바?같은 걸로 온도, 시간을 조절하거나 바로 옆의 InputField를 이용해서 정확한 값 입력
- TAB : 레시피 UI 띄우기
- Q : 레시피UI를 띄운 상태에서 누르면 마우스가 나타나고 레시피 창 조작 가능(이때 플레이어는 움직일 수 없다.)
- WASD : 이동
- ESC : 일시정지
