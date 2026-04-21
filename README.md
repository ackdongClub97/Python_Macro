🧾 프로젝트 소개

이 프로젝트는 Python과 Selenium을 활용하여
공공 체육시설(테니스 / 풋살) 예약 사이트를 자동화하는 프로그램입니다.

GUI(Tkinter)를 통해 사용자가 직접 정보를 입력하고
브라우저 자동화를 통해 예약을 수행합니다.

⚙️ 주요 기능
✔ GUI 기반 예약 입력창 (Tkinter)
✔ 브라우저 실행 선택 (Headless / Visible)
✔ 자동 로그인 기능
✔ 테니스 / 풋살 선택
✔ 날짜 캘린더 선택 (tkcalendar)
✔ 시간대 자동 선택
✔ 예약 가능 여부 자동 새로고침
✔ Selenium 기반 웹 자동화
🧰 사용 기술
Python 3.x
Selenium
Tkinter
tkcalendar
Babel
Chrome WebDriver
📦 설치 방법
1️⃣ 필수 패키지 설치
pip install selenium
pip install tkcalendar
pip install Babel
2️⃣ ChromeDriver 설치

Chrome 버전 확인

chrome://version
맞는 ChromeDriver 다운로드
https://googlechromelabs.github.io/chrome-for-testing/
PATH 설정 또는 프로젝트 폴더에 위치
🚀 실행 방법
python macro.py
🖥️ 프로그램 흐름
1️⃣ 브라우저 선택
YES → Chrome 실행
NO → Headless 모드 실행
2️⃣ 로그인
ID 입력
PASSWORD 입력
자동 로그인 수행
3️⃣ 예약 정보 입력
종목 선택 (테니스 / 풋살)
장소 선택
날짜 선택 (Calendar UI)
참가 인원 입력
시간대 선택
4️⃣ 예약 자동 실행
사이트 이동
로그인 유지 확인
예약 가능 시간 탐색
자동 클릭 후 예약 완료
⚠️ 주의사항
실제 사이트 구조 변경 시 XPath 오류 발생 가능
ChromeDriver 버전 반드시 맞춰야 함
Headless 모드는 일부 사이트에서 막힐 수 있음
자동 반복 refresh는 서버 정책에 따라 제한될 수 있음
🧠 핵심 구조
Tkinter GUI
   ↓
사용자 입력
   ↓
Selenium WebDriver
   ↓
로그인 자동화
   ↓
예약 페이지 접근
   ↓
조건 기반 시간 선택
   ↓
예약 완료
📌 프로젝트 특징
GUI + 자동화 결합
실시간 예약 경쟁 대응 구조
XPath 기반 DOM 제어
사용자 입력 기반 동적 예약 시스템
💡 개선 가능 포인트
안정적인 Selector (XPath → CSS)
API 기반 예약 전환
로그 시스템 추가
실패 시 retry 로직 개선
headless 안정성 개선
🚀 한 줄 설명

👉 “Tkinter GUI로 입력 받고 Selenium으로 자동 예약까지 수행하는 Python 자동화 프로그램”
