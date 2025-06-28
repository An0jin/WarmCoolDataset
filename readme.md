# 🎨 퍼스널 컬러 분석 시스템

## 📌 프로젝트 소개
이 프로젝트는 YOLOv11-CLS 모델을 기반으로 사용자의 얼굴 이미지에서 퍼스널 컬러(웜톤/쿨톤)를 자동으로 분류하는 AI 기반 시스템입니다. Unity AR 기능과 실시간 커뮤니티 기능을 통합하여 사용자 친화적인 서비스를 제공합니다.

---


## 🏗 시스템 구성

프로젝트는 다음 다섯 개의 주요 리포지토리로 구성되어 있습니다:

### 1. [WarmCoolYolo](https://github.com/An0jin/WarmCoolYolo)

- YOLO12 기반 퍼스널 컬러 분류 모델
- Roboflow를 통한 데이터셋 관리
- 모델 학습 및 평가 파이프라인

### 2. [WarmCoolFastapi](https://github.com/An0jin/WarmCoolFastapi)

- FastAPI 기반 백엔드 서버
- YOLOv12 모델 서빙
- RESTful API 엔드포인트 제공
- Postgresql 데이터베이스 연동

### 3. [WarmCoolUnity](https://github.com/An0jin/WarmCoolUnity)

- Unity 기반 AR 애플리케이션
- ARFoundation을 통한 얼굴 인식
- 가상 메이크업 적용
- Photon 기반 실시간 채팅

### 4. [WarmCoolSQL](https://github.com/An0jin/WarmCoolSQL)

- 채팅 정보 관리
- 유저 정보 관리
- 퍼스널 컬러 해설

### 5. [WarmCoolDataset](https://github.com/An0jin/WarmCoolDataset)

- roboflow를 활용한 데이터 수집
- github를 활용한 데이터 수집
- open CV를 활용한 데이터 증강

### 6. [WarmCoolVim](https://github.com/An0jin/WarmCoolVim)

- vim으로 작성한 쉘 스크립트
- 쉘 스크립트를 활용한 도커 조작
- 쉘 스크립트를 활용한 웹호스팅

---



## 🛠 사용 기술
### 1학기
- ![Roboflow](https://img.shields.io/badge/-roboflow-6706CE?style=flat&logo=roboflow&logoColor=white)
- ![github](https://img.shields.io/badge/-github-000000?style=flat&logo=github&logoColor=white)

### 2학기
- ![Roboflow](https://img.shields.io/badge/-roboflow-6706CE?style=flat&logo=roboflow&logoColor=white)
- ![github](https://img.shields.io/badge/-github-000000?style=flat&logo=github&logoColor=white)
- ![open cv](https://img.shields.io/badge/-open%20cv-5C3EE8?style=flat&logo=opencv&logoColor=white)