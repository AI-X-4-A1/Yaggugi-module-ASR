# Yaggugi-module-ASR

![Python](https://img.shields.io/badge/Python-v3.12.7-3776AB?style=for-the-badge&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-v2.5.1-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-v0.115.4-009688?style=for-the-badge&logo=fastapi&logoColor=white)

> 약국이는 내 몸에 맞는 영양제를 추천하고, 섭취 일정을 손쉽게 관리하는 맞춤형 건강 앱 입니다.


```bash
<!-- 실행방법 -->
git clone https://github.com/AI-X-4-A1/Yaggugi-module-ASR.git

cd Yaggugi-module-ASR

docker build -t yaggugi-module-asr .

docker run --env-file .env -d -p 8010:8000 --name yaggugi-module-asr yaggugi-module-asr

<!-- 테스트 방법 -->
http://localhost:3000/

<!-- 특이 -->
ffmpeg : 인코딩 디코딩 관련 모든 기능을 제공하는 오픈 소스 
macOS : brew install ffmpeg
윈도우 : Windows에서는 FFmpeg를 직접 설치. 파일 경로 환경변수에 추가.
```

## 🩺 **Feature**

- 영양제 플래너 ASR
    - 음성인식모델(Whisper)
    - 음성감정분류(LLM : llama3-8b & Groq API)

## 🩺 **Folder Structure**

```bash
begin_fastAPI/
├── main.py               # FastAPI 애플리케이션 코드       
├── requirements.txt      # 필요한 패키지 목록
└── Dockerfile            # Docker 설정 파일
```

## 🩺 **Contributor**

- Yesssung | 박예성 | [깃허브](https://github.com/Yesssung)
- shaneee123 | 이세인 | [깃허브](https://github.com/shaneee123)

## 🩺 **Stack**

![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![LLama38b](https://img.shields.io/badge/LLama38b-7289DA?style=for-the-badge&logo=llama&logoColor=white)
![Whisper](https://img.shields.io/badge/Whisper-5A9?style=for-the-badge&logo=whisper&logoColor=white)


