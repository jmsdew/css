# css

* cascading style sheets의 약자
* html로 만들어진 웹 문서에 색, 크기, 글꼴 등 스탕리을 설정해 주는 언어

* css로 기대되는 효과
1. 정보와 디자인을 분리하여 관리할 수 있음.
2. 정보를 수정하지 않고 디자인만 변경할 수 있음.
(html 태그마다 style속성을 주게 되면 소스코드가 지저분해 지는데, 분리하여 관리하게 되면 유지보수 및 가독성이 좋아짐.)

### css의 기본 구조
<img src=./css.png>

- 전체 구조를 rule set라 부름
- selector(선택자) = 맨 앞에 있는 html 요소 이름. 꾸밀 요소를 선택
- declaration(선언)= color : red 같은 규칙 등 원하는 요소의 속성을 명시
- property(속성) = 주어진 html 요소를 꾸밀 수 있는 방법.
- property value(속성 값) 

*각각의 rule set은 반드시 {}로 감싸져야 한다. <br>
*각각의 선언을 구분하기 위해 세미콜론( ; )을 사용해야한다.

### 박스모델
<img src=./box-model.png>

 - css 레이아웃은 박스모델을 주 기반으로 하고있음.
 - padding = 컨텐츠 주위의 공간
 - border = padding을 둘러싼 실선
 - margin = 요소의 바깥을 둘러싼 공간


 ---
 ### 사용하는 속성

 - width = 한 요소의 너비
 - height = 한 요소의 길이
 - color = 한 요소의 색
 - display = 요소의 표시 형식 설정
 - background-color = 요소의 컨텐츠와 padding의 배경 색

 등등