# 🏟️ Sports Reservation Automation (Tennis / Futsal)

## 📌 프로젝트 소개

이 프로젝트는 Python + Selenium + Tkinter를 활용하여  
공공 체육시설(테니스 / 풋살) 예약을 자동으로 수행하는 프로그램입니다.

GUI 기반 입력을 통해 사용자가 정보를 입력하면  
브라우저 자동화를 통해 예약을 진행합니다.

---

## ⚙️ 주요 기능

- 🖥️ Tkinter GUI 기반 사용자 입력
- 🌐 Chrome 브라우저 자동 실행 (Normal / Headless 선택)
- 🔐 자동 로그인 기능
- 🎾 테니스 / ⚽ 풋살 선택 기능
- 📅 캘린더 기반 날짜 선택 (tkcalendar)
- ⏰ 시간대 자동 선택
- 🔄 예약 가능 여부 자동 새로고침
- 🤖 Selenium 기반 웹 자동화

---

## 🧰 사용 기술

- Python 3.x
- Selenium
- Tkinter
- tkcalendar
- Babel
- Chrome WebDriver

---

## 📦 설치 방법

### 1️⃣ 필수 라이브러리 설치

```bash
pip install selenium
pip install tkcalendar
pip install Babel
2️⃣ ChromeDriver 설치

Chrome 버전 확인

chrome://version
ChromeDriver 다운로드
https://googlechromelabs.github.io/chrome-for-testing/
설치 후 PATH 설정 또는 프로젝트 폴더에 배치
🚀 실행 방법
python macro.py
🖥️ 사용 흐름
1️⃣ 브라우저 선택
YES → 브라우저 실행
NO → Headless 모드 실행
2️⃣ 로그인
ID 입력
PASSWORD 입력
자동 로그인 수행
3️⃣ 예약 정보 입력
종목 선택 (테니스 / 풋살)
장소 선택
날짜 선택 (캘린더 UI)
참가 인원 입력
시간대 선택
4️⃣ 예약 실행
예약 사이트 접속
로그인 상태 확인
예약 가능 시간 자동 탐색
자동 클릭 후 예약 진행
⚠️ 주의사항
사이트 구조 변경 시 XPath 오류 발생 가능
ChromeDriver 버전 반드시 맞춰야 함
Headless 모드는 일부 사이트에서 차단될 수 있음
반복 refresh는 서버 정책에 따라 제한될 수 있음
🧠 프로그램 구조
Tkinter GUI
   ↓
사용자 입력
   ↓
Selenium WebDriver 실행
   ↓
자동 로그인
   ↓
예약 페이지 이동
   ↓
시간/날짜 선택
   ↓
예약 실행
💡 개선 가능 포인트
XPath → CSS Selector로 안정화
API 기반 예약 구조로 전환
실패 시 retry 로직 추가
로그 시스템 추가
headless 안정성 개선
🚀 한 줄 설명

Tkinter GUI 입력 기반 Selenium 자동 예약 시스템
