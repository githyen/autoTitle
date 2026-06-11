# 🎥 Video Subtitle Automation Tool

이 프로젝트는 유튜브 링크나 로컬 MP4 파일을 입력받아, **자동으로 자막을 생성하고 영상에 합성하여 결과물을 출력**하는 웹 기반 자동화 서비스입니다.

## 🚀 주요 기능
* **간편한 영상 입력:** 유튜브 URL 직접 입력 또는 드래그 앤 드롭 파일 업로드.
* **자동 자막 생성:** `stable-ts`를 활용하여 높은 정확도의 한국어 자막(SRT) 생성.
* **영상 합성:** `FFmpeg`을 사용하여 영상에 폰트 스타일이 적용된 자막을 즉시 합성.
* **웹 기반 UI:** 깔끔한 대시보드 UI를 통해 누구나 쉽게 사용 가능.

---

## 🛠 기술 스택
* **Backend:** Python, FastAPI, Uvicorn
* **Processing:** FFmpeg, stable-ts, yt-dlp
* **Frontend:** HTML5, Tailwind CSS, JavaScript (Fetch API)

---

## 📋 설치 및 실행 방법

### 1. 사전 준비
시스템에 `FFmpeg`이 설치되어 있어야 합니다.
```bash
# Ubuntu/Debian 기준
sudo apt update
sudo apt install ffmpeg fonts-nanum -y
sudo fc-cache -fv


