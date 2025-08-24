# Fa05-fin-TMI
KPMG Future Academy 5기 TMI팀 마지막 프로젝트

---------------------------------------

# 프로젝트 계획서

## 1. 프로젝트 개요
- **프로젝트명** : TMI
- **목표** : AI 말벗 기반 가족 디지털 동행 서비스 TRIPOT
- **기간** : 2025년 6월 10일 - 2025년 8월 9일

## 2. 프로젝트 일정
- **분석 및 설계** : 2025년 6월 10일 - 6월 23일
- **개발** : 2025년 6월 24일 - 8월 8일
- **발표** : 2025년 8월 9일

## 3. 팀 구성
<img src="./readme_src/team.png" alt="Team" height="400"/>

---------------------------------------

# 서비스 개요
<img src="./readme_src/service_intro.JPG" alt="intro"/>

---------------------------------------

# 서비스 기능

---------------------------------------

# 설치 및 실행 방법

## 1. Clone Repository
```
git clone https://github.com/KpmgFuture-Academy/Fa05-fin-TMI.git
```

## 2. Install Dependencies
```
pip install -r requirements.txt
```

## 3. Developer Options
- 스마트폰 설정에서 개발자 옵션에서 USB 디버깅 on

## 4. Run Backend
```
# tripot_backend에서
docker-compose up -d --build
```

## 5. Run Frontend
```
# tripot_family_app에서
npx react-native run-android

# tripot_seninor_app에서
npx react-native start --port 8082

# 어르신트라이팟 앱에서 스마트폰을 흔들어 개발자 매뉴로 들어가 Change Bundle Location 클릭 후 본인ip:8082 입력 
```
---------------------------------------