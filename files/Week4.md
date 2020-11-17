# 4주차

<br>

## [4주차 개발 내용 영상]

<iframe width="1280" height="720" src="https://www.youtube.com/embed/yB6mnglivKc" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

<br>

#### 1. 좌클릭을 꾹 눌러서 물건을 고정시키고, 마우스로 화면을 돌리면 그에 따라 오브젝트가 움직이게 한다. 휠을 굴려서 오브젝트를 밀고 당긴다.(z축)
<iframe src='//gifs.com/embed/racipe-window-lxGwBj' frameborder='0' scrolling='no' width='1280px' height='720px' style='-webkit-backface-visibility: hidden;-webkit-transform: scale(1);' ></iframe>

<br>

- 90%
- 휠로 밀고 당기기 기능은 아직 안넣음.

<br>

#### 2. 재료를 든 상태에서 보울 속에 넣고 E키를 누르면 보울 속 해당 재료의 무게가 점점 올라간다. 전자 저울에 올려놓으면 무게가 뜨게 한다.
<iframe src='//gifs.com/embed/object-lifting-vlV0n5' frameborder='0' scrolling='no' width='1280px' height='720px' style='-webkit-backface-visibility: hidden;-webkit-transform: scale(1);' ></iframe>

<br>

- 90%
- 저울 부분 UI로 띄우는 부분을 아직 구현하지 않음(현재는 콘솔창에 Debug.Log로 띄움)
- 변경사항 : E키를 꾹 누르는 것이 아니라 누를 때마다 우유, 밀가루는 10g씩, 물을 제외한 나머지는 1g씩(계란은 개로 표기), 물은 보울과 닿고 있으면 점점 무게가 오르게했다.

<br>

#### 3. 반죽기를 작동시키면 보울 속에 반죽 오브젝트를 생성한다. 이때 들어간 재료에 따른 완성도 공식을 적용한다.
- 50%
- 반죽 오브젝트를 생성만 했고 완성도 공식은 아직 적용하지 못함.
- 변경사항 : 완성도 공식은 레시피 저장방식을 xml이 아니라 PlayerPrefs로 따로 저장하기로 계획을 수정함.

<br>

#### 4. 오븐에서 발효시키는 기능을 구현한다.
- 0%
- 예정대로 넘기게 됨.
