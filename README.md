# Dacon_hackathon
multicultural helper_in Dacon project

# Multicultural helper

Multicultural helper는 한국에 처음 오는 외국인을 위해 기본 정보, 생활 적응, 문화 차이 등 실질적인 질문에 답변하는 AI 기반 Q&A 서비스입니다.  
사전에 수집한 문화적응 Q&A 데이터셋을 기반으로 동작하며, 실제 생활에 필요한 짧고 명확한 질문들을 중심으로 학습됩니다.    
또한, 서울 지역 시설 지도 정보를 제공하여 서울 생활에 도움을 줍니다.  


## 프로젝트 기간

개발 기간: 2025.11.01 ~ 2025.11.18 (해커톤 제출용)

## 주요 기능

1. 카테고리 기반 Q&A
   
    * 비자, 의료, 교육, 일자리, 보험 등 주요 분야별로 분류된 질문·답변 제공
  
    * 사용자가 질문을 입력하면 즉시 AI가 답변
  
    * 서울외국인포털 FAQ를 기반으로 정확한 정보 응답
  
    * UI 구조는 Manus 자동 생성 템플릿 기반
  

2. 노코딩 툴을 이용한 웹 구현
  
    * 카테고리 카드 자동 생성, 챗봇 스타일 질문 입력창
  
    * 별도 디자인/레이아웃 코드 없이 Manus가 자동 배치
  
    * 백엔드 개발 없음, DB 구축 없음
  
    * 빠른 MVP 제작에 적합

3. 지역 정보 지도
  
    * 서울 지역 내 외국인이 자주 이용하는 시설을 지도 상에 표시  
    (대형 병원, 외국인 지원센터, 은행, 약국, 편의점 등)
  
    * 카테고리별 필터링 버튼 제공
  
    * 좌측에는 시설 리스트, 우측에는 지도 표시

## 기술 스택

* Web builder: Manus(No-Code Website Generator)  

* AI Answering: OpenAI API (Manus 내장)
  
* Data source: 서울 외국인 포털 FAQ
  
* Mapping: Manus 제공 지도 컴포넌트 (Google Maps 기반)
  
* Hosting: Manus 자동 호스팅  

## 프로젝트 구조

multicultural helper/    
├── Home Page                 # 카테고리 선택 메인 화면  
├── Visa Page                 # 비자 관련 Q&A  
├── Insurance Page            # 보험·건강보험 Q&A  
├── Job Page                  # 취업 정보 Q&A   
├── Education Page            # 교육·학교 정보 Q&A
├── Medical Page              # 의료 관련 Q&A  
├── Local Information Map     # 지도 기반 지역 시설 정보  
└── Knowledge Base            # 서울외국인포털 FAQ 기반 데이터  

## MVP 실행 방법

1) Manus에서 실행
  
    * Manus 프로젝트 URL 접속
  
    * 카테고리 선택 → Q&A 페이지 진입
  
    * 지도 페이지에서 시설 검색 가능

2) 로컬 실행 없음

    노코드 기반이므로 별도의 설치/빌드 과정 없음.


## 방법론 문서 설명

* Manus 기반 No-Code MVP 제작 절차
  
* 서울외국인포털 FAQ → Knowledge Base 구축 과정
  
* Prompt-to-App 방식
  
* 지도 기능 생성 방식 및 한계
  
* 향후 개선 방향

## 팀원 소개

| 이름  | GitHub ID      | 역할                |
| --- | -------------- | ----------------- |
| 오영서 | YoungSeo-coder | 팀장, 데이터 구축 및 모델 구조 설계 |
| 신유민 | uminshin        | 프론트엔드 및 API 구축    |

---
