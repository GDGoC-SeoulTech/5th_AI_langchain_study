# LangChain Study

## 1.  스터디원

### 1팀

<table align="center">
<tr align="center">
  <td width="200"><img src="https://avatars.githubusercontent.com/orieasy1" width="90"></td>
  <td width="200"><img src="https://avatars.githubusercontent.com/no-glass-otacku" width="90"></td>
  <td width="200"><img src="https://avatars.githubusercontent.com/kimm00" width="90"></td>
  <td width="200"><img src="https://avatars.githubusercontent.com/shinh09" width="90"></td>
  <td width="200"><img src="https://avatars.githubusercontent.com/ChooJG" width="90"></td>
  <td width="200"><img src="https://avatars.githubusercontent.com/" width="90"></td>
</tr>

<tr align="center">
  <td><a href="https://github.com/orieasy1">지원</a></td>
  <td><a href="https://github.com/no-glass-otacku">가영</a></td>
  <td><a href="https://github.com/kimm00">도이</a></td>
  <td><a href="https://github.com/shinh09">신형</a></td>
  <td><a href="https://github.com/ChooJG">제근</a></td>
  <td><a href="https://github.com/">준수</a></td>
</tr>
</table>

### 2팀

<table align="center">
<tr align="center">
  <td width="200"><img src="https://avatars.githubusercontent.com/mmuhunn" width="90"></td>
  <td width="200"><img src="https://avatars.githubusercontent.com/itisyijy" width="90"></td>
  <td width="200"><img src="https://avatars.githubusercontent.com/" width="90"></td>
  <td width="200"><img src="https://avatars.githubusercontent.com/hajinki" width="90"></td>
  <td width="200"><img src="https://avatars.githubusercontent.com/dodhdo23" width="90"></td>
  <td width="200"><img src="https://avatars.githubusercontent.com/yuyoung924" width="90"></td>
  <td width="250"><img src="https://avatars.githubusercontent.com/MelonChicken" width="90"></td>
</tr>

<tr align="center">
  <td><a href="https://github.com/mmuhunnm">대훈</a></td>
  <td><a href="https://github.com/itisyijy">정윤</a></td>
  <td><a href="https://github.com/">은아</a></td>
  <td><a href="https://github.com/hajinki">하진</a></td>
  <td><a href="https://github.com/dodhdo23">도현</a></td>
  <td><a href="https://github.com/yuyoung924">유영</a></td>
  <td><a href="https://github.com/MelonChicken">준우</a></td>
</tr>
</table>

<br>

##  2. 스터디 내용

### 사용자료

* [랭체인LangChain 노트 책](https://wikidocs.net/book/14314)
* [랭체인 노트 깃허브](https://github.com/teddylee777/langchain-kr)

### 주차별 커리큘럼

| 주차 | 챕터 | 범위 | 비고 |
| --- | --- | --- | --- |
| 1주차 | Ch01 | LangChain 시작하기 | 설치, API 키, LangSmith, Runnable |
| 2주차 | Ch02 | 프롬프트 | PromptTemplate, Few-shot, CoT 등 |
| 3주차 | Ch03 | 출력 파서 | Pydantic, JSON, StrOutput 등 |
| 4주차 | Ch04 | 모델 | LLM, ChatModel, Streaming |
| 5주차 | Ch05 | 메모리 | ConversationBuffer, Summary, TokenBuffer |
| 6주차 | Ch06 | 문서 로더 | 다양한 Loader (PDF, Web, DB 등) |
| 7주차 | Ch07 | 텍스트 분할 | RecursiveCharacterTextSplitter 등 |
| 8주차 | Ch08 | 임베딩 | OpenAI, HuggingFace, SentenceTransformer |
| 9주차 | Ch09 | 벡터저장소 | FAISS, Chroma, Milvus |
| 10주차 | Ch10 | 검색기 | kNN, BM25, Hybrid 등 |
| 11주차 | Ch11 | 리랭커 | Cross-Encoder, Ranker, 평가 지표 |
| 12주차 | Ch12 | RAG | Retrieval-Augmented Generation 구성 |
| 13주차 | Ch13 | LCEL | Runnable, Stream, Compose |
| 14주차 | Ch14 | 체인 | Sequential, SimpleChain, RouterChain |
| 15주차 | Ch15 | 평가 | LLM-as-Judge, 휴먼 평가, 자동 평가 |
| 16주차 | Ch16 | 에이전트 | Tool, ReAct, AgentExecutor |
| 17주차 | Ch17-1 | LangGraph: 핵심 기능 | 노드, 엣지, 상태 관리 |
| 18주차 | Ch17-2 | LangGraph: 구조 설계 | 체크포인트, 워크플로우, 디자인 |
| 19주차 | Ch17-3 | LangGraph: Use Cases | 멀티턴 대화, RAG 워크플로우 |

<br>

## 3. 스터디 진행 및 룰

### 스터디 전 준비사항

- 스터디 하루 전까지 책을 읽고 실습까지 진행한 공부 내용 정리본을 해당주차 본인의 이름이 있는 폴더에 올립니다.
    - 책 내용에 맞춰 **실습 코드**를 직접 실행 및 기록해오기
    - 내용 정리본(마크다운 파일, pdf파일 등)과 실행한 코드파일 혹은 colab notebook을 올립니다.
    - LLM을 사용한 내용정리는 지양해주세요.
    - 발표자는 발표자료만 정리하면 됨. (선택적 진행)
- 스터디 내 함께 이야기하고 싶은 내용, 질문 사항 최소 1개, 최대 3개를 준비합니다.

### 스터디 진행 방식 (발표)

- 매주 발표자를 미리 정하고 발표자는 해당 주차 내용에 대해 발표를 진행합니다.
- 발표자는 발표 자료를 자유롭게 만들어서 스터디 시간 전까지 깃허브에 업로드
    - 해당 주차 **학습 요약 + 실습 결과 + 토의거리** 준비
    - 발표 시간: **10~15분 발표 + 5분 Q&A**
- 다음주 발표자가 서기로 기록을 맡습니다.
- 발표 종료 후 책 내용에 대해서 질문 및 공유사항을 나눕니다
- **첫 발표는 팀장**부터 시작, 이후 **팀 배치 순서**대로 순환
    - 불가피하게 발표가 어려운 경우, 미리 다음 사람과 **순서 교환 가능**

### 기본 원칙

- 스터디 시간은 **지각 없이 시작** (정시 기준)
- 질문은 자유롭게, 단 **발표자 존중**
- 팀장의 **승인 하에** 시험기간 및 쉬어가는 주차 생길 수 있음
- 불성실한 참여가 지속될 시 경고 2회 후 **방출 조치**
    - 예정되지 않은 불참시 벌금 1만원 (최소 5일 전에 이야기해주기)
    - 발표자로 선정되었는데 미 준비 시 벌금 1만원
    - 개인 공부 및 진행 자료 전날 오후 11시 59분까지 업로드 안할 시 벌금 5천원
    - 개인 공부 및 진행 자료 미 진행시 벌금 1만원
