![캐릭터(프로젝트 소개)](https://github.com/Burgundysocks/final-project/assets/136434305/7e148ea8-72ed-487d-ac36-14c453672033)

# TRIPFY
#### Tripfy는 사용자 개인이 가이드가 되어 자신의 여행 코스를 패키지로 다른 사용자들에게 판매가 가능하고,
#### 커뮤니티 기능으로 동행을 구하거나 여러 정보를 공유할 수 있는 사이트입니다.

## Main Color

![스크린샷 2024-06-26 오후 12 20 09](https://github.com/Burgundysocks/final-project/assets/136434305/678bc1cf-7867-4db8-85ba-1a6c7132b54d)

## Tech-Stack

### 
![js](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=JavaScript&logoColor=white)
![html](https://img.shields.io/badge/HTML-239120?style=for-the-badge&logo=html5&logoColor=white)
![css](https://img.shields.io/badge/CSS-239120?&style=for-the-badge&logo=css3&logoColor=white)
### 
![java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)

### Tool
![visualstudiocode](https://img.shields.io/badge/Visual_Studio_Code-0078D4?style=for-thebadge&logo=visual%20studio%20code&logoColor=white)
![eclipse](https://img.shields.io/badge/Eclipse-2C2255?style=for-the-badge&logo=eclipse&logoColor=white)
![mysql](https://img.shields.io/badge/MySQL-00000F?style=for-the-badge&logo=mysql&logoColor=white)

![](https://img.shields.io/badge/Figma-F24E1E?style=for-the-badge&logo=figma&logoColor=white)
![](https://img.shields.io/badge/Sourcetree-0052CC?style=for-the-badge&logo=Sourcetree&logoColor=white)

### Front-end
![](https://img.shields.io/badge/Spring-6DB33F?style=for-the-badge&logo=spring&logoColor=white)
(Tymeleaf)

### Back-end
![](https://img.shields.io/badge/Spring-6DB33F?style=for-the-badge&logo=spring&logoColor=white)

### DataBase
![mysql](https://img.shields.io/badge/MySQL-00000F?style=for-the-badge&logo=mysql&logoColor=white)

## Team
박기호(팀장) 박민수 유성휘 최영환 정상현

## Period
### 2024.05.10 ~ 2024.06.14 (5주)

## Main function
#### ● 패키지 작성
![스크린샷 2024-06-26 오후 12 22 02](https://github.com/Burgundysocks/final-project/assets/136434305/1077696a-05b2-4fc5-8057-839bb4d091bc)

####  ● 게시판
![게시판1(주요기능 및 화면)](https://github.com/Burgundysocks/final-project/assets/136434305/0c710d3c-174d-4f6c-a4f2-2a215c0b1f6f)
![게시판2(주요기능 및 화면)](https://github.com/Burgundysocks/final-project/assets/136434305/f233e66b-9771-4df7-8dd0-2f201a179285)
1. 게시글 정렬

2. 키워드(지역) 검색

3. 키워드 검색

4. 여행 후기 및 동행 관련 게시글 목록


## My Role
#### ● 패키지 등록(타임라인생성 제외), 조회, 수정, 삭제
![스크린샷 2024-06-26 오후 12 22 02](https://github.com/Burgundysocks/final-project/assets/136434305/1077696a-05b2-4fc5-8057-839bb4d091bc)
국내/해외 -> 지역 -> 여행기간 -> 간단 소개글 작성 -> 인원 수 및 가격 -> 사진 등록순 으로 진행되는 모달 창

#### ● 패키지 결제(부트페이 api 활용)
![스크린샷_2024-06-24_오후_5 16 22](https://github.com/Burgundysocks/final-project/assets/136434305/959b511b-dffa-4a3f-b287-cb7b7fae45c2)
![스크린샷_2024-06-09_오후_5 06 46](https://github.com/Burgundysocks/final-project/assets/136434305/8bd30cd1-25fe-4566-aba4-4daf37ffc571)

부트페이 api를 이용하여 패키지를 결제한 이용자의 정보 및 결제 가격, 결제 수단 DB 및 부트페이 관리자 페이지저장




## 프로젝트 미구현 기능
#### ● 채팅 오류 - 채팅이 일정량 이상 쌓이면 에러가 발생
#### ● 여행지 추천 - 공공데이터 활용으로 국내 여행지 추천 페이지
#### ● 자동환불 - 결제 취소시 부트페이 관리자 페이지에서 자동 환불
#### ● 소셜 로그인 - 카카오, 네이버, 구글 등 소셜아이디 로그인(개인정보 관련 이슈)
#### ● 본인 인증  - Pass본인인증(개인정보 관련이슈)


# How to use
## 1. sts, lombok 설치
Tripfy는 sts, mysql를 이용해 개발
Maven을 이용해 만든 프로젝트

## 2. 파일, 디렉토리 세팅
#### application.properties line:3 dataSource설정에서 사용하시려는 데이터베이스 정보를 입력해주세요
#### application.properties line:28 아래의 파일 경로를 본인의 환경에 맞게 설정해주세요

## 3. api 키 세팅
Tripfy를 사용하시기 전에 4종류의 api 키를 기입해주세요

### a. google map javascript
src/main/resource/temlplate/board/get.html line:138

src/main/resource/temlplate/board/modify.html line:229

src/main/resource/temlplate/package/pget.html line:173

src/main/resource/temlplate/package/pmodify.html line:118

src/main/resource/temlplate/package/timelineGet.html line:128

src/main/resource/temlplate/package/timelineWrite.html line:141

### b. google place
src/main/resource/temlplate/user/join.html line:204

### c. bootpay
src/main/resource/temlplate/package/pay.html line:241

src/main/resource/temlplate/package/pay.html line:311

### d. coolSMS
src/main/java/com/t1/tripfy/controller/user/SMSController.java line: 49

src/main/java/com/t1/tripfy/controller/user/SMSController.java line: 50

src/main/java/com/t1/tripfy/controller/user/SMSController.java line: 54

# 번외: 더미 데이터 넣기
+sts에서 프로젝트를 실행합니다

+url: localhost:8080/manager/managerAccess을 입력해 이동합니다

+더미데이터 버튼을 클릭합니다

+sts 콘솔을 통해 데이터가 삽입되는지를 확인합니다

+정상적으로 데이터 삽입이 완료되면 콘솔창에 [성공]이라고 쓰인 에러메시지가 반환됩니다
