🚗 TalkTalkCar

시각장애인을 위한 음성명령 차량 제어 시스템

TalkTalkCar는 시각 정보 없이도 차량의 주요 기능(시동, 속도, 문, 연료)을 자연어 음성명령으로 제어할 수 있는 시스템입니다.

💡 프로젝트 배경 및 필요성

시각장애인은 차량의 기본 기능(시동, 문 개폐, 속도, 연료 확인)조차 시각 정보 기반 설계로 인해 접근이 어렵습니다. 기존 차량 제어 시스템은 정형 명령어만 인식하거나 시각 중심 UI에 의존하여, 시각장애인을 고려하지 않는 한계가 있습니다.

🎯 프로젝트 목표

자연어 음성명령으로 차량의 주요 기능을 제어하고, AI 기반 명령 해석기(OpenAI GPT-3.5-turbo)를 사용해 자유로운 일상 언어도 인식할 수 있도록 했습니다. 또한 Arduino 하드웨어와 연동해 실제 차량 기능을 제어하며, 폭우 시 주행 제한, 응급상황 보호자 자동 알림 등 실사용 맥락을 고려했습니다.

🛠️ 개발 범위

Flutter 모바일 앱 UI 및 음성 인터페이스

FastAPI 백엔드 서버와 WebSocket 통신

Arduino 하드웨어 제어

상황 인식 기능 탑재

⚡ 개발 결과

자유 명령어 인식 예시: “시동 켜줘”, “출발해볼까?”, “연료 상태 알려줘”

보호자 긴급 알림 기능

폭우 시 주행 제한 안내

RGB LED로 연료 상태 표시, 서보모터로 속도계 제어

✨ 활용 방안

시각장애인뿐 아니라 노약자, 손이 자유롭지 않은 일반 사용자에게도 유용하며, 자율주행 스마트카의 보조제어 시스템으로 확장 가능합니다.

🖥️ 실행 방법

Flutter 앱 실행: frontend 폴더에서 flutter run

FastAPI 서버 실행: backend 폴더에서 uvicorn main:app --reload

Arduino 코드 업로드: Arduino IDE로 arduino 폴더의 .ino 파일을 열고 보드에 업로드

📂 폴더 구조

frontend: Flutter 앱
backend: FastAPI 서버
arduino: Arduino 코드
images: 스크린샷 이미지

🖼️ 화면 구성 

앱 메인 화면: ![image](https://github.com/user-attachments/assets/1d97ffa8-38af-43b0-92cb-9b722282b2b5)

음성명령 인식 화면: ![image](https://github.com/user-attachments/assets/404d26cb-5760-4581-8afb-960ab1060568)

명령 실행 결과 화면: ![image](https://github.com/user-attachments/assets/b666678d-1288-4a5e-bf31-eed71d51694a)

GPT API 기반 AI 어시스턴트 화면: ![image](https://github.com/user-attachments/assets/149b9e79-abff-4c78-9b10-2a16e438362f)

비상상황 알림 화: ![image](https://github.com/user-attachments/assets/8b5a83e6-6464-4575-af5d-29fe8079a24b)


📝 나의 역할

Flutter 프론트엔드 개발(UI/UX, 음성인식, TTS), WebSocket 실시간 통신 연동, 접근성 및 응급 알림 UI 설계
