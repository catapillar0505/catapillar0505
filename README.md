<div align="center">

# 안녕하세요, 김진아입니다 👋

### Backend & Cloud Infrastructure Engineer

[![Email](https://img.shields.io/badge/Email-twrp3301@gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:twrp3301@gmail.com)
[![Notion Portfolio](https://img.shields.io/badge/Portfolio-Notion-000000?style=flat-square&logo=notion&logoColor=white)](https://www.notion.so/jina8/329ec63d769480eb942fdec9ed6c399e)

</div>

---

## 🏆 수상 이력

| 수상 | 주최 | 프로젝트 | 날짜 |
|---|---|---|---|
| 멋쟁이사자처럼 백엔드 15기 파이널 **🥇 최우수 (1위)** | 멋쟁이사자처럼 | [MYCE](https://github.com/catapillar0505/myce-server) | 2025.08 |
| Programming GURU 해커톤 Android 부문 **🥇 대상** | 서울여자대학교 | [Mechuragi](https://github.com/catapillar0505/mechuragi_main_server) | 2024.02 |
| 배리어프리 앱 개발 컨테스트 **우수상** | 현대오토에버 · (사)그린라이트 | [Stainless](https://github.com/catapillar0505/Stainless) | 2024.02 |
| 학생창업 아이디어경진대회 **우수상** | 한국창업협회 · 요즈마그룹코리아 | Recordy | 2023.11 |
| 한이음 ICT멘토링 공모전 **입선** | 한국정보산업연합회 | Keep Work | 2023.12 |
| 소프트웨어융합학과 졸업 프로젝트 **은상** | 서울여자대학교 | Stainless | 2023.02 |
| Programming GURU 해커톤 Python 부문 **장려상** | 서울여자대학교 | — | 2023.02 |
| 창업 아이디어 경진대회 **대상** | 서울여자대학교 산학협력단 | Recordy | 2022.10 |

---

## 🚀 주요 프로젝트

### 🔭 Micro-Lens — 시력보조 AI 비전 플랫폼 (1인 프로젝트)

> 일상 속 미세한 부분까지, 대신 확인해주는 시력보조 파트너 · 📹 [시연 영상](https://youtu.be/7jnekg9lZeo)

- **kubeadm으로 Kubernetes 클러스터 직접 구축** — Terraform·Ansible·Kustomize·ArgoCD로 GitOps 파이프라인까지 전 구간 IaC
- YOLOv5 → YOLOv12 전환 + 데이터셋 개선(배경 이미지 10% 추가 등)으로 **mAP50 0.55 → 0.8**
- 운영 중 GPU 사용률 **2.5%를 직접 관측** → g4dn(GPU) → t3(CPU) 전환, 절감 비용으로 **replicas 2 + podAntiAffinity HA** 확보

[![infra](https://img.shields.io/badge/GitHub-microlens--infra-181717?style=flat-square&logo=github)](https://github.com/MICRO-LENS/microlens-infra)
[![ai-api](https://img.shields.io/badge/GitHub-microlens--ai--api-181717?style=flat-square&logo=github)](https://github.com/MICRO-LENS/microlens-ai-api)
[![client](https://img.shields.io/badge/GitHub-microlens--client-181717?style=flat-square&logo=github)](https://github.com/MICRO-LENS/microlens-client)

### 🎟️ MYCE — 박람회 생애주기 관리 플랫폼 <sub>🏆 멋사 백엔드 15기 파이널 최우수 (1위)</sub>

> 박람회 개최부터 예약·결제·정산까지 원스톱 박람회 생애주기 관리 플랫폼

- **박람회 관리자 도메인을 백엔드부터 프론트까지 엔드투엔드 전담** (머지 PR 55개 — server 20 + client 35)
- 대시보드 통계의 데이터 정합성 문제 해결 — 기준 테이블 통일 + **Redis 캐시 키 버전 관리** 체계 도입
- D-1·행사 1시간 전 **알림 스케줄러** 구현, 박람회 단위 그룹핑으로 중복 알림 제거 / QR 도메인 SRP 리팩토링

[![server](https://img.shields.io/badge/GitHub-myce--server-181717?style=flat-square&logo=github)](https://github.com/catapillar0505/myce-server)
[![client](https://img.shields.io/badge/GitHub-myce--client-181717?style=flat-square&logo=github)](https://github.com/catapillar0505/myce-client)

### 🐦 메추라기 — Claude AI 메뉴 추천 커뮤니티 <sub>🏆 Programming GURU 해커톤 대상</sub>

> "오늘 뭐먹지?" 고민을 줄여주는 AI 추천 + 투표 커뮤니티 · 📹 [시연 영상](https://youtube.com/shorts/QZbuvk-MRn8?feature=share)

- 팀 전체 머지 PR 177개 중 **125개(71%) 작성** — 백엔드·프론트·AI·인프라 전 저장소 기여, **인프라는 단독 설계·구축(기여 100%)**
- **k6 부하 테스트로 게이트웨이 구조 검증** — OpenResty + Lua JWT 직행 경로 채택으로 처리량 **+32%**, p95 **-45%**
- 알림 시스템을 DB 폴링에서 **Redis Keyspace Notifications + SSE**로 전환 — 최대 60초 지연 → 실시간, 하이브리드 fallback 설계

[![main](https://img.shields.io/badge/GitHub-mechuragi__main__server-181717?style=flat-square&logo=github)](https://github.com/catapillar0505/mechuragi_main_server)
[![ai](https://img.shields.io/badge/GitHub-mechuragi__ai__server-181717?style=flat-square&logo=github)](https://github.com/catapillar0505/mechuragi_ai_server)
[![client](https://img.shields.io/badge/GitHub-mechuragi__client-181717?style=flat-square&logo=github)](https://github.com/catapillar0505/mechuragi_client)
[![infra](https://img.shields.io/badge/GitHub-mechuragi__infra-181717?style=flat-square&logo=github)](https://github.com/catapillar0505/mechuragi_infra)

### 👕 Stainless — 시각장애인용 옷 얼룩 탐지 앱 <sub>🏆 배리어프리 앱 개발 컨테스트 우수상</sub>

> 보이지 않아도, 깨끗한 옷을 입을 권리 · 📹 [시연 영상](https://youtube.com/shorts/isyrkpcRVUI?feature=share)

- 시각장애인 인터뷰로 니즈를 검증하고, **YOLOv5 + TensorFlow Lite 온디바이스 실시간 탐지** 구현 (Camera2 API, TTS·진동 안내)
- 얼룩 데이터셋 직접 제작 → 모델 학습 → TFLite 변환 → 카메라 파이프라인 연결까지 AI 전 과정 수행
- 심사평: *"출품작 중 가장 실체적이고 구체적인 아이디어"* — 이후 Micro-Lens로 발전

[![GitHub](https://img.shields.io/badge/GitHub-Stainless-181717?style=flat-square&logo=github)](https://github.com/catapillar0505/Stainless)

---

## 🛠 기술 스택

**Backend**

![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![Spring Security](https://img.shields.io/badge/Spring_Security-6DB33F?style=flat-square&logo=springsecurity&logoColor=white)
![Spring Data JPA](https://img.shields.io/badge/Spring_Data_JPA-6DB33F?style=flat-square&logo=spring&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![JWT](https://img.shields.io/badge/JWT-000000?style=flat-square&logo=jsonwebtokens&logoColor=white)
![SSE](https://img.shields.io/badge/SSE-E34F26?style=flat-square&logo=html5&logoColor=white)

**Database / Cache**

![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)

**AI Serving**

![AWS Bedrock](https://img.shields.io/badge/AWS_Bedrock-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white)
![YOLO](https://img.shields.io/badge/YOLO-00FFFF?style=flat-square&logoColor=black)
![ONNX Runtime](https://img.shields.io/badge/ONNX_Runtime-005CED?style=flat-square&logo=onnx&logoColor=white)

**Cloud / Infra**

![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-844FBA?style=flat-square&logo=terraform&logoColor=white)
![Ansible](https://img.shields.io/badge/Ansible-EE0000?style=flat-square&logo=ansible&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![ArgoCD](https://img.shields.io/badge/ArgoCD-EF7B4D?style=flat-square&logo=argo&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white)

**CI/CD**

![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![Jenkins](https://img.shields.io/badge/Jenkins-D24939?style=flat-square&logo=jenkins&logoColor=white)
![k6](https://img.shields.io/badge/k6-7D64FF?style=flat-square&logo=k6&logoColor=white)

---

## ✏️ 학력 · 교육 · 자격증

- **서울여자대학교** 소프트웨어융합학과 (2020.03 ~ 2026.02)
- **멋쟁이사자처럼** — JAVA 백엔드 15기 (2025.02 ~ 2025.08)
- **새싹 청년취업사관학교** — AWS와 AI를 활용한 MSA 웹서비스 개발 (2026.05 ~ 2026.11)
- **정보처리기사** (2025.08.13)

---

<div align="center">

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=catapillar0505&show_icons=true&theme=default&hide_border=true&count_private=true)

</div>
