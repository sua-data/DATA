# DATA - 경제 뉴스 기반 이슈 분석 서비스

경제 뉴스 데이터를 수집하고 분석하여  
일별 주요 키워드, 이슈 흐름, 감성 분포, 관련 뉴스 요약을 제공하는 데이터 분석 프로젝트입니다.

## 1. 프로젝트 개요

본 프로젝트는 네이버 경제 뉴스와 RSS 기반 경제 뉴스를 수집한 뒤,  
키워드 분석, 감성 분석, 요약, 유사 뉴스 묶음 처리를 통해  
사용자가 특정 경제 이슈의 흐름을 쉽게 파악할 수 있도록 구성한 서비스입니다.

주요 목표는 단순 뉴스 목록 제공이 아니라,  
뉴스 데이터를 기반으로 이슈 단위의 분석 결과를 제공하는 것입니다.

## 2. 주요 기능

- 경제 뉴스 데이터 수집
- 뉴스 본문 전처리
- 키워드 추출
- 감성 분석
- 유사 뉴스 그룹화
- 이슈별 요약 생성
- Elasticsearch 기반 검색
- 일별 주요 이슈 조회
- 사용자 화면을 통한 뉴스 분석 결과 제공

## 3. 사용 기술

### Backend
- Python
- FastAPI
- MariaDB
- Elasticsearch

### Data / AI
- pandas
- scikit-learn
- FAISS
- KR-FinBERT-SC
- TextRank
- TF-IDF
- kiwipiepy

### Frontend
- HTML
- CSS
- JavaScript
- jQuery
- axios

### Tools
- Git
- GitHub
- VSCode
- PyCharm

## 4. 프로젝트 구조

```bash
DATA/
├── api/                 # FastAPI 관련 코드
├── batch/               # 뉴스 수집 및 분석 배치 코드
├── config/              # 설정 파일
├── model/               # 분석 모델 관련 코드
├── static/              # 정적 파일
├── templates/           # 화면 템플릿
├── util/                # DB, ES 등 공통 유틸
├── view/                # 프론트 화면 관련 파일
├── requirements.txt
├── .gitignore
└── README.md

## 📌 Development Log

프로젝트 진행 과정은 아래 문서에서 확인할 수 있습니다.

👉 [개발 로그 전체 보기](./docs/devlog)