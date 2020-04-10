# layout-practice

practice for web publishing, layout configuration

## Layout

`layout01`

- 🏷 margin: 0 auto - (블록요소 가운데 정렬)
- 🏷 float: left - (블록요소 가로정렬)
- 🏷 line-height - (텍스트 1줄 일 때 세로정렬)
- 🏷 text-transform: uppercase - (텍스트 대문자 변경)

`layout02`

- 🏷 clear: both - (기존에 적용되었던 float의 속성을 지우기 위해 사용)

`layout03`

- 🏷 블로그에서 자주 보이는 레이아웃

`layout04`

- 🏷 전체 콘텐츠를 감싸는 컨테이너의 크기 지정해주기

`layout05`

- ✉️ `참고사이트` : 디비컷
- 🏷 전체 영역과 중간 컨테이너의 구분 (화면이 커져도 전체영역은 유지)
- 🏷 전체 영역 작업 > 컨테이너(::가운데) 영역
- 🏷 width: 100%; - (기본값)
- 🏷 자식 요소의 height값이 있으면 부모 요소의 height값은 없어도 됨

`layout06`

- 🏷 layout05 에서 코드 간결화
- 🏷 height: inherit; - (높이 상속)
- 🏷 rgba(0,0,0,0.3)

`layout07`

- 🏷 전체적인 틀 잡을 때는 id(#)를 많이 사용, 반복되는 부분에는 class(.)을 사용
- 🏷 명명이랑 주석처리는 항상 깔끔하게 하기
- 🏷 큰틀부터 컨테이너까지 하나씩 접근
- 🏷 `DOTHOME` : 무료호스팅 (3개까지가능)

`layout08`

- 🏷 전체 사이트 만들기 시작
- 🏷 html, css 파일 분리
- 🏷 `@charset "utf-8"` : css 한글 깨지지 않기 위해 추가
- 🏷 reset.css 생성 : 사용할 태그에 대해서 css 여백 초기화

## Menu and Function

`스킵 메뉴(SKIP MENU)`

- 🏷 스킵 내비게이션 만들기 : (웹 접근성으로 인한 반드시 필요한 메뉴)
- 🏷 a 태그 id명으로는 바로 접근 가능
- 🏷 position: absolute; - (절대적인 위치, 영역을 내 마음대로 움직임 가능, 영역이 붕 뜰 수 있음)
- 🏷 웹 표준 참고 `네이버 웹표준 널리` `다음 웹표준 다음` `웹접근성 연구소`

`헤더 배경 및 메뉴`

- 🏷 인라인 요소는 전체 영역이 없다. 부모 요소의 영향을 받음.
- 🏷 display: inline-block (인라인 요소와 블록 요소의 성질을 모두 가짐.)
- 🏷 css에서도 부모와 자식과의 관계를 알기 쉽게 써놓는 것이 중요.

`헤더 타이틀 및 웹 폰트`

- 🏷 OS에 따른 여백이나 폰트 차이를 최소화 하기 위해 웹 폰트 사용 (:구글폰트)

`헤더 아이콘 수정`

- 🏷 사이트에서 이미지를 표현하는 방법이 중요 (HTML OR CSS)
- 🏷 1. img 태그로 표현 (의미가 있을 때) / alt 태그 - 대체 문자 표현
- 🏷 2. background 속성으로 표현 (의미가 없을 때) - 대체 문자 X
- 🏷 3. 요즘에는 이미지를 background 속성으로 많이 표현 / 가상으로 대체 문자를 만들어 준다(IR 효과) (이미지 스프라이트 기법 이용)
- 🏷 의미가 있을 때와 없을 때를 구분해서 작업
- 🏷 IR 기법 : CSS 기법을 사용하여 이미지 대체텍스트를 제공할 수가 있다.

`전체 메뉴`

- 🏷 overflow: hidden; - (float:left;를 사용한 요소 상위 요소에 사용::깨짐방지)

`전체 타이틀`

- 🏷 position: absolute; - (영역을 없앰 / 절대적 위치 / 반응형에서는 잘 사용하지 않음)
- 🏷 position: relative; - (absolute의 기준점을 잡아줌)
