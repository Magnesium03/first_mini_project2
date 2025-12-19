# HODU - 랜딩 페이지


## 1. 프로젝트 개요

### 1.1 목표
- **웹 표준을 준수한 시맨틱 마크업**: HTML5 시맨틱 태그를 활용하여 구조적이고 접근성 높은 웹 페이지 구현
- **반응형 웹 디자인(RWD)**: 데스크탑, 모바일 등 다양한 디바이스 환경에 최적화된 레이아웃 제공
- **Figma 디자인 구현**: 제공된 디자인 시안을 오차 없이 정교하게 퍼블리싱하는 능력 배양
- **순수 CSS 활용**: 별도의 프레임워크 없이 Flex와 Grid를 활용한 레이아웃 설계

### 1.2 주요 기능
- **반응형 레이아웃**: 
  - Desktop (1920px 이하)
  - Mobile (768px 이하)
- **모달(Modal) 인터페이스**: 구독 버튼 클릭 시 팝업 및 모바일 메뉴 구현 (HTML/CSS 기반 구조)
- **이미지 갤러리**: CSS Grid를 활용한 3열 카드 레이아웃
- **Scroll Top**: 페이지 최상단으로 이동하는 고정 버튼 배치
- **Header**: 스크롤 시 상단에 고정되는 Sticky Header 구현

### 1.3 팀 구성 & 개발 기간
- **개발 기간**: 2025.12.11 ~ 2025.12.18 (7일)
- **팀 구성**: 1인 개발 (Personal Project)

<table>
  <tr>
    <th align="center">Name</th>
    <th align="center">Role</th>
    <th align="center">Github</th>
  </tr>
  <tr>
    <td align="center"><strong>강민기</strong></td>
    <td align="center">Frontend Developer<br>(Publishing)</td>
    <td align="center">
        <a href="https://github.com/magnesium03">
            <img src="https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=GitHub&logoColor=white"/>
        </a>
    </td>
  </tr>
</table>


## 2. 개발 환경 및 배포 URL

### 2.1 기술 스택
- **Language**: HTML5, CSS3
- **Editor**: Visual Studio Code
- **Versioning**: Git, GitHub
- **Deploy**: GitHub Pages

