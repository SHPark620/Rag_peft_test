##  LLaMA3 기반 RAG 챗봇 (로컬 환경)

###  개요
이 프로젝트는 **LLaMA3** 모델과 **RAG (Retrieval-Augmented Generation)** 구조를 활용하여,  
외부 API 없이 **개인 로컬 환경에서 실행되는 경량 챗봇**을 구현한 예제입니다. 

기초 NLP 구조(RNN, LSTM, Transformer 등) 학습 이후, LLM 실습을 위해 개발된 프로젝트입니다.

---

###  사용 기술

- **LLM 모델**: LLaMA3 (Ollama로 실행)
- **UI 프레임워크**: Streamlit
- **문서 검색**: RAG 기반 검색
- **구성 방식**: 외부 API 없이 Local PC에서만 동작

---

###  주요 파일

- `chatbot.py` : 메인 실행 코드
- `requirements.txt` : 의존성 패키지 목록

---

###  특징

- 외부 API 없이 **로컬에서 완전 실행 가능**
- **LangChain + Streamlit + Ollama**를 이용한 통합 구조
- 사용자 문서를 기반으로 **RAG 방식 응답 생성**

---

>  이 챗봇은 교육 목적과 개인 LLM 환경 구축 경험을 위한 실습 프로젝트입니다.
