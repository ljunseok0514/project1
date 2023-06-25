# 📂 MarketKurly

## 🦁 멋쟁이사자처럼 FE 6기, HTML / CSS 프로젝트(1조: 1희1비)

마켓컬리를 기반으로 작성된 '마켓칼리' 피그마 시안을 참고하여 만든 HTML + CSS 프로젝트입니다.

## 🗓️ 프로젝트 기간 및 팀원 👨🏻‍💻 👩‍💻

**2023.06.23 ~ 2023.06.28**

👨‍👩‍👦‍👦 **Front-End(4명)** : 김봉석, 노치현, 이준석, 정소이

## ⚔️ 기술 스택

**Front-End**
<br>

<p align="center">

<img src="https://img.shields.io/badge/html5-E34F26?style=for-the-badge&logo=html5&logoColor=white">
<img src="https://img.shields.io/badge/css3-1572B6?style=for-the-badge&logo=css3&logoColor=white">

<img src="https://img.shields.io/badge/Sass-cc6699?style=for-the-badge&logo=Sass&logoColor=white">

## ⛳️ 역할 담당

<details>
    <summary>🧐 김봉석</summary>
    <!-- summary 아래 한칸 공백 두고 내용 삽입 -->
        * 이벤트 + 배너 + 사이드바 섹션
  </details>
<details>
    <summary>🤓 노치현</summary>
    <!-- summary 아래 한칸 공백 두고 내용 삽입 -->
        * 공통 내비게이션 +
  </details>
<details>
    <summary>😎 이준석</summary>
    <!-- summary 아래 한칸 공백 두고 내용 삽입 -->
        * 공통 헤더 +
  </details>
  <details>
    <summary>😃 정소이</summary>
    <!-- summary 아래 한칸 공백 두고 내용 삽입 -->
        * 상품 섹션
  </details>

### ✏️ 네이밍 컨벤션

- BEM 패턴
  - 자식요소: \_\_ => event\_\_title
  - 상태: -- => button--active

### 🚫 웹 접근성(공통)

- 마크업

  - img 태그에 alt(대체 텍스트) 부여

  - form 태그 내 label 필요(a11yHidden 처리)

  - section/div 내 heading이 없어도 heading 부여(a11yHidden 처리)

  - push 전 validator 확인(유효성 검증)

  - a태그 내 target=”\_blank”지정시 rel=”noreferrer noopener” 속성 부여

### 🌈 믹스인(공통)

### ✨ SEO

## 📜 페이지(섹션) 설명

![마켓칼리HTML구조](/src/kurlyHtml.png)

### 메인 페이지

#### Header
```dom
header.header
└── div.header__group
    └── div.header__group__tab
        └── h1.group__logo
            └── img.group__logo_img
        └── ul.group__itemBox
            └── li.grop__itemBox__item
                └── a.itemBox__link[href="/"] (마켓칼리)
            └── li.grop__itemBox__item
                └── span.itemBox__item__divider[aria-hidden="true"] (ㅣ)
                └── a.itemBox__link[href="/"] (뷰티칼리)
    └── form.header__group__searchForm[action="/"][method="POST"]
        └── fieldset.group__searchForm__fieldset
            └── legend.a11yHidden (검색 폼)
            └── div.searchForm__group
                └── div.searchForm__group__formInputBox
                    └── label.a11yHidden[for="search"] (검색어)
                    └── input.group__input[type="search"][id="search"][name="search"][required][placeholder="검색어를 입력하세요."]
                └── button.searchForm__group__button[type="submit"]
    └── ul.header__group__myPage
        └── li.group__myPageLi
            └── button.group__myPageLi__button[type="button"][aria-label="배송지 등록"]
        └── li.gorup__myPageLi
            └── button.group__myPageLi__button[type="button"][aria-label="찜하기"]
        └── li.gorup__myPageLi
            └── button.group__myPageLi__button[type="button"][aria-label="장바구니"]
    └── ul.header__group__memberOnly
        └── li.group__memberOnlyLi
            └── a[href="/"] (회원가입)
        └── li.group__memberOnlyLi
            └── span.group__memberOnlyLi__divider[aria-hidden="true"] (ㅣ)
            └── a[href="/"] (로그인)
        └── li.group__memberOnlyLi
            └── span.group__memberOnlyLi__divider[aria-hidden="true"] (ㅣ)
            └── a[href="/"] (고객센터)

```

- 마크업


1. 작업하면서 태그 마다 클래스 속성을 다 써본적 없는데 처음으로 다 클래스를 부여했다<br>
2. 스크린리더가 읽기, 읽기않기 위한 태그, 속성사용 ex) label,aria-label, aria-hidden <br>
3. 회원가입, 로그인, 고객센터 부분이 시각적으로 제일 상단에 위치해서 태그위치도 상단에 있었으나 중요도로는 우선순위가 떨어지기에 제일 하단으로 옮김<br>
4. 검색창 부분을 시멘틱한 구조로 짜기 위해 form, fieldset, label 태그 사용

- CSS

#### Nav

- 마크업
- CSS

#### Section(event)

- 마크업
- CSS

#### Section(goods1+ goods2)

- 마크업
- CSS

#### Section(banner + side)

- 마크업
- CSS

### Footer

- 마크업
- CSS

## ⭐️ 결과물
