![image](https://github.com/user-attachments/assets/69a435b6-b46c-45c8-9264-6a2796416bdd)
![image](https://github.com/user-attachments/assets/2e863443-3b9f-4b35-b05b-f7b2eae9f1b7)
![image](https://github.com/user-attachments/assets/a23e76a9-f72f-4a22-9e4c-2a4309359ed2)
![image](https://github.com/user-attachments/assets/191513bf-f5a8-4cfd-ab6e-fc042c2b7a14)
![image](https://github.com/user-attachments/assets/c1ddd8fd-d5f4-40ca-95d4-eac0613503b7)
![image](https://github.com/user-attachments/assets/5681c222-f938-4bdd-ac47-4a4d23916244)
![image](https://github.com/user-attachments/assets/f4f71365-49e0-460f-beeb-37a186dbc05e)
![image](https://github.com/user-attachments/assets/8be7b9bb-8b79-4f47-8d16-8071417159cc)
![image](https://github.com/user-attachments/assets/1bc92af6-b0f4-43f6-9b54-ca3de27f6b53)
![image](https://github.com/user-attachments/assets/8190787f-67d6-4a37-9dbc-c77568706d81)
![image](https://github.com/user-attachments/assets/414cc7ad-5a45-4519-b39d-7083a06599f8)

[TalkTalkCar]

-시각장애인을 위한 음성명령 차량 제어 시스템

-TalkTalkCar는 시각 정보 없이도 차량의 주요 기능(시동, 속도, 문, 연료)을 자연어 음성명령으로 제어할 수 있는 시스템입니다.

[프로젝트 배경 및 필요성]

-시각장애인은 차량의 기본 기능(시동, 문 개폐, 속도, 연료 확인)조차 시각 정보 기반 설계로 인해 접근이 어렵습니다. 기존 차량 제어 시스템은 정형 명령어만 인식하거나 시각 중심 UI에 의존하여, 시각장애인을 고려하지 않는 한계가 있습니다.

[프로젝트 목표]

-자연어 음성명령으로 차량의 주요 기능을 제어하고, AI 기반 명령 해석기(OpenAI GPT-3.5-turbo)를 사용해 자유로운 일상 언어도 인식할 수 있도록 했습니다. 또한 Arduino 하드웨어와 연동해 실제 차량 기능을 제어하며, 폭우 시 주행 제한, 응급상황 보호자 자동 알림 등 실사용 맥락을 고려했습니다.

[개발 범위]

-Flutter 모바일 앱 UI 및 음성 인터페이스

-FastAPI 백엔드 서버와 WebSocket 통신

-Arduino 하드웨어 제어


[개발 결과]

-자유 명령어 인식 예시: “시동 켜줘”, “출발해볼까?”, “연료 상태 알려줘”

-보호자 긴급 알림 기능

-폭우 시 주행 제한 안내

-RGB LED로 연료 상태 표시, 서보모터로 속도계 제어

[활용 방안]

-시각장애인뿐 아니라 노약자, 손이 자유롭지 않은 일반 사용자에게도 유용하며, 자율주행 스마트카의 보조제어 시스템으로 확장 가능합니다.


[폴더 구조]

frontend: Flutter 앱
backend: FastAPI 서버
arduino: Arduino 코드
images: 스크린샷 이미지

[화면 구성] 

1) 앱 로그인 화면: 

![image](https://github.com/user-attachments/assets/8a8b15b6-36d8-4f02-af30-ffb508191510)

2) 음성명령 인식 화면: 

![image](https://github.com/user-attachments/assets/f8d01aaf-7ba4-4d57-a720-78865a655e4e)

3) 명령 실행 결과 화면: 

![image](https://github.com/user-attachments/assets/85d7f055-a6c4-4ca3-9b80-ada61ab6cd7d)

4) GPT API 기반 AI 어시스턴트 화면: 

![image](https://github.com/user-attachments/assets/cc6d08dd-bdcd-4ac4-80a1-ac8abf2a785d)




[최종 보고서 및 발표자료]

- [TalkTalkCar 최종보고서 보기](docs/TalkTalkCar-%20보고서.pdf)
- [TalkTalkCar 최종 발표 PPT 보기](docs/TalkTalkCar_0611(%EC%B5%9C%EC%A2%85%20%EB%B0%9C%ED%91%9C%20PPT).pptx)


