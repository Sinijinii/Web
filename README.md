# Web
- World Wide Web : 인터넷으로 연결된 컴퓨터들이 정보를 공유하는 거대한 정보 공간
- Web: Web site, Web application등을 통해 사용자들이 정보를 검색하고 상호작용하는 기술
- Web site: 인터넷에서 여러개의 Web page가 모인 공간
- Web page: HTML, CSS등의 웹 기술을 이용해 만들어진, Web site를 구성하는 하나의 요소

---

# HTML

- HyperText Markup Language
- 웹 페이지의 의미와 구조를 정의하는 언어
- 요소의 이름은 소문자 사용을 권장
- 속성의 따옴표는 큰 따옴표 권장
- 에러를 반환하지 않기에 작성 시 주의해야함

## Hypertext

- 웹 페이지를 다른 페이지로 연결하는 링크
- 참조를 통해 사용자가 한 문서에서 다른 문서로 즉시 접근할 수 있는 텍스트

## Markup Language

- 태그 등을 이용하여 문서나 데이터의 구조를 명시하는 언어
- HTML, Markdown
    
    ![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/1848a85f-9836-46e1-8795-3eff9f43f933/b3edb6dd-c006-4ff8-be61-f5aee0bce1c1/Untitled.png)
    

## HTML 구조

```html
<!DOCTYPE html>
- 해당 문서가 html문서라는것을 나타냄

<html></html>
- 전체 페이지의 콘텐츠를 포함

<title></title>
- 브라우저 탭 및 즐겨찾기 시 표시되는 제목으로 사용

<head></head>
- HTML문서에 관련된 설명, 설정 등
- 사용자에게 보이지 않음

<body></body>
- 페이지에 표시되는 모든 콘텐츠
```

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/1848a85f-9836-46e1-8795-3eff9f43f933/caa25ac0-2d3d-4167-b7d9-d0146b0c0d52/Untitled.png)

### HTML Element(요소)

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/1848a85f-9836-46e1-8795-3eff9f43f933/dd9cddb4-1466-48d4-866e-4ba2aa96cbde/Untitled.png)

- 하나의 요소는 여는 태그와 닫는 태그 그리고 그 안의 내용으로 구성
- 닫는 태그는 태그 이름앞에 슬래시가 포함
- 닫는 태그가 없는 태그도 존재 - 컨텐츠가 없다는 뜻 ex) img태그

### HTML Attributes(속성)

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/1848a85f-9836-46e1-8795-3eff9f43f933/e15fc2ad-2a10-4647-9b51-bab22bc581e5/Untitled.png)

- 규칙
    - 속성은 요소 이름과 속성 사이에 공백이 필요
    - 하나 이상의 속성들이 있는 경우엔 속성 사이에 공백으로 구분
    - 속성의 값은 열고 닫는 따온표로 감싸야 함 - 주로 `" "`
- 목적
    - 나타내고 싶지 않지만 추가적인 기능, 내용을 담고 싶을때
    - CSS에서 해당 요소를 선택하기 위한 값으로도 활용

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/1848a85f-9836-46e1-8795-3eff9f43f933/f5a471a7-8043-41f1-a5fd-95d09a534ceb/Untitled.png)

## HTML Text structure- 주요 목적 중 하나는 텍스트 구조와 의미를 제공

## HTML - 웹페이지의 의미와 구조를 정의하는 언어

### img

```html
<img src="images/sample.png" alt="">
```

- alt부분은 이미지가 없을때 혹은 불러와지지 않을때 대체할 텍스트
- 시각 장애인용 리더기에서는 이미지를 alt값으로 읽어오기에 필수적으로 필요

### h1~6

```html
<h1>Heading</h1>
```

- h1: 현재 문서의 최상위 제목을 뜻함
- 텍스트를 크게만 만드는것이 아님
- 하나의 html문서에는 하나의 h1태그만을 두기를 권장

### p

`<p></p>` 태그는 paragraph, 즉 문단의 약자로, 하나의 문단을 만들 때 사용

```html
<p>문단</p>
```

### br

```html
<br>
```

- 줄바꿈 태그

## Lists

### ol

- ordered list - 숫자나 알파벳 등 순서가 있는 목록을 만드는데 사용

### ul

- unordered list - 순서가 필요 없는 목록을 만들때 사용

### dl

- definition list - 사전처럼 용어를 설명하는 목록을 만들때 사용

### li

- list item - <ol>, <ul>의 각 항목들을 나열할때 사용하는 태그

