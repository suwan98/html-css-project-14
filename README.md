<h1 align="center">14👑 HTML/CSS 프로젝트 👨‍💻</h1>

<br />


<br />

<br />

## ✅ **프로젝트 소개**
<hr />
<br />

### `html/sass`를 이용해 UI를 구성한 OttTaing 프로젝트입니다
<br />


## ✅ **개발 기간** 
<hr />
<br />

### 📅 2023.06.23(금) ~ 2023.06.28(수)

<br />
<br />

## ✅ **배포 주소** 
<hr />
<br />

🚀https://taing14.netlify.app/

<br />


## ✅ **팀원 및 역할 소개**
<hr />
<br />

👤 **박지영 백수빈 조희정 고수완**
- **박지영**
   - 공통 헤더 및 푸터 컴포넌트 개발
   - 온보딩페이지 UI 구현 및 로그인 페이지 UI 구현
- **백수빈**
   -  프로필페이지 UI 구현 및 회원가입 페이지 UI 구현
- **조희정** 
   -  검색페이지 UI 구현 및 비밀번호 찾기 페이지 UI 구현
- **고수완** 
  -  메인페이지 UI 구현 및 아이디 찾기 페이지 UI 구현

<br />
<br />

## ✅ **웹 표준 마크업 과 스타일링**

