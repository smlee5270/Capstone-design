# Capstone-design

![KakaoTalk_20191208_190953699](https://user-images.githubusercontent.com/9815703/70439086-91375b80-1ad2-11ea-8cdf-ba4c3953d8dd.jpg)

## Project Name : Smart Mirror 
## Introduction
사용자가 시간과 노력을 들이지 않아도 일상생활 정보를 시각적으로 확인할 수 있으며, 산업 현장에서는 간편한 모니터링 목적으로도 응용 가능한 스마트 디바이스를 제작한다.

## 기능 
### Smart Mirror
[Magic Mirror2](https://magicmirror.builders/) Open Source code 및 각종 모듈 사용 

### 아두이노 인체감지 센서 
인체 감지 센서를 이용하여 사용자를 감지하여 Mirror 테두리 무드등 기능 

### 음성인식 
Google assistant / snowboy 이용한 hot word detection

### 사용 한 모듈 종류 및 변경사항
공통
 1. 도시 공기 상태 [MMM-AirQuality](https://github.com/CFenner/MMM-AirQuality)
 2. 시계 [Clock](https://github.com/MichMich/MagicMirror/tree/master/modules/default/clock)
 3. 날씨 [Weather Forecast](https://github.com/MichMich/MagicMirror/tree/master/modules/default/weatherforecast)
   - 변경사항 : 날씨 아이콘 이미지 변경
 4. Calendar week [MMM-CalendarWeek](https://github.com/heskja/MMM-CalendarWeek)
 5. Calendar Monthly [Calendar Monthly](https://github.com/KirAsh4/calendar_monthly)
 6. 할일 [MMM-Wunderlist](https://github.com/paviro/MMM-Wunderlist)
 
얼굴인식
 1. 얼굴인식 [MMM-Facial-Recognition-OCV3](https://github.com/normyx/MMM-Facial-Recognition-OCV3)
   - 변경사항 : 얼굴 인식 성공시 (Module: Alert) 모듈을 추가하여 노티피케이셔 알람 설정 
   
음성인식
 1. HotWord [MMM-Hotword](https://github.com/eouia/MMM-Hotword)
 2. Google assistant [MMM-AssistantMk2](https://github.com/eouia/MMM-AssistantMk2)

### 작업 완료 내역 및 모듈 테스트 
- 백그라운드 이미지 변경 / 날씨 이모티콘 변경 / 아두이노 센서를 이용한 LED 제어 / 셋톱박스 프레임 제작 (catia 작업 -> 3D프린팅) 테스트 완료
- 얼굴인식을 통한 개인 Private Samart mirror 모듈 테스트 완료
- 할일 모듈 환경설정 및 테스트 완료 
- 5일 단위 캘린더 모듈 테스트 완료 
- 대한민국 특정 지역 공기질 상태 표시 모듈 테스트 완료 
- 30일 31 일 달력 모듈 테스트 완료 
- 구글 어시턴스 모듈 테스트 완료 
- HotWord 모듈 테스트 완료 

### 작업 일정 
개발일정 |  내용  
:---: | ---  
2019-12-09 | Capstone-design Project start
2019-12-11 | Capstone-design 아이디어 회의 / 주제 선정 / 주제 스마트 미러 
2019-12-13 | 11일 ~ 13일까지 : 프레임 제작을 위한 설계 작업 수행 
2019-12-16 | 16일 ~ 20일까지 : 필요 모듈 테스트 및 환경구축 (시계 / 날씨 / 얼굴인식 / 할일 / 디버깅 로그 모듈 설정) 완료
2019-12-23 | 23일 ~ 27일까지 : 필요 모듈 테스트 및 환경구축 (5일 단위 캘린더 모듈, 음성인식) 완료 
2020-01-03 | Capstone-design Project end 


사용 언어 : 자바 스크립트 CSS HTML 파이썬

제작 인원 : 3명 

제작 기간 : 4주

Team 
협업 방식 : 주 1회 스프린트 미팅, Daily Scrum으로 매일(평일) 개발 상황 공유  
협업 도구 : Google docs, GitHumb  

#### 개발 운영 환경 및 관련 사항 
- [라즈베리파이 Open CV 설치 방법](https://github.com/HUST-Robot/Capstone-design/issues/3)
- [USB 스피커, 마이크 라즈베리파이에 연결하기](https://github.com/HUST-Robot/Capstone-design/issues/13)

#### 설계이슈
- [Error: Cannot find module 'node_helper' 에러가 발생한 경우 고치는 방법](https://github.com/HUST-Robot/Capstone-design/issues/8)
- [.DS_Store 파일을 git에 포함시키지 않기](https://github.com/HUST-Robot/Capstone-design/issues/12)