```html
    <ul>
        <li>파이썬</li>
        <li>웹</li>
    </ul>
```

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/1848a85f-9836-46e1-8795-3eff9f43f933/51c73b26-3736-4196-9f02-82585da251b9/Untitled.png)

---

# CSS

- Cascading Style Sheet
- 웹 페이지의 디자인과 레이아웃을 구성하는 언어

## 구문

- 선택자, 선언- (속성, 값)으로 나뉨

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/1848a85f-9836-46e1-8795-3eff9f43f933/26360fda-153f-4c4e-a776-3ff287f3fcaf/Untitled.png)

- 선언이 끝났다는 의미로 `;` 필요

## 적용방법

### 1. 인라인 스타일

- html요소 안에 style 속성 값으로 작성
    
    ![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/1848a85f-9836-46e1-8795-3eff9f43f933/3d6c3f98-6f27-4fa7-aa12-c406ae373325/Untitled.png)
    

### 2. 내부 스타일 시트

- head 태그 안에 style 태그에 작성
    
    ![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/1848a85f-9836-46e1-8795-3eff9f43f933/7f9194cf-6450-4a9d-8be6-fe8cf0daabf6/Untitled.png)
    

### 3. 외부 스타일 시트

- 별도의 CSS 파일 생성 후 HTML link 태그를 사용해 불러오기

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/1848a85f-9836-46e1-8795-3eff9f43f933/fd98d242-db81-418d-beb0-ea5d8cdf3341/Untitled.png)

## CSS Selectors

- HTML 요소를 선택하여 스타일을 적용할 수 있도록 하는 선택자

### 1. 기본 선택자

- 전체(*)선택자 - `*`
    - HTML 모든 요소를 선택
- 요소(Tag)선택자
    - 지정한 모든 태그를 선택
- 클래스(class)선택자 - `.`
    - 주어진 클래스 속성을 가진 모든 요소
- 아이디(id)선택자 - `#`
    - 주어진 아이디 속성을 가진 요소
    - 문서에는 주어진 아이디를 가진 요소가 하나만 있어야 함
- 속성(attr)선택자

```html
<head>
  <...
  <style>
    /* 전체 선택자 */
    * {
      color: green;
    }
    h2 {
      color: orange;
    }
    h3,h4 {
      color: pink;
    }
    /* 클래스 선택자 */
    .blue{
      color: blue;
    }
    /* 아이디 선택자 */
    #purple{
      color: purple;
    }
  </style>
</head>

<body>
  <h1 class="blue">Heading</h1>
  <h2>선택자</h2>
  <h3>연습</h3>
  <h4>반가워요</h4>
  <p id="purple">과목 목록</p>
  <ul>
    <li>파이썬</li>
    <li>알고리즘</li>
    <li>웹
      <ol>
        <li>HTML</li>
        <li>CSS</li>
        <li>PYTHON</li>
      </ol>
    </li>
  </ul>
  <p class="blue">Lorem, <span>ipsum</span> dolor.</p>
</body>
```

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/1848a85f-9836-46e1-8795-3eff9f43f933/146e3c3c-8f12-4453-a2d6-a70306457059/Untitled.png)

### 2. 결합자(Combinators)

- 자손 결합자(” “ (space))
    - 첫번째 요소의 자손 요소들을 선택
- 자식 결합자(”>”)
    - 첫번째 요소의 직계 자식만 선택

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/1848a85f-9836-46e1-8795-3eff9f43f933/2e0effad-65a2-4a6e-ab59-4875715cbda8/Untitled.png)

## 명시도(Specificity)

- 최종적으로 적용할 CSS선언을 결정하기 위한 알고리즘
- CSS Selector에 가중치를 계산하여 어떤 스타일을 적용할지 결정
- 동일한 요소를 가리키는 2개 이상의 CSS규칙이 있는 경우 가장 높은 명시도를 가진 스타일이 적용

### 명시도 순서

**Importance(!important) > Inline 스타일 > 선택자(id > class > 요소) > 소스코드 선언 순**

- 소스 코드 선언 순은 CSS 내부에 작성된 선언임
- 마지막에 선언된것이 결정
- **Importance 는 사용하지 않는 것을 권장**
- **속성은 되도록 “class”만 사용할 것을 권장**
    - 불필요한 가중치에 대해 고민하지 않도록 Class에 대해서만 만들어둠

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/1848a85f-9836-46e1-8795-3eff9f43f933/bf689db0-1a72-4e76-979d-931a6a017932/Untitled.png)

