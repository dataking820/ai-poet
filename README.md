# ai-poet

## 소개
ai-poet는 사용자가 입력한 주제를 기반으로 시를 생성하는 인공지능 프로그램입니다. 이 프로그램은 Generative AI 기술을 활용하여, 사용자가 입력한 주제에 대한 시를 실시간으로 생성합니다. 이를 통해 사용자는 자신이 생각하는 주제나 감정, 상황에 대한 독창적인 시를 얻을 수 있습니다. ai-poet는 그 어떤 주제도 받아들일 수 있으며, 인공지능의 창조력을 통해 아름다운 시를 만들어냅니다.

## 설치 방법
1. 이 Repository를 Clone하거나 다운로드 받습니다.
2. Clone한 디렉토리로 이동합니다.
   ```
   cd ai-poet
   ```
3. 필요한 라이브러리를 설치합니다.
   ```
   pip install -r requirements.txt
   ```

## 설정 방법
1. 환경변수 추가방법
   - OpenAI API 키를 환경 변수에 추가합니다.
     ```
     export OPENAI_API_KEY='your-api-key'
     ```
2. .env 파일에 추가하는 방법
   - OpenAI API 키를 .env 파일에 추가합니다.
     ```
     OPENAI_API_KEY='your-api-key'
     ```
   - 이 파일을 프로젝트 루트 디렉토리에 위치시킵니다. 
   - 그리고 main.py 파일에서 아래 주석을 해제해줍니다.
     ```
     # from dotenv import load_dotenv
     # load_dotenv()
     ```

## 실행 방법
1. Streamlit를 실행합니다.
   ```
   streamlit run main.py
   ```
2. 웹 브라우저를 열고 Streamlit 앱이 실행 중인 URL로 이동합니다. (기본적으로 http://localhost:8501)
3. '시의 주제를 제시해주세요.'란에 원하는 주제를 입력하고 '시 작성 요청하기' 버튼을 누릅니다.
4. 잠시 후, 작성된 시를 확인할 수 있습니다.

## 파일 구조
- `main.py`: 프로그램의 메인 스크립트입니다. Streamlit 앱을 실행합니다.
- `requirements.txt`: 프로그램 실행에 필요한 Python 라이브러리 목록입니다.

## 기여
프로젝트에 기여하려면 Pull Request를 보내주세요. 큰 변화를 주려는 경우, 먼저 Issue를 열어서 논의해주세요.

## 라이선스
[MIT](https://choosealicense.com/licenses/mit/)
