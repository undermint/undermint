# 📝 감정 분석 AI 일기 웹사이트

## 📌 프로젝트 개요

"**Inside U**"는 사용자가 감정 카드를 작성하고, AI 기반 분석을 통해 감정을 피드백받을 수 있는 웹 애플리케이션입니다.  
감정을 기록하며 자신의 상태를 돌아볼 수 있도록 돕습니다.  

- AI를 활용해 일기를 작성하고 감정을 분석하여 관리할 수 있는 서비스
- 선택한 감정카드와 간단한 상황 입력만으로도 완성되는 AI 일기 작문
- AI 감정 분석 및 인사이트 제공으로 사용자 스스로의 감정 이해와 성찰 지원

---
🚀 **배포 사이트:** [InsideU 서비스 바로가기](https://insideu-e7710.firebaseapp.com)

 **프로젝트 보고서:** [InsideU 감정카드일기.pdf](https://github.com/undermint/undermint/blob/d7cc9c6a0002dff41c7c052447edc704f119c731/Project_EmotionCard_Diary/%E1%84%8B%E1%85%B5%E1%86%AB%E1%84%89%E1%85%A1%E1%84%8B%E1%85%B5%E1%84%83%E1%85%B3%E1%84%8B%E1%85%B2_%E1%84%80%E1%85%A1%E1%86%B7%E1%84%8C%E1%85%A5%E1%86%BC%E1%84%8F%E1%85%A1%E1%84%83%E1%85%B3%E1%84%8B%E1%85%B5%E1%86%AF%E1%84%80%E1%85%B5.pdf)

---

## 🔧 기술 스택  

### 🎨 **UI/UX**  
- **Figma** - UI/UX 디자인  

### 🌐 **Frontend**  
- **Vue CLI 3** - Vue.js 프로젝트 설정 및 개발  
- **Vuetify** - UI 디자인 프레임워크  
- **Axios** - API 통신 라이브러리  

### 🖥️ **Backend**  
- **Node.js** - 서버 개발  
- **Express** - REST API 구축  

### 🤖 **AI & 데이터 처리**  
- **ChatGPT API** - AI 기반 감정 분석 및 자동 일기 생성  

### 🔥 **Firebase (배포 & 백엔드 서비스)**  
- **Firestore Database** - NoSQL 실시간 데이터베이스  
- **Firebase Hosting** - 정적 웹사이트 배포  
- **Firebase Functions** - 서버리스 백엔드 (Node.js 기반 API)  
- **Firebase Storage** - 사용자 업로드 파일 저장  

### 📦 **버전 관리 & 협업**  
- **Git/GitHub** - 소스 코드 관리  
- **Git Fork** - 협업을 위한 브랜치 전략  

### 📑 **문서 및 기획**  
- **Notion** - 프로젝트 관리 및 문서화  
---

## 🎯 주요 기능
✅ 감정 카드 작성 및 저장  
✅ AI 기반 감정 분석 및 피드백 제공  
✅ 일별 감정 변화 확인 (히스토리 기능)  
✅ 카카오톡 로그인 및 공유 기능  
✅ Firebase 인증 및 데이터 저장  

---

## 📸 프로젝트 미리보기


<img src="https://github.com/undermint/undermint/blob/main/Project_EmotionCard_Diary/asset/%E1%84%86%E1%85%A6%E1%84%8B%E1%85%B5%E1%86%AB%E1%84%92%E1%85%AA%E1%84%86%E1%85%A7%E1%86%AB.png" width="500" height="300"/>


<img src="https://github.com/undermint/undermint/blob/main/Project_EmotionCard_Diary/asset/%E1%84%80%E1%85%A1%E1%86%B7%E1%84%8C%E1%85%A5%E1%86%BC%E1%84%8F%E1%85%A1%E1%84%83%E1%85%B3%E1%84%89%E1%85%A5%E1%86%AB%E1%84%90%E1%85%A2%E1%86%A8_02.png" width="500" height="300"/>




### 💡 감정 카드 작성 화면



<img src="https://github.com/undermint/undermint/blob/main/Project_EmotionCard_Diary/asset/%E1%84%8B%E1%85%B5%E1%86%AF%E1%84%80%E1%85%B5%E1%84%8C%E1%85%A1%E1%86%A8%E1%84%89%E1%85%A5%E1%86%BC1.png" width="500" height="300"/>

<img src="https://github.com/undermint/undermint/blob/main/Project_EmotionCard_Diary/asset/%E1%84%8B%E1%85%B5%E1%86%AF%E1%84%80%E1%85%B5%E1%84%8C%E1%85%A1%E1%86%A8%E1%84%89%E1%85%A5%E1%86%BC2.png" width="500" height="300"/>


### 📊 감정 분석 결과

<img src="https://github.com/undermint/undermint/blob/main/Project_EmotionCard_Diary/asset/%E1%84%87%E1%85%AE%E1%86%AB%E1%84%89%E1%85%A5%E1%86%A8%E1%84%80%E1%85%A7%E1%86%AF%E1%84%80%E1%85%AA1.png" width="500" height="300"/>

<img src="https://github.com/undermint/undermint/blob/main/Project_EmotionCard_Diary/asset/%E1%84%87%E1%85%AE%E1%86%AB%E1%84%89%E1%85%A5%E1%86%A8%E1%84%80%E1%85%A7%E1%86%AF%E1%84%80%E1%85%AA2.png" width="500" height="300"/>


### 📈 향후 개선 사항



    친구 기능 
    ● 친구와 연결된 사용자들에게 일기 작성 알림을 제공.
    ● 서로의 기록 상태를 공유하며 긍정적인 동기부여 제공.

    하루 일과 자동 기록
      ● 위치 정보, 캘린더 이벤트, 운동 기록 등 데이터를
      활용해 하루 일과 자동 요약.
      ● 사용자가 추가적인 정보를 입력하지 않아도 간편하게
      하루를 돌아볼 수 있음.