```html
<style>
    h2 {
      color: darkviolet !important;
    }

    p {
      color: blue;
    }

    .orange {
      color: orange;
    }

    .green {
      color: green;
    }

    #red {
      color: red;
    }
  </style>
</head>

<body>
  <p>1</p>
  <p class="orange">2</p>
  <p class="green orange">3</p>
  <p class="orange green">4</p>
  <p id="red" class="orange">5</p>
  <h2 id="red" class="orange">6</h2>
  <p id="red" class="orange" style="color: brown;">7</p>
  <h2 id="red" class="orange" style="color: brown;">8</h2>
</body>
```

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/1848a85f-9836-46e1-8795-3eff9f43f933/2a356203-0f6e-48a1-ae2a-f0e6ad7fbc40/Untitled.png)

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/1848a85f-9836-46e1-8795-3eff9f43f933/491053cb-01cb-4274-86d8-6fa2512ce5bf/Untitled.png)

- 개발자 도구를 통해 확인이 가능함

## Cascade

- 계단식
- 한 요소에 동일한 가중치를 가진 선택자가 적용된다면 마지막에 나오는 선언이 사용

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/1848a85f-9836-46e1-8795-3eff9f43f933/9debcfeb-f719-4d1b-8d33-1824720eb2a1/Untitled.png)

## CSS 상속

- 기본적으로 CSS는 상속을 통해 부모 요소릐 속성을 자식에게 상속해 재사용성을 높임

### 1. 상속 되는 속성

- Text 관련 요소(font, color, text-align), opacity, visivility등

### 2. 상속 되지 않는 속성

- Box model 관련 요소 (width, height, border, box-sizing…)
- position 관련 요소(position, top/right/bottom/left, x-index)등

**상속 여부는 MDN문서에서 확인 가능**

---
@240307
# CSS Latout

## CSS Box Model

- 모든 HTML요소를 사각형 박스로 표현하는 개념
- 내용(Content), 안쪽 여백(Padding), 테두리(border), 외부간격(margin)으로 구성되는 개념
    
    ![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/1848a85f-9836-46e1-8795-3eff9f43f933/b764d94f-e4a6-4f18-85bc-e92f516b920e/Untitled.png)
    

### Width & height 속성

- 요소의 너비와 높이를 지정
- 이때 지정되는 요소의 너비와 높이는 콘텐츠 영역을 대상으로 함

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/1848a85f-9836-46e1-8795-3eff9f43f933/e2fda458-57c9-47e8-8fac-4e2066b196cd/Untitled.png)

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/1848a85f-9836-46e1-8795-3eff9f43f933/4d72ec82-e24a-4189-9228-08a872147fb8/Untitled.png)

## 박스 타입

- 항상 새로운 행으로 나뉨
- Width 와 height 속성을 사용하여 너비와 높이를 지정할 수 있음
- 기본적으로  width속성을 지정하지 않으면 박스는 inline방향으로 사용 가능한 공간아ㅡㄹ 모두 차지함
- 대표적인 block 타입 태그
    - h1~h6, p, div

## inline 타입

- 새로운 행으로 나뉘지 않음
- width와 height속성을 사용할 수 없음
- 수직방향
    - padding, margins, borders가 적용되지만 다른 요소를 밀어낼 수는 없음
- 수평방향
    - padding, margins, borders가 적용되어 다른 요소를 밀어낼 수 있음
- 대표적인 inline타입 태그
    - a, img, span

### 속성에 따른 수평 정렬

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/1848a85f-9836-46e1-8795-3eff9f43f933/ef2f82dc-5efb-4540-b98c-dc6c456d6a65/Untitled.png)

## 기타 display 속성

### 1. inline - block

- inline과 block 요소 사이의 중간 지점을 제공하는 display값
- block 요소의 특징을 가짐
    - width 및 height 속성 사용 가능
    - padding, margin 및 border로 인해 다른요소가 밀려남
- 요소가 줄바꿈 되는것을 원하지 않으면서 높이와 너비를 적용하고 싶은 경우에 사용

### 2. none

- 요소를 화면에 표시하지 않고, 공간조차 부여되지 않음

## shorthand 속성 - border

- border-width, border-style, border-color를 한번에 설정하기 위한 속성

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/1848a85f-9836-46e1-8795-3eff9f43f933/8d8be9fb-177e-488e-a09b-1dc0ed418f63/Untitled.png)

## shorthand 속성 - margin and padding

- 4반향의 속성을 각각 지정하지 않고 한번에 지정할 수 있는 속성

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/1848a85f-9836-46e1-8795-3eff9f43f933/c38d9fb7-2884-4609-8d37-cdf029153a6c/Untitled.png)

## 마진 상쇄 - margin collapsing

