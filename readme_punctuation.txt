- index.html 
    자바스크립트의 setTimeout 함수를 활용하여 0.5초 간격으로 
    문자의 색상을 변경하게 만들었습니다.

- page1_punctuation.html
    가운데 돌아가는 도형은 css에서 animation rotate 효과를 사용하여 계속 회전이 가능하게 만들었습니다.
    펼쳐지는 punctation 이미지는 정해진 위치에서 시작하여 크기가 점점 커지면서 브라우저 밖으로 나가게 만들었습니다.

    css에서 animation scale 을 사용하여 크기를 크게 만들었습니다.
    css에서 animation translateX, translateY 를 통해 각 이미지의 방향을 정했습니다.

- page2_question.html
    물음표 이미지가 위에서 아래로 내려가는 효과는 css에서 animation translateY를 사용했습니다.
    물음표 이미지를 원하는 개수만큼 생성과 위에서 아래로 내려가는 속도는 자바스크립트를 통해 구현했습니다.

- page3_exclamationMark.html
    느낌표 이미지 크기가 커졌다 작아졌다 하는 효과는 css에서 animation scaleX, scaleY를 사용했습니다.
    느낌표 이미지를 원하는 위치에 생성하는 내용은 자바스크립트를 통해 구현했습니다.

- page4_circleComma.html
    동그라미가 굴러가는 효과는 css에서 animatioin 효과를 사용했습니다.
    회전효과는 rotate 효과를 사용했습니다.
    왼쪽에서 오른쪽으로 이동하는 효과는 translate를 사용했습니다.

- page4_circleComma.html
    공을 튀기기, 공이 튀기면서 발생하는 그림자 효과는 css에서 animatioin 효과를 사용했습니다.
    
    공 튀기기는 공의 위치를 바꿔가며 튀기는 효과를 주기 위해 translateY로 위치를 변경했고 
    바닥에 가까울때 튕김 효과를 위해 공 이미지의 height, width를 조절하여 크기를 변형했습니다.

    그림자 효과는 공 튀기기 animatioin과 동일한 효과에 맞춰 바닥에 가까울때 그림자 div의 크기와 투명도를 조절했습니다.
    scale을 통해 크기를 조절했고
    background-color를 통해 투명도를 조절하여 그림자 효과를 적용했습니다.

- page6_colonSemicolon.html
    콜론, 세미콜론 이미지를 각각 분리된 이미지를 가지고 :hover(호버) 효과를 사용하여
    마우스가 올라가면 콜론, 세미콜론의 아래 이미지가 내려가게끔 만들었습니다.


- page7_bigComma.html
    콤마 이미지를 cursor 클래스가 포함된 div 태그에 적용했습니다.
    글이 포함된 영역에 마우스가 올라가면 콤마 이미지가 커지도록 :hover(호버) 효과를 사용했습니다.

    콤마 이미지는 실제 커서가 아닌 div 태그안의 내용이라 자바스크립트를 통해
    mousemove 이벤트를 활용하여 실제 커서가 움직임에 따라서 cursor 클래서 div가 
    실제 커서 위치로 따라가게끔 구현했습니다.

    그리고 cursor 클래스가 포함된 div 영역이 블러 처리된 red-word-blur 클래스 영역에 올라가면
    블러 처리가 해제되어 글이 보이게끔 처리했습니다.


    