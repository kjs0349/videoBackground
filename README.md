# videoBackground
 
![VideoBackground](https://user-images.githubusercontent.com/61913417/103990978-676cce80-51d5-11eb-967d-097fecc0e3b8.gif)
우선 완성 화면입니다.
보시다시피 배경을 video로 놓고 그 위에 contents들을 넣어봤습니다!

html/css로 배경이 움직이는 역동적인 화면을 만들고 싶어서 만들어 봤습니다.

# 공부
## video 태그 속성들
- autoplay : 자동재생 ( <-> autoplay="false" : 자동재생 비활성화)
- muted : 오디오 재생, 기본값으로 false를 가지고 있으며 명시하지 않으면 false 명시하면 자동으로 true 값을 가지게 된다.
- loop : 무한재생 (배경이므로 계속 움직이기 위해 사용)
## CSS 속성
- object-fit
	- fill : 요소를 가득 채울수 있는 크기로 변화 되면서 종횡비는 유지되지 않는다.
	- contain : 내용이 종횡비를 유지하면서 요소에 정의된 너비와 높이안에서 가능한한 많이 확대 시킨다.
	- cover : 내용이 종횡비를 유지하면서 정의된 너비와 높이를 가득 채울때까지 확대된다.
	- none : 교체된 컨텐츠는 크기가 조정되지 않는다.
	- scale-down : 내용은 none또는 contain지정된 것처럼 크기가 조정되며 , 어느 쪽이든 구체적인 객체 크기가 더 작아진다.
- z-index
	쌓이는 순서를 임의로 적용할 수 있는 속성(마이너스 값도 가능)
