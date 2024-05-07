# 딴복 ( 딴짓하면, 복습이다! )
학습 능률 향상 & 학습 태도 개선을 위한 스터디 앱

YOLOv5 알고리즘을 활용한 학습 모델을 통해 사용자의 학습 태도를 분석함과 동시에, 
에빙하우스의 망각곡선 이론을 활용하여 효율적인 학습을 할 수 있도록 도와주는 스터디 애플리케이션

<br />

## 🛠 기술 및 도구
![Java](https://img.shields.io/badge/JAVA-007396?style=flat-square&logo=java&logoColor=white) 
![Python](https://img.shields.io/badge/Python-3776AB?&style=flat-square&logo=Python&logoColor=white)
![Android Studio](https://img.shields.io/badge/Android%20Studio-3DDC84?style=flat-square&logo=Android&logoColor=white) 
![Colab](https://img.shields.io/badge/Google%20Colab-F9AB00.svg?&style=flat-square&logo=googlecolab&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-%23039BE5.svg?style=flat-square&logo=firebase)
![GitHub](https://img.shields.io/badge/Github-%23121011.svg?style=flat-square&logo=github&logoColor=white)

<br>

## 🔗 링크

**Original Repository Link :** [https://github.com/gamjaseob/Review_Project](https://github.com/gamjaseob/Review_Project)

<br />

## 💻 동작 구조도
![시스템 구조도](https://github.com/gamjaseob/Review_Project/assets/54940615/f82a930d-779f-425f-ab45-3e0d4ca05838)

<br>

## 🎯 주요 기능

### 1. 사용자가 학습한 파일에 대한 " 망각 진행률 " 그래프 제공
- 헤르만 에빙하우스의 망각 곡선 이론을 바탕
- 사용자는 그래프를 열람으로써 동기 부여 효과
- 망각 진행률이 60%일 때, 복습 알림 전송

<img width="450" height="600" alt="망각곡선" src="https://github.com/YouHyunji/Application-to-Improve-Learning-Attitudes/assets/54940615/78b3cbb0-f0ec-418a-9db4-79308c49de26.gif" />

<br>
  
### 2. AI 모델 ( YOLOv5 ) 을 적용시킨 학습 태도 분석 ( 집중모드 )

<img width="50%" alt="학습 태도 분석 과정" src="https://github.com/YouHyunji/Review_Project/assets/54940615/4e08069d-4eea-4101-b2f7-65612c34ba2f" />

- 사용자가 자리 이탈 하는 경우와 졸고 있는 경우를 감지
- 집중모드로 학습 후 학습 태도 분석 결과 열람 가능
- 학습 태도 개선 효과

<br>
  
### 3. "복습하기 " 리스트
- 사용자가 학습한 파일 중에서, 시스템이 복습이 필요하다고 판단한 파일을 '복습하기' 리스트에 자동으로 업로드
- '복습하기' 리스트에서는 '집중모드'가 자동 실행
- 시스템이 복습이 잘 되었다고 판단했을 경우에는 복습하기 리스트에서 자동으로 삭제
- 복습 횟수 증가 & 학습 태도를 개선 효과

![복습리스트](https://github.com/YouHyunji/Application-to-Improve-Learning-Attitudes/assets/54940615/208af134-7f28-4da8-aefd-fbfe67991afc)


<br>

## ⏰ 커밋 히스토리

[나의 커밋 히스토리](https://github.com/gamjaseob/Review_Project/commits?author=YouHyunji)
<br/>
<br/>
<br/>

## 할일
🟩 - 구현 🟨 - 작업중 🟥 - 미구현

### 9월 1째주 

🟩 메뉴 버튼 구현 [유현지, 08-26 ~ 08-30]

🟩 과목 카테고리 & 파일 삭제 기능 추가 [유현지, 08-30 ~ 09-03]

🟩 명언 추가 [김지섭, 08-27 ~ 09-03]

🟨 망각곡선 코드 수정 [김지섭, 09-04 ~]


### 9월 2째주

🟩 PDF Viewer의 기능 수정  [유현지, 09-04 ~ 09-07]

🟩 복습리스트에 파일 자동 업로드 기능 [유현지, 09-04 ~ 09-11 ]

🟩 집중모드 적용 로직 구현 [유현지, 09-06 ~ 09-12 ]

🟥 로그인, 회원가입 GUI [노관범, 09-13 ~ ]

🟨 학습 태도 분석 사전조사 [김지섭, 유현지, 09-04 ~ 09-11 ]

### 9월 3째주

🟩 복습리스트의 파일 자동 삭제 기능 [유현지, 09-11 ~ 09-17]

🟩 중복되는 이름의 카테고리, 파일 삭제  오류 해결 [유현지, 09-14 ~ 09-16]

🟩 복습리스트 조건에 따른 분류 기능 [김지섭, 09-13 ~ 09-18]

### 9월 4째주

🟩 집중모드 구현 방법 조사 [김지섭, 09-18 ~ 09-24] 

🟩 YOLOv5 알고리즘 분석 [유현지, 09-18 ~ 09-24] 

🟨 메인화면 GUI (메인로고 제작) [노관범, ]

🟥 로딩창 GUI [노관범, ]

🟥 리스트 GUI [노관범, ]

### 9월 5째주

🟨 프로토타입 yolo 모델 어플리케이션에 적용 [김지섭, 09-26 ~ ]

🟥 Custom DataSet 제작 및 생성 [유현지, 노관범, 09-26 ~ ]

🟨 프로토타입 Yolov5 모델 구현 [유현지, 09-26 ~]

