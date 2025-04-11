# 🎨 퍼스널 컬러 분석 시스템

## 📌 프로젝트 소개
이 프로젝트는 YOLOv11-CLS 모델을 기반으로 사용자의 얼굴 이미지에서 퍼스널 컬러(웜톤/쿨톤)를 자동으로 분류하는 AI 기반 시스템입니다. Unity AR 기능과 실시간 커뮤니티 기능을 통합하여 사용자 친화적인 서비스를 제공합니다.

---

## 🏗 시스템 구성
프로젝트는 다음 5개의 주요 리포지토리로 구성되어 있습니다:

---

### 1. WarmCoolDataset
- Roboflow를 활용한 데이터 수집 및 관리
- GitHub를 통한 추가 데이터 수집
- 데이터 전처리 및 정제 파이프라인

### 2. WarmCoolYOLO
- YOLOv11-CLS 기반 퍼스널 컬러 분류 모델
- Ultralytics 라이브러리 활용
- 모델 학습 및 성능 평가 시스템

### 3. WarmCoolFastAPI
- FastAPI 기반 백엔드 서버
- AI 모델 서빙 시스템
- RESTful API 엔드포인트 제공

### 4. WarmCoolUnity
- Unity 기반 AR 애플리케이션
- ARFoundation을 통한 얼굴 인식
- 가상 메이크업 시뮬레이션
- Photon 기반 실시간 커뮤니티 기능

### 5. WarmCoolSQL
- 사용자 정보 관리 데이터베이스
- 채팅 기록 저장 및 관리
- 퍼스널 컬러 분석 결과 저장

---


## 🛠 기술 스택
- **AI/ML**: YOLOv11-CLS, Ultralytics
- **백엔드**: FastAPI, MySQL
- **프론트엔드**: Unity, ARFoundation
- **데이터 관리**: Roboflow, Python
- **네트워킹**: Photon PUN2
- **개발 도구**: Jupyter Notebook