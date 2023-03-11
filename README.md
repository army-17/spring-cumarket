# ICIA-CuMarket
인천일보아카데미 세미 프로젝트 : 중고거래 사이트 CuMarket

- **프로젝트 기간 : 2022.11 - 2022.11 (약 1주일)**
- **프로젝트 인원 : 4명**
- **프로젝트 개요 : 중고거래 플랫폼 CuMarket**
- **사용 프로그램 : IntelliJ, MySQL**
- **사용 언어 : Java, Html, Css, JavaScript, jQuery**

## 환경 구성

- IDE(통합개발환경) : IntelliJ Ultimate
- 프레임워크 : Spring Boot
- 데이터베이스 : MySQL
- DB 접근 기술 : JPA
- View Template : Thymeleaf

## 프로젝트 설명

CRUD 기능 위주로 당근마켓을 벤치마킹한 중고거래 사이트 CuMarket을 제작하였습니다.

**[ 사이트의 주요 기능 ]**

중고거래를 원하는 물품을 등록하고 다른 이용자들은 게시글을 볼 수 있습니다.

**[ 메인 페이지 ]**
<img width="485" alt="image" src="https://user-images.githubusercontent.com/96126414/224473398-032b3cce-a009-4eed-8071-38dc0228e3cf.png">
<br><br>

**[ 주요 담당 기능 ]**

1. 로그인 페이지
<img width="485" alt="image" src="https://user-images.githubusercontent.com/96126414/224474931-30e404f2-3443-4834-b070-0f83e01d5991.png">
<br><br>

2. 글 작성 페이지
<img width="485" alt="image" src="https://user-images.githubusercontent.com/96126414/224474981-1ad917ed-0d27-49fc-bd89-c454a544f467.png">
<br><br>

## DB

**ERD**

<img width="402" alt="cuMarket ERD" src="https://user-images.githubusercontent.com/96126414/215404216-d0afc262-3cbc-4294-bd85-9f439f3ffefd.png"><br><br>

**DB 설명**
- membertbl : 사이트 이용자와 관리자(admin) 정보
- boardtbl : 사이트 이용자들이 작성한 글 정보
- boardfiletbl : 해당 게시에 업로드 된 파일 정보

## 마치며
#### 소감
JPA와 thymeleaf를 배우고 바로 진행한 프로젝트로 기본적인 CRUD 기능만 구현하였습니다. ModelAndView나 thymeleaf를 아직 능숙하게 다루기에는 실력이 많이 부족하여 기본적인 CRUD 작업을 진행하는 것에도 어려움이 있었습니다. 처음 프로젝트 계획 당시, 댓글 기능을 구현하기로 하였지만 시간 상 제외하고 진행한 것이 많이 아쉬움이 남습니다. 추후에 공부를 진행한 후 개인적으로 보완하는 작업을 진행해볼 생각입니다. 