- **Web Developer validate local html**를 이용하여 page내의 모든 html파일의 `validate`를 완료했습니다
- 프로젝트 마크업시 페이지의 대제목 요소엔 `<h1>` 을 붙였고 아래 섹션에 소제목 요소엔 `<h2>`로 마크업하기로 공통스타일을 결정했습니다
- 전체 문서를 `body`내에 `<header>` `<main>` `<footer>` 세 요소로 나눠서 마크업 진행했으며 안에 내부 요소들은 `<section>`으로 묶어서 마크업했습니다
- 네이밍 컨벤션은 [BEM](https://getbem.com/)방식을 사용하여 클래스 네이밍은 상대적으로 부모인 태그엔 케밥 케이스(Kebab Case) , 하위 자식요소 들에겐 ** `케밥케이스  + __` **로 부여하였습니다

<br />
<br />
  
## ✅ **웹 접근성**
<hr />
<br />

- 전체적인 image들 경우에는 background로 불러와야하기때문에 div태그 내에 `aria-label`을 이용하여 해당 이미지의 대체 텍스트를 제공하였습니다

<br />
<br />

## ✅ **페이지 구성**
<hr />
<br />



***전체 페이지를 반응형으로 구성했습니다.***

> 로그인페이지 모바일 뷰
<img width="320" src="https://github.com/suwan98/html-css-project-14/assets/74893676/1583e730-5ee4-45a0-b9cd-2a80e8bedaa6.png" />

> 로그인페이지 태블릿 뷰
<img width="700" src="https://github.com/suwan98/html-css-project-14/assets/74893676/e5ea8284-276e-432e-af0d-7d584702ff41.png" />

> 로그인페이지 데스크탑 뷰
<img width="980" src="https://github.com/suwan98/html-css-project-14/assets/74893676/77ef73d5-3f7f-4df3-97ff-d1f3f01db90c.png" />
* form의 input(id, password)과 button 영역을 컴포넌트화 시켰습니다.
* button component에는 로그인, 온보딩 시작 버튼, 확인, 테두리 없는 버튼의 네 가지 스타일을 세분화시켰습니다.
 
### 온보딩페이지
> 온보딩페이지 모바일 뷰
<img width="320" src="https://github.com/suwan98/html-css-project-14/assets/74893676/8a0c563b-5ab6-4f9d-ad99-4c35c0c7b841.png" />

> 온보딩페이지 태블릿 뷰

<img width="700" src="https://github.com/suwan98/html-css-project-14/assets/74893676/3b94aeac-5229-4a2e-96f0-f8401eb3a962.png" />

> 온보딩페이지 데스크탑 뷰
<img width="980" src="https://github.com/suwan98/html-css-project-14/assets/74893676/bf9664c5-b50a-4c50-be8f-fd7f9ca0e7d6.png" />
* 온보딩 영역의 첫 번째 섹션은 백그라운드 이미지를 두 개 겹침으로써 그라데이션 효과를 완성했습니다.
* 두 번째, 세 번째 영역의 콘텐츠들은 애니메이션 효과를 통해 무한 슬라이드를 완성했습니다.
* hover시 애니메이션이 멈추며 사진 크기가 커집니다.

### 헤더
> 헤더 simple1
<img width="980" src="https://github.com/suwan98/html-css-project-14/assets/74893676/bf450509-7f84-469f-aea9-845db7719b9b.png" />

> 헤더 simple2
<img width="980" src="https://github.com/suwan98/html-css-project-14/assets/74893676/9987a456-3f8d-4a4c-8bf9-a92c95df4640.png" />

> 헤더 simple3
<img width="980" src="https://github.com/suwan98/html-css-project-14/assets/74893676/6e5e006b-2490-43dc-8669-4f132f01cb02.png" />
* 헤더는 simple1, simple2, default type 으로 나뉩니다.
* 기본 구조는 default type에 맞춰 제작되었으며 class 탈부착을 통해 simple type으로 변화가 가능합니다.

### 푸터
> 푸터 모바일 뷰
<img width="320" src="https://github.com/suwan98/html-css-project-14/assets/74893676/a3cc91bb-9468-4cf6-be54-623b33c31c75.png" />

> 푸터 태블릿 뷰
<img width="700" src="https://github.com/suwan98/html-css-project-14/assets/74893676/d08da4d6-227d-43b9-9337-7db2a0ac6263" />

> 푸터 데스크탑 뷰
<img width="980" src="https://github.com/suwan98/html-css-project-14/assets/74893676/e56e8e80-4596-4688-b77d-7d2edd839d58.png" />
* 푸터는 데스크탑/태블릿이 유사하고 모바일에서 변화가 있습니다. 
* 따라서 푸터 내비게이션을 제외한 비즈니스 정보 영역을 모바일에서는 숨김 처리하여 반응형을 완성했습니다.
* 푸터 sns 영역은 이미지 sprite 기법을 활용해 리소스 로딩 속도를 최적화하고자 했습니다.

  

## **프로필 선택**
<img src="./src/assets/readme-images/soobin/profiles_mobile.png" width="320">
<img src="./src/assets/readme-images/soobin/profiles_tablet.png" width="700">
<img src="./src/assets/readme-images/soobin/profiles_desktop.png" width="980">

* 데스크화면과 태블릿화면은 유사합니다.
* ul, li태그를 활용해 가상 선택자와 position을 활용해 잠금화면을 나타내게 하였으며 flex를 활용해 사용자들의 프로필을 반응형 별로 나누었습니다.

## **프로필 편집**
<img src="./src/assets/readme-images/soobin/profilesEdist_mobile.png" width="320">
<img src="./src/assets/readme-images/soobin/profilesEdit_tablet.png" width="700">
<img src="./src/assets/readme-images/soobin/profilesEdit_desktop.png" width="980">


* 데스크화면과 태블릿화면은 유사합니다.
* 프로필 선택 페이지와 같이 ul, li태그를 활용해 가상 선택자에 편집화면을 나타내게 하였으며 flex를 활용해 사용자들의 프로필을 반응형 별로 나누었습니다.

## **메인페이지**

> 메인페이지 데스크탑 뷰

<img src='./src/assets/readme-images/수완님/d_main-banner.png' width="980">
<br />
<img src='./src/assets/readme-images/수완님/d_main-sectino1.png' width="980">
<br />
<img src='./src/assets/readme-images/수완님/d_main-section2.png' width="980">
<br />
<img src='./src/assets/readme-images/수완님/d_main-section3.png' width="980">
<br />
<img src='./src/assets/readme-images/수완님/d_main-section4.png' width="980">
<br />
<img src='./src/assets/readme-images/수완님/d_main-section5.png' width="980">
<br />
<img src='./src/assets/readme-images/수완님/d_main-last.png' width="980">


> 메인페이지 태블릿 뷰

<img src='./src/assets/readme-images/수완님/t_main1.png' width="700">
<br />
<br />
<img src='./src/assets/readme-images/수완님/t_main2.png' width="700">


> 메인페이지 모바일 뷰

<img src='./src/assets/readme-images/수완님/m_section1.png' width="320">
<br />
<img src='./src/assets/readme-images/수완님/m_section2.png' width="320">
<br />
<img src='./src/assets/readme-images/수완님/m_section3.png' width="320">
<br />
<img src='./src/assets/readme-images/수완님/m_section4.png' width="320">
<br />
<img src='./src/assets/readme-images/수완님/m_section6.png' width="320">
<br />

- 메인페이지는 총 하나의 큰 메인페이지 배너 (section 0) + 나머지 7개의 섹션으로 분리하여 마크업하였으며 
- 각각의 섹션들은 `flex`를 사용해서 `gap`속성을 부여해 여백을 주었습니다

## **아이디 찾기**

<img src='./src/assets/readme-images/수완님/m_id.png' width="320">
<img src='./src/assets/readme-images/수완님/t-id.png' width="700">
<img src='./src/assets/readme-images/수완님/d_id.png' width="980">

-  아이디 찾기 페이지는 모바일에선 아이디 찾기 텍스트가 TVING ID 로그인으로 바뀌도록 스타일링했습니다
-  크기가 작아질수록 전체 `padding`을 축소하여  전체 간격을 조정하였고
-  크기가 작아질 수록 `font-size`도 다르게 부여해 반응형으로 만들었습니다