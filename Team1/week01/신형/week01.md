# LangChain 스터디 기록 (Chapter 1 - 설치 및 키 발급)

## 1. 환경 설정 / API key 발급

- `pyenv`로 Python 3.11.13 설치
  
  ```bash
  pyenv install 3.11.13
  pyenv global 3.11.13
  python --version  # Python 3.11.13

  
<img width="1030" height="558" alt="스크린샷 2025-10-05 오전 12 40 52" src="https://github.com/user-attachments/assets/fb9e8dcd-ea45-4def-8208-0a06367324d8" />
<img width="1148" height="596" alt="스크린샷 2025-10-05 오전 12 54 27" src="https://github.com/user-attachments/assets/5bd3ebf8-d01d-49fe-b355-0f442e1d1ca5" />

- 전역으로 3.11 버전으로 지정해줘야 한다고 합니다.
  
<img width="1192" height="900" alt="스크린샷 2025-10-05 오전 12 58 27" src="https://github.com/user-attachments/assets/07525002-6426-430b-b6b3-dd094061c29a" />

- LangChain 및 관련 라이브러리  어마어마하게 깔아줍니다. 


<img width="1214" height="384" alt="스크린샷 2025-10-05 오전 1 06 14" src="https://github.com/user-attachments/assets/18c1cd88-a8b3-4452-a5ee-bed50db0dcb8" />

- .env 수정해서 api "ture"가 나오도록 설정하기. 근데 이제 공식 api 발급한 것이 아니여서

<img width="1438" height="1224" alt="스크린샷 2025-10-05 오전 1 15 19" src="https://github.com/user-attachments/assets/16e461d5-419c-406d-9ebc-68dcf2de15fa" />

- 이런 오류가 생겼습니다... 키 발급을 해오겠습니다...

<img width="1882" height="748" alt="스크린샷 2025-10-05 오전 1 36 50" src="https://github.com/user-attachments/assets/c7419f78-6d50-4b93-adf4-0ddb9a1ec485" />

- openAI api 발급을 위해 5달러를 결제해줍니다. 기존 GPT결제와 무관하게, api를 사용하려면 모두 결제를 해야 하더군요
  
<img width="976" height="484" alt="스크린샷 2025-10-05 오전 1 39 32" src="https://github.com/user-attachments/assets/40c6ee57-f31e-40f2-be71-2a36426e09df" />

- 이렇게 정상작동을 하는 모습입니다. 그래도 api를 쓰려면 발급 후 10-30분은 기다려야 한다네요..

## 2. OpenAI LLM

