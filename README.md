# TRIPFY
Tripfy는 사용자 개인이 가이드가 되어 자신의 여행 코스를 패키지로 다른 사용자들에게 판매가 가능하고,
커뮤니티 기능으로 동행을 구하거나 여러 정보를 공유할 수 있는 사이트입니다.

## 기술스택

### 언어
HTML, CSS, JavaScript, Java

### 프론트엔드
Spring(Tymeleaf)

### 백엔드
Spring/ SpringBoot

### 데이터베이스
MySQL

## 함께한 사람들
박기호(팀장) 박민수 유성휘 최영환 정상현

## 개발기간
### 2024.05.10 ~ 2024.06.14 (5주)

## 구현기능
● 패키지 등록(타임라인생성 제외), 조회, 수정, 삭제
● 패키지 결제(부트페이 api 활용)

## 미구현 기능
● 채팅에 있어서 오류 발생
● 공공데이터 활용 여행지 추천 부가기능 추가 실패
● 결제 취소시 api연동 자동 환불기능


# 사용법
## 1. sts, lombok 설치
Tripfy는 sts, mysql를 이용해 개발했어요

## 2. 파일, 디렉토리 세팅
application.properties line:3 dataSource설정에서 사용하시려는 데이터베이스 정보를 입력해주세요
application.properties line:28 아래의 파일 경로를 본인의 환경에 맞게 설정해주세요

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
