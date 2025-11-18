# Dacon_hackathon
multicultural helper_in Dacon project

# multicultural helper

multicultural helper는 한국에 처음 오는 외국인을 위해 기본 정보, 생활 적응, 문화 차이 등 실질적인 질문에 답변하는 AI 기반 Q&A 서비스입니다.
사전에 수집한 문화적응 Q&A 데이터셋을 기반으로 동작하며, 실제 생활에 필요한 짧고 명확한 질문들을 중심으로 학습됩니다.

## 프로젝트 기간

개발 기간: 2025.11.01 ~ 2025.11.18 (해커톤 제출용)

## 주요 기능

**구현 완료**

* 외국인 생활 Q&A 데이터 수집 및 정제(약 150개 핵심 문항)
* 문화적응 분야 특화 Q&A 모델 파인튜닝 준비
* 실질적·단문 중심 질문만 선별된 데이터셋 구성
* 기본 Q&A 에이전트 구조 설계

**구현 중인 기능**

* 파인튜닝 모델 학습
* API 연동형 챗 UI 구현
* 사용자 질문 전처리(언어 감지, 질문 축약)
* 추가 문화 분야 데이터 확장(대중교통, 병원, 관공서 등)

## 기술 스택

Language: Python
Framework: FastAPI (예정)
Model: LLM Fine-tuning 기반(예정)
Data: 사용자 제작 문화적응 Q&A 데이터셋
Tools: Colab, HuggingFace, GitHub
Etc: JSON/CSV 기반 데이터 파이프라인

## 프로젝트 구조

cultureassist/
├── data/
│   ├── raw/                          # 원본 Q&A 데이터
│   ├── processed/                    # 정제된 단문 중심 Q&A
│   └── schema/                       # 데이터 형식 정의
├── model/
│   ├── preprocessing/                # 질문 정제 및 언어 감지
│   ├── finetune/                     # 파인튜닝 스크립트
│   └── inference/                    # 모델 추론 코드
├── api/
│   └── main.py                       # FastAPI 서버 (예정)
├── utils/
│   └── formatter.py                  # 질문/답변 포맷팅
├── README.md
└── requirements.txt

## 실행 방법

### 데이터 확인

data/processed 폴더 내 JSON 파일 확인
문화적응 단문 Q&A 150문항 포함

### 모델 실행(예정)

Colab에서 파인튜닝 스크립트 실행
환경 세팅 후 inference/main.py로 추론 가능

## 팀원 소개

| 이름  | GitHub ID      | 역할                |
| --- | -------------- | ----------------- |
| 오영서 | YoungSeo-coder | 팀장, 데이터 구축 및 모델 구조 설계 |
| 신유민 | uminshin        | 프론트엔드 및 API 구축    |

---
