## yuseungyeol

Java · Spring 백엔드 개발 / IoT / 머신러닝

### Tech Stack

<img src="https://img.shields.io/badge/Java-334155?style=flat-square" alt="Java" /> <img src="https://img.shields.io/badge/Spring_Boot-334155?style=flat-square&logo=springboot&logoColor=6DB33F" alt="Spring Boot" /> <img src="https://img.shields.io/badge/MySQL-334155?style=flat-square&logo=mysql&logoColor=60a5fa" alt="MySQL" /> <img src="https://img.shields.io/badge/TypeScript-334155?style=flat-square&logo=typescript&logoColor=60a5fa" alt="TypeScript" /> <img src="https://img.shields.io/badge/React-334155?style=flat-square&logo=react&logoColor=61DAFB" alt="React" /> <img src="https://img.shields.io/badge/Python-334155?style=flat-square&logo=python&logoColor=facc15" alt="Python" /> <img src="https://img.shields.io/badge/PyTorch-334155?style=flat-square&logo=pytorch&logoColor=EE4C2C" alt="PyTorch" />

### Projects

| 프로젝트 | 설명 · 담당 작업 |
| :--- | :--- |
| **[마디](https://github.com/14thLikeLion5TeamHackathon/BE)** | 시술 후 회복 관리 서비스 · 팀 해커톤<br>날씨·환경 지표 API, OpenWeatherMap 연동<br>Google Calendar 연동, 토큰 갱신과 예외 처리 |
| **[AetherSpace](https://github.com/yuseungyeol-823/iot-web-dashboard)** | IoT 좌석 점유·자동 반납 관제 대시보드<br>React·Spring Boot 기반 SSE 상태 동기화<br>카메라 스트리밍과 센서 연결 끊김 처리 |
| **[Lions PBL Archive](https://github.com/yuseungyeol-823/Lions-PBL-Archive)** | Java·Spring 학습 프로젝트<br>회원·과제 관리 API, JPA·MySQL 연동<br>전역 예외 처리와 Swagger 문서화 |

### Private Projects

#### LG Aimers 9기 — 투구 제구 성공 확률 예측

과거 투구 이력과 경기 상황으로 다음 투구의 제구 성공 확률을 예측하는 팀 프로젝트. 개인 실험 저장소에서 모델 비교와 검증을 진행했습니다.

- LightGBM·CatBoost·PyTorch MLP 모델 비교
- 과거 TrackMan 이력 기반 피처와 잔차 모델 실험
- 시간순 검증과 OOF 예측 기반 확률 보정·앙상블
- 학습·추론 파이프라인 분리, 실험 결과와 모델 채택·기각 근거 정리

#### 월별 예산·소비 내역 관리 백엔드

멋쟁이사자처럼 14기 6팀 프로젝트. 월별 예산 API와 소비 내역 저장 기능을 담당했습니다.

- 월별 총예산 설정·조회 API 구현
- 리포트와 연동할 소비 내역(Transaction) DB 계층 구현
- API 명세에 맞춰 공통 응답 형식과 HTTP 상태 코드 수정