- 두 block 타입 요소의 margin top과 bottom이 만나 더 큰 margin으로 결함되는 형상
- 웹 개발자가 레이아웃을 더욱 쉽게 관리할 수 있도록 함
- 각요소에 대한 상,하 margin을 각각 설정하지 않고 한 요소에 대해서만 설정하기 위함

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/1848a85f-9836-46e1-8795-3eff9f43f933/77e6e7ef-989f-468a-b569-91fbb8f5a540/Untitled.png)

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/1848a85f-9836-46e1-8795-3eff9f43f933/6ca6ffc8-850e-4112-8ec8-7663d4779816/Untitled.png)

---

---

# CSS Posotion

## CSS Layout

- 각 요소의 위치와 크기를 조정하여 웹 페이지의 디자인을 결정하는 것
- 요소를 Normal Flow에서 제거해 대른 위치로 배치하는 것
    - 다른 요소 위에 올리기, 화면의 특정 위치에 고정시키기 등
    
    ![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/1848a85f-9836-46e1-8795-3eff9f43f933/defa1cc8-a2f1-4e86-9eac-19c645e5b23f/Untitled.png)
    

## Position 유형

### 1. static

- 기본값으로 부여를 하지 않아도 됨
- Normal Flow에 따라 배치

### 2. relative

- 본인의 위치를 기준으로 이동
- 상대 위치
    - 본인의 static위치를 기반으로

### 3. absolute

- 요소를 Normal Flow에서 제거
- 가장 가까운 relative 부모 요소를 기준으로 이동
- 문서에서 요소가 차지하는 공간이 없어짐
- 아래에서 작성했던 레이아웃이 많았다면 깨질 위험이 있음
    - 본인이 차지했던 공간이 사라지기 때문
    - 본인의 static이 없음
- static이 아닌 부모요소를 찾아감
- absolute를 조정할 부모 요소가 중요함
- 부모에 position: relative;를 줘야함 static불가
    - 부모가 이동하면 absolute도 이동해야함

### 4. fixed

- 화면에 고정이 되어 있음
- 요소를 Normal Flow에서 제거
- 현재 화면 영역(viewport)을 기준으로 이동
- 문서에서 요소가 파지하는 공간이 없어짐

### 5. sticky

- 요소를 Normal Flow에 따라 배치
- 요소가 일반적인 문서 흐름에 따라 배치되다 스크롤이 특정 임계점에 도달하면 그 위치에 고정
- 만약 다음 sticky요소가 고정되어 있던 위치와 다음 sticky 요소의 자리를 대체
    - 이전 스티키 요소가 고정되어 있던 위치와 다음 요소가 고정되어야 할 위치가 겹치기 때문
- 임계점이 없다면 Normal Flow

## Z-index

- 요소가 겹쳤을 때 어떤 요소 순으로 위에 나타낼지 결정
- 정수 값을 사용해 Z축 선서를 지정
- 더 큰 값을 가진 요소가 작은 값의 요소를 덮음

## Position의 역할

- 전체 페이지에 대한 레이아웃을 구성하는 것이 아닌 **페이지 특정 항목의 위치를 조정**하는 것

## CSS Flexbox

- 요소를 행과 열 형태로 배치하는 1차원 레이아웃 방식
    - 공간배열 & 정렬
    
    ![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/1848a85f-9836-46e1-8795-3eff9f43f933/390c5160-b599-4a1d-a6d5-f34525996687/Untitled.png)
    

### main axis(주 축)

- flex item들이 배치되는 기본 축
- main start에서 시작하여 main end방향으로 배치(기본 값)

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/1848a85f-9836-46e1-8795-3eff9f43f933/fcad5b5a-fb84-4ae5-9dcb-54dbe8d54730/Untitled.png)

### cross axis(교차 축)

- main axis에 수직인 축
- cross start에서 시작하여 cross end방향으로 배치((기본 값)
    
    ![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/1848a85f-9836-46e1-8795-3eff9f43f933/b9e8faa1-caa9-4b82-81b4-87f5a6d56d94/Untitled.png)
    

### Flex Container

- display: flex; 혹은 display: inline-flex; 가 설정된 부모 요소
- 이 컨테이너의 1차 자식 요소들이 Flex item이 됨
- flexbox속성 값들을 사용하여 자식 요소 Flex item들을 배치하는 주체
    
    ![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/1848a85f-9836-46e1-8795-3eff9f43f933/fbcbf995-60ff-4bc1-b17b-0e15eedef50b/Untitled.png)
    

### Flex Item

- flex container 내부에 레이아웃 되는 항목
