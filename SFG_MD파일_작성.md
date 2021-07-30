
# 1. SFP 라이브러리
SFP 는 현재 java 11 버전을 사용하고 있으며, SFP의 라이브러리 구성은 다음과 같다.

<img src="image/sfp-diagram.png">
<center><그림> SFP 라이브러리 구성도<br></center>
<br>

## 1.1	sfp-starter-parent
SFP에서 사용하는 각 lib 버전을 관리하며, spring-boot-starter-parent 와 연결되어 있다. (java version 도 관리한다)
<br>




## 1.2	sfp-core
SFP의 서비스 개발의 위한 기본 구조 및 기능 제공한다.<br>
화면(view)이 없는 단독 rest-api 개발인 경우에 직접 연계하여 사용할 수도 있다.<br>
화면(view) 필요한 경우 sfp-web-core 또는 sfp-web-core-apps 를 사용하며, 해당 라이브러리는 sfp-core 를 기반으로 한다.

<br>

---

<br>

# 2. JSP 구조

### script closer 디자인 패턴을 사용하여 보다 간편하게 화면(View) 작성한다.

---

## 2.1 Title 네이밍 룰



## 2.2  script 구조

## 2.3 HTML 구조
- 화면(VIEW)를 구성하는 요소
    1) header: h2태그를 사용하여 페이지의 제목 설정.
    2) .align-*: 해당 태그 안에 데이터를 정렬.(align-left : 좌측, center, right)
    3) .function-area: 검색조건이 위치함.(예시 : 그림 3.1.2-1 : input태그(상품ID, 수량))
    4) .*-grid: grid 사용시 해당 div 태그안에 데이터를 그림.
    5) .footer-wrap: 해당 위치에 페이징을 설정.
    6) footer: .footer-wrap 태그로 페이징을 그림. /dialog의 경우는 닫기 등의 버튼이 위치함.

<br>

---

<br>

# 2. TILE

### SFP의 Front는 웹페이지 메뉴 및 상/하단 등과 같은 반복적으로 사용되는 부분들에 대해서 정보를 모아서 관리한다.

<br>

---

<br>

# 3. SFP 라이브러리 사용법


<br>


## 3.1 SFP UI 구조
VIEW와 스크립트 파일의 구조
### - SFP와 파일의 구조
1. sfp-라는 이름으로 모듈화 되어있다.
2. 스크립트라는 위젯, 위임방식을 사용한다.


## 3.2 Template + grid
## 3.2.1 Template, grid

### - option
1. onAfterDraw
2. templateModel

### - function

### - attribute


# 1. 제목
## 1.1 소제목
## 1.1.1 소제목
## 1.1.1.1 소제목
*,- => -로 통일 (하위는 *, -)


⑪ 이미지에 있는 애들은 어쩔 수 없다
아니면 1), 2) 사용

<img src = './image/test.png'>