---
layout: home
title: 김석현 (Seokhyeon Kim)
---

# 김석현 (Seokhyeon Kim)
**AI Engineer — Knowledge Graph & AIOps**

금융 도메인 지식그래프와 LLM 서빙 인프라를 기획부터 운영까지 직접 설계·구축하는 AI Engineer입니다.

---

## 자기소개

저는 16세에 대학에 입학했습니다. 어릴 때부터 컴퓨터에 깊은 흥미를 느껴 보다 빠르고 주도적인 학습을 위해 중·고등학교 대신 검정고시를 선택했고, 곧바로 대학 입시를 준비해 Beijing Institute of Technology에 입학했습니다.

대학 입학 후에도 소프트웨어로 문제를 해결하는 과정에 몰두했습니다. 다양한 공모전과 해커톤에 개발자로 참여했고, 소프트웨어 마에스트로, KDT, 백엔드 인턴십 등을 통해 기술로 문제를 정의하고 해결하는 경험을 쌓아왔습니다.

현재는 미래에셋증권 AI솔루션본부에서 AIOps 플랫폼 및 AI 서비스 파이프라인 개발을 담당하고 있으며, 최근에는 증권사 도메인에 특화된 Knowledge Graph DB 구축을 맡고 있습니다. 증권사 상품, PB 가이드, WM 업무 가이드를 대상으로 온톨로지와 지식 그래프를 설계·구현해, 기존 벡터 검색 기반 RAG로는 대응하기 어려웠던 연관관계 중심 질의와 구조적 질문을 처리할 수 있는 검색 구조를 구축했습니다.

이 과정에서 정형·비정형 데이터의 파싱과 청킹 전략 수립, 지식 그래프 데이터 추출·적재, 그래프 기반 검색까지 전 과정을 직접 기획·개발하며, 단순 검색을 넘어 Agent가 업무 지식을 실제 업무 프로세스에 활용할 수 있는 기반을 마련했습니다.

앞으로는 도메인 지식을 이해하고 실행할 수 있는 AI 서비스 파이프라인을 설계·구축하는 AI Engineer로 성장하고자 합니다.

---

## 경력

### 미래에셋증권 — AI솔루션본부 Data플랫폼팀, AI Engineer
**2023.07 – 현재**

**Knowledge Graph DB with Ontology**
- 증권사 상품, PB 가이드, WM 업무 가이드를 대상으로 온톨로지·지식그래프 설계, 정형·비정형 데이터 KG 생성 파이프라인 기획·개발
- LLM 기반 비정형 데이터 정보 추출, 문서 유형별 파이프라인 분리 구현
- 벡터 검색 기반 RAG의 한계(연관관계·구조적 질의 미대응)를 KG 기반 RAG로 확장해 해결
- 사내 업무 프로세스(WM, PB 업무)를 온톨로지로 구현해 Agent가 업무 효율화를 수행할 수 있는 기반 마련
- Hallucination 문제: 도메인 이해가 없는 LLM을 비정형 데이터에 적용하며 관계 오류·신뢰도 저하 발생 → VL 모델 기반 임베딩, Reranker 적용, 금융 도메인 특화 LLM·프롬프트 설계로 개선 방향 제시
- 검색 속도 문제: 그래프 탐색 특성상 벡터 검색·RDB 쿼리 대비 응답 속도 저하 → FAQ·문서·그래프 기반 예상 질의-응답 쌍을 사전 생성해 별도 그래프로 저장하는 **Semantic Caching** 전략 설계

**AIOps 플랫폼 & LLM 최적화 서빙**
- EKS/ECR 기반 Kubernetes 서버 배포, CloudFront 기반 프론트엔드 정적 배포, GitHub Actions 배포 자동화
- vLLM, TensorRT-LLM 등 서빙 프레임워크 사내 도입, 폐쇄 온프레미스 환경 LLM 서빙 및 엔드포인트 제공
- 사내 데이터 분석 환경 및 전사 LLM 서빙 인프라 구축으로 안정적인 AI 서비스 운영 지원
- 수상: 정보통신산업진흥원 원장상

---

## 학위 논문

**Design and Implementation of a Blockchain-based Multi-UAV Mission Management System**
Beijing Institute of Technology — 학사 졸업논문 · 2023.02 – 2023.06

- HLF(Hyperledger Fabric) 기반 폐쇄형 블록체인 네트워크 설계, 체인코드·합의 알고리즘 개발
- Go 기반 트랜잭션 처리 REST 서버 개발
- 블록체인 네트워크 트랜잭션 처리 및 실시간 관제 대시보드 설계·개발
- Django 기반 UAV 관리 시스템 및 FANET 비동기 task 처리 엔드포인트 개발

---

## 주요 프로젝트 / 수상

### 나만의 제주어 이름 생성기 "제주일름" — 9oormthon(구름톤) 1기
**2022.08.22 – 2022.08.26**
- 사라져가는 제주어 활성화를 목표로, 이름의 뜻을 담아 제주어 이름을 생성해주는 웹 콘텐츠 제작
- Flask 백엔드 개발, PyTorch 인공지능 모델 서빙
- 수상: 제1회 구름톤 — 카카오 대표상 대상

### 독거노인을 위한 반려로봇 "백구" — 소프트웨어 마에스트로
**2020.06 – 2020.11**
- 혼자 거주하는 어르신의 생활 패턴을 케어하고 위급 상황을 감지하는 반려로봇 서비스
- Flask 백엔드, AWS/IoT 인프라 구축, NLP 기반 말벗 서비스 설계, 라즈베리파이 기반 로봇 본체 및 3D 모델링
- 특허: 낙상 감지 알고리즘을 이용한 독거노인 케어 로봇 (10-2020-0152831) 등 2건 출원
- SW 저작권: 보호자용 앱, 스마트 반려로봇, 관제 웹페이지 등 3건 등록
- 수상: ICT이노베이션 제주 인공지능&블록체인 아이디어 공모전 대상 입상, 왕중왕전(전국 인공지능 아이디어 공모전) 출전
- 키즈카페 (주)꼬마빌리지와 MOU 체결

---

## Skills

- **Backend**: Flask, Django, Go
- **AI/LLM**: PyTorch, vLLM, TensorRT-LLM, Knowledge Graph/Ontology 설계, RAG
- **Infra/DevOps**: AWS(EKS, ECR, CloudFront), Kubernetes, GitHub Actions
- **Blockchain**: Hyperledger Fabric

---

[LinkedIn](https://www.linkedin.com/in/seokhyeon-kim/) · [GitHub](https://github.com/9r3at)