### 2.2 배포 URL
- **Live Demo**: [https://magnesium03.github.io/first_mini_project2/](https://magnesium03.github.io/first_mini_project2/)
- **Design Source**: [Figma Link](https://www.figma.com/design/rbi8px4O2GrnXN4gK0ZaLv/WENIV_FE_%EC%8B%A4%EC%8A%B5-%EC%98%88%EC%A0%9C?node-id=49-1791&p=f&t=NlVsrGvdZ10glS7b-0)


## 3. UI/UX 및 구현 화면

## 3.1 와이어프레임 및 디자인피그마(Figma)
- 디자인 시안을 바탕으로 픽셀 퍼펙트(Pixel Perfect)를 지향하며 개발하였습니다.
- Font: Spoqa Han Sans Neo

## 3.2 화면 설계

### 1. 메인 웹페이지 (Main Page)
<table>
  <tr>
    <th align="center">구분</th>
    <th align="center">데스크탑 (Desktop)</th>
    <th align="center">데스크탑 축소 버전</th>
    <th align="center">모바일 (Mobile)</th>
  </tr>
  <tr>
    <td align="center"><strong>전체 화면</strong></td>
    <td align="center">
      <img src="./images/screenshot_desktop_1.png" width="50%" alt="데스크탑 화면1">
      <img src="./images/screenshot_desktop_2.png" width="50%" alt="데스크탑 화면2">
      <img src="./images/screenshot_desktop_3.png" width="50%" alt="데스크탑 화면3">
      <img src="./images/screenshot_desktop_4.png" width="50%" alt="데스크탑 화면4">
    </td>
    <td align="center">
      <img src="./images/screenshot_desktop_shrink_1.png" width="50%" alt="줄어든 데스크탑 화면1">
      <img src="./images/screenshot_desktop_shrink_2.png" width="50%" alt="줄어든 데스크탑 화면2">
      <img src="./images/screenshot_desktop_shrink_3.png" width="50%" alt="줄어든 데스크탑 화면3">
      <img src="./images/screenshot_desktop_shrink_4.png" width="50%" alt="줄어든 데스크탑 화면4">
      <img src="./images/screenshot_desktop_shrink_5.png" width="50%" alt="줄어든 데스크탑 화면5">
      <img src="./images/screenshot_desktop_shrink_6.png" width="50%" alt="줄어든 데스크탑 화면6">
    </td>
    <td align="center">
      <img src="./images/screenshot_mobile_1.png" width="50%" alt="모바일 화면1">
      <img src="./images/screenshot_mobile_2.png" width="50%" alt="모바일 화면2">
      <img src="./images/screenshot_mobile_3.png" width="50%" alt="모바일 화면3">
      <img src="./images/screenshot_mobile_4.png" width="50%" alt="모바일 화면4">
      <img src="./images/screenshot_mobile_5.png" width="50%" alt="모바일 화면5">
    </td>
  </tr>

### 2. 팝업창 (Popup / Modal)
<table>
  <tr>
    <th align="center">구분</th>
    <th align="center">데스크탑 (Desktop)</th>
    <th align="center">모바일 (Mobile)</th>
  </tr>
  <tr>
    <td align="center"><strong>팝업창 1</strong></td>
    <td align="center">
      <img src="./images/screenshot_desktop_popup.png" width="50%" alt="데스크탑 팝업창">
    </td>
    <td align="center">
      <img src="./images/screenshot_mobile_popup.png" width="50%" alt="모바일 팝업창1">
    </td>
  </tr>
  <tr>
    <td align="center"><strong>팝업창 2</strong></td>
    <td align="center">
      -
    </td>
    <td align="center">
      <img src="./images/screenshot_mobile_popup2.png" width="50%" alt="모바일 팝업창2">
    </td>
  </tr>
</table>

## 4. CSS 활용

### 4.1 반응형 미디어 쿼리 전략
- 다양한 기기 대응을 위해 Breakpoint를 1280px, 768px로 설정하여 레이아웃을 조정했습니다.
- Desktop ver. 즉, 1920px 이하, 768px 이상일 때의 반응형 구조와 Mobile ver. 즉, 768px 이하, 390px 이상일 때의 반응형 구조를 나누어 설계했습니다.
- 1280px에 Breakpoint를 준 이유는 Desktop ver.에서 메인의 컨테이너 영역의 너비가 1280px였기 때문에 1280px보다 작아지는 경우에도 Desktop ver.을 유지하면서 자연스럽게 모바일 버전으로 넘어갈 수 있도록 반응형 구조를 설계하였습니다.
- flex-wrap을 통해 뷰포트의 크기에 따라 자연스럽게 이미지와 글자의 배치가 바뀌도록 하였습니다.

### 4.2 CSS 변수(Variables) 활용
- 유지보수 효율성을 높이기 위해 색상 코드를 :root 변수로 관리했습니다.

```CSS
:root {
    --bg-color: #F2E9D8;
    --p-color: #000000;
    --btn-color: #D97652;
    --btn-p-color: #FFFFFF;
    --sub-color:#263140;
    --social-color:#F29D52;
    --shadow: rgba(0, 0, 0, 0.25);
    --scroll-top-btn-bg-color: #FFFFFF80;
    --scroll-top-btn-bd-color: #C4C4C4;
    --footer-nav-color: #767676;
    --modal-bg-color: #F2E9D8;
}
```

### 4.3 z-index 활용
- scroll top button이 hover 시, z-index가 바뀌도록 하여 색이 더 짙은 이미지가 드러나도록 하였습니다.


## 5. 개발 회고 및 느낀점

### 5.1 배운 점
- 시맨틱 태그의 중요성: header, main, section, footer 등을 사용하여 문서 구조를 명확히 잡는 법을 익혔습니다.
- Grid & Flex: Grid와 Flex 등을 통해 CSS 레이아웃 시스템을 적용했습니다.
- 크로스 브라우징: reset.css를 통해 브라우저 간 기본 스타일 차이를 최소화하는 경험을 했습니다.

### 5.2 향후 개선 사항
- JavaScript 기능 추가: 현재는 UI만 구현되어 있는 모달창 닫기 기능, 이메일 유효성 검사, 스크롤 탑 버튼 동작 등을 JavaScript로 구현하여 동적인 웹사이트로 발전시킬 예정입니다.
- 이미지 최적화: 고해상도 이미지가 많아 로딩 속도 개선을 위해 picture 태그 등을 고려하고 있습니다.