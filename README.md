# WATERBOMB - Project

> 이 프로젝트는 Vue.js를 활용한 프로그레시브웹앱(PWA) 개발자 양성과정 [14th]에서 진행한 팀 프로젝트입니다.

> 개발기간 : 2024.06 ~ 2024.07

> github pages : <https://devkisungjang.github.io/waterbomb_project/html/main.html>

## 💁‍♂️ 프로젝트 소개

**워터밤 티켓구매 프로그램**은 대중에게 인기 있는 워터밤 콘서트의 티켓 구매를 간편하게 할 수 있도록 설계된 웹 애플리케이션입니다. 사용자 친화적인 인터페이스를 통해 쉽게 콘서트 일정과 출연진 정보를 확인하고, 티켓 구매를 진행할 수 있습니다.

## 🎯 프로젝트 목표

이 프로젝트는 대규모 콘서트와 같은 이벤트에서 티켓 구매 과정을 간소화하여 사용자 경험을 향상시키는 것을 목표로 합니다. 특히, 로그인한 사용자와 비회원 모두가 쉽게 티켓을 구매하고 관리할 수 있도록 다양한 기능을 제공하며, 안전하고 직관적인 결제 시스템을 구현했습니다.

## 📈 주요 기능
- 콘서트 일정 및 출연진 정보 제공: 사용자는 간편하게 콘서트 일정과 출연진 정보를 확인할 수 있습니다.
- 티켓 구매 프로세스: 사용자들은 원하는 날짜와 지역을 선택하고, 손쉽게 티켓을 구매할 수 있습니다.
- 로그인 및 비회원 티켓 조회: 로그인한 사용자는 물론 비회원도 자신의 티켓을 조회하고 결제할 수 있습니다.
- 결제 시스템: 사용자는 로그인 여부와 상관없이 간편하게 티켓 결제를 진행할 수 있으며, 결제가 완료되면 마이티켓페이지에서 티켓 정보를 확인할 수 있습니다.

## 🔗디자인 및 기획
- [Figma 링크](https://www.figma.com/design/pNvtYRE4FaMr6btL9YmxRp/%EC%9E%A5%EA%B8%B0%EC%84%B1?node-id=2052-1421)

## 💁‍♂ 팀원 소개

| 장기성 | 이승빈 | 최 은 | 장채연 |
| :---: | :---: | :---: | :---: |
|  [@devkisungjang](https://github.com/devkisungjang) | [@leebin96](https://github.com/leebin96) | [@eunidayo](https://github.com/eunidayo) | [@meoritdol](https://github.com/meoritdol) |
| 기획, 퍼블리싱(Leader) | PM, 퍼블리싱 | 디자인, 퍼블리싱(Leader) | 디자인, 퍼블리싱 | 디자인, 퍼블리싱 |

### 🛠️ 사용된 기술 스텍

<img src="https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=HTML5&logoColor=white"> <img src="https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=CSS3&logoColor=white"> <img src="https://img.shields.io/badge/Javascript-F7DF1E?style=flat&logo=Javascript&logoColor=white"> <img src="https://img.shields.io/badge/Bootstrap-7952B3?style=flat&logo=Bootstrap&logoColor=white"> <img src="https://img.shields.io/badge/Figma-F24E1E?style=flat&logo=Figma&logoColor=white">
## 🗂️ 프로젝트 구조

```
waterbomb_project/
│
├── html/          # HTML 파일들이 위치한 폴더
│   ├── main.html               # 워터밤 일정, 출연진 정보, 티켓 구매/확인 버튼이 있는 페이지
│   ├── login01.html            # 결제하기 버튼 클릭 시 나오는 로그인 페이지
│   ├── login02.html            # myticket 버튼 클릭 시 나오는 로그인 페이지 (비회원 티켓 조회 버튼 포함)
│   ├── ticket_selection.html   # 공연 날짜와 지역 선택 및 티켓 수량 선택 페이지
│   ├── payment.html            # 로그인한 사용자 티켓 결제 페이지
│   ├── payment_guest.html      # 비회원 사용자 티켓 결제 페이지
│   ├── payment_success.html    # 결제 완료 페이지
│   ├── myticket.html           # 구매한 티켓 확인 페이지
│   ├── myticket_empty.html     # 구매한 티켓이 없을 경우 나오는 페이지
│   └── mypage.html             # 결제 완료 후 이동되는 마이페이지
│
├── css/           # CSS 파일들이 위치한 폴더
│   └── (스타일 시트 파일들)
│
├── image/         # 이미지 파일들이 위치한 폴더
│   └── (이미지 파일들)
│
├── js/            # JavaScript 파일들이 위치한 폴더
│   └── (스크립트 파일들)
│
└── video/         # 비디오 파일들이 위치한 폴더
    └── (비디오 파일들)
```

### 💁‍♂️ 맡은 역할
- 장기성 : main.html, login01.html, login02.html
- 이승빈 : ticket_selection.html
- 최 은 : payment_success.html, mypage.html 
- 장채연 : payment.html, payment_guest.html, myticket.html, myticket_empty.html

## 💻 프로젝트 설치 및 실행

### 설치 및 실행

1. 리포지토리 클론

```
cd your-project
git clone https://github.com/devkisungjang/waterbomb_project/
```

2. 실행

- 이 프로젝트는 HTML, CSS, JavaScript로 구성되어 있어 특별한 설치 과정 없이 브라우저에서 실행할 수 있습니다.


    
