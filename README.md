![header](https://capsule-render.vercel.app/api?type=waving&color=0:1e3a5f,100:3b82f6&height=180&section=header&text=박정호&fontSize=48&fontColor=ffffff&desc=Backend%20Developer%20·%20Team%20Lead&descAlignY=72&animation=fadeIn)

<div align="center">

**명세에서 출발해 이슈·리뷰·CI로 팀 프로젝트를 이끌어 본 백엔드 개발자 박정호입니다.**

<a href="mailto:parkjungho20@gmail.com"><img src="https://img.shields.io/badge/Email-parkjungho20@gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white"/></a>
<a href="TODO_노션_URL"><img src="https://img.shields.io/badge/Notion-Portfolio-000000?style=flat-square&logo=notion&logoColor=white"/></a>
<a href="TODO_이력서_URL"><img src="https://img.shields.io/badge/Resume-이력서-4B5563?style=flat-square&logo=readdotcv&logoColor=white"/></a>

</div>

---

## 🚀 대표 프로젝트 — white-eyes

> 드론·CCTV처럼 높은 곳에서 찍은 영상에서 사람 수와 이동을 세고, 구역별 혼잡도와 이용 패턴을 통계로 보여 주는 서비스

```mermaid
flowchart LR
    B[브라우저] --> N[nginx]
    N --> U[사용자 앱<br/>Spring Boot]
    N --> A[관리자 앱<br/>Spring Boot]
    A <-->|내부 API| F[분석 서버<br/>Flask · YOLOv8]
    U --> D[(MySQL)]
    A --> D
```

**Stack**
<img src="https://img.shields.io/badge/Java_17-007396?style=flat-square&logo=openjdk&logoColor=white"/>
<img src="https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white"/>
<img src="https://img.shields.io/badge/Spring_Security-6DB33F?style=flat-square&logo=springsecurity&logoColor=white"/>
<img src="https://img.shields.io/badge/JPA-59666C?style=flat-square&logo=hibernate&logoColor=white"/>
<img src="https://img.shields.io/badge/Flyway-CC0200?style=flat-square&logo=flyway&logoColor=white"/>
<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white"/>
<img src="https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white"/>
<img src="https://img.shields.io/badge/YOLOv8-111F68?style=flat-square&logo=ultralytics&logoColor=white"/>
<img src="https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white"/>
<img src="https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white"/>
<img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white"/>
<img src="https://img.shields.io/badge/nginx-009639?style=flat-square&logo=nginx&logoColor=white"/>
<img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white"/>

**My Role — PM · 리뷰어 · 백엔드**
- **명세 → 이슈**: 요구·기능·API·테이블 명세를 md 문서 하나로 모으고, 기능 하나를 이슈 하나로 쪼개 프로젝트 보드에서 3단계로 일정 관리
- **코드 리뷰**: PR 리뷰 **271건**, 브랜치 룰셋(PR 필수·승인·코드 오너·CI `build` 통과)을 설계해 dev/main 품질 관리
- **결정 기록(ADR) 18건**: 혼잡 3단계 기준, 탐지 모델 교체(YOLO-CROWD → VisDrone YOLOv8m + PointTracker), 계정 테이블 분리 등 결정 이유를 문서로 남김
- **배포 구성**: 전체 서비스를 docker compose 한 번으로 띄우는 로컬 실행 환경, nginx 설정, 앱별 DB 계정

| 지난 1년 활동 | 커밋 | PR | 리뷰 | 이슈 |
|:-:|:-:|:-:|:-:|:-:|
| 2025.11 ~ 2026.11 | 338 | 109 | 271 | 149 |

🔗 [docs](https://github.com/white-eyes1/white-eyes-docs) · [spring](https://github.com/white-eyes1/white-eyes-spring) · [flask](https://github.com/white-eyes1/white-eyes-flask) · [deploy](https://github.com/white-eyes1/white-eyes-deploy)

---

## 🧩 그 밖의 프로젝트

| 프로젝트 | 한 줄 설명 | 스택 |
|---|---|---|
| [obsidian-shield](https://github.com/Kanabig/obsidian-shield) | TODO | Python · Flask · OpenCV · YOLO · InsightFace |
| [spring-boot-calendar-admin](https://github.com/Kanabig/spring-boot-calendar-admin) | TODO | Java · Spring Boot |
| [community-board-toy](https://github.com/Kanabig/community-board-toy) | TODO | Java |

---

## 🛠 Tech Stack

<div align="center">

<img src="https://img.shields.io/badge/Java-007396?style=flat-square&logo=openjdk&logoColor=white"/>
<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white"/>
<img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black"/>
<br/>
<img src="https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white"/>
<img src="https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white"/>
<img src="https://img.shields.io/badge/Thymeleaf-005F0F?style=flat-square&logo=thymeleaf&logoColor=white"/>
<br/>
<img src="https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white"/>
<img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white"/>
<img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white"/>
<img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white"/>

</div>
