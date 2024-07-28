# 🤖 DressDreamer 프로젝트

## 📝 프로젝트 소개

이 프로젝트는 얼굴 분석을 통한 개인화된 패션 추천 시스템입니다.

## ✨ 주요 기능

- 💬 텍스트 대화: Gemini 기반의 대화 모델
- 🖼️ 이미지 생성: Stable Diffusion XL를 이용한 이미지 생성
- 📖 모델: aldente0630/musinsaigo-3.0

## 🛠️ 기술 스택

- **Frontend**: Streamlit
- **Backend**: FastAPI
- **AI 모델**:
  - 대화: Gemini
  - 이미지 생성: Stable Diffusion XL

## 🚀 설치 및 실행 방법

1. 저장소 클론:
   ```
   git clone [저장소 URL]
   cd [프로젝트 디렉토리]
   ```

2. 필요한 패키지 설치:
   ```
   pip install -r requirements.txt
   ```

3. 각 서비스 실행:
   - 이미지 생성 및 얼굴 분석 서버:
     ```
     fastapi_fashion.ipynb
     ```
   - 프론트엔드:
     ```
     streamlit run app.py
     ```

## 📖 사용 방법

1. Streamlit 앱 접속
2. '패션 추천해줘'와 같은 문구 포함 시 패션 추천 이미지 생성

## 👨‍💻 개발자 정보

- **개발자**: 정강빈
- **버전**: 2.0.0

## 🔗 API 엔드포인트

- 이미지 생성 API: `이미지 토큰/fashion`

## 📜 라이선스

이 프로젝트는 [라이선스 이름] 하에 배포됩니다. 자세한 내용은 `LICENSE` 파일을 참조하세요.

---

❗ **참고**: API 엔드포인트는 개발 환경에 따라 변경될 수 있습니다. 실제 배포 시 안정적인 URL로 업데이트해주세요.
