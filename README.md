<div align="center">

# 안녕하세요, 최용훈입니다 👋
### 임베디드 시스템과 IoT를 공부하는 개발자입니다

C/C++ 기반의 임베디드 제어(STM32, Arduino)와 OpenCV를 활용한 비전 처리를 연결해서,
하드웨어가 실제로 판단하고 움직이는 시스템을 만드는 데 관심이 있습니다.

</div>

<br/>

## 🛠 Tech Stack

**Languages**

![C](https://img.shields.io/badge/C-A8B9CC?style=for-the-badge&logo=c&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![C#](https://img.shields.io/badge/C%23-239120?style=for-the-badge&logo=csharp&logoColor=white)

**Embedded / Hardware**

![STM32](https://img.shields.io/badge/STM32-03234B?style=for-the-badge&logo=stmicroelectronics&logoColor=white)
![Arduino](https://img.shields.io/badge/Arduino-00979D?style=for-the-badge&logo=arduino&logoColor=white)
![FreeRTOS](https://img.shields.io/badge/FreeRTOS-000000?style=for-the-badge&logo=freertos&logoColor=white)
![Raspberry Pi](https://img.shields.io/badge/Raspberry%20Pi-A22846?style=for-the-badge&logo=raspberrypi&logoColor=white)
![ROS](https://img.shields.io/badge/ROS-22314E?style=for-the-badge&logo=ros&logoColor=white)

**Data / Network / Tools**

![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)
![VS Code](https://img.shields.io/badge/VS%20Code-007ACC?style=for-the-badge&logo=visualstudiocode&logoColor=white)

<br/>

## 🚀 Featured Projects

### 🎯 [Auto-Tracking Pan-Tilt Turret System](https://github.com/yonghoon304/target_tracking_system)
웹캠으로 얼굴/색상 객체를 실시간 검출하고, PD 제어 알고리즘과 칼만 필터로 2축 서보모터를
구동해 객체를 중앙에 정조준하는 자동 추적 터렛 시스템입니다. 비전 처리(Ubuntu/Raspberry Pi)와
실시간 모터 제어(STM32 + FreeRTOS)를 분리해 지연 시간을 최소화했습니다. *(팀 프로젝트)*

`C` `C++` `OpenCV` `STM32` `FreeRTOS` `CAN/UART` `Kalman Filter`

---

### 🏭 [SmartConveyor](https://github.com/yonghoon304/Project_SmartConveyor)
컨베이어 벨트 위 물체의 QR 코드를 인식해 컨베이어와 로봇팔을 자동 제어하는 프로젝트입니다.
PC/Raspberry Pi가 OpenCV·ZBar로 QR을 판단하면, Arduino가 CAN 메시지로 변환해
STM32(FreeRTOS) 보드들이 모터·로봇팔을 구동합니다. *(팀 프로젝트)*

`C++` `OpenCV` `ZBar` `Arduino` `CAN Bus` `STM32` `FreeRTOS`

---

### 👾 [iot_MiniProject](https://github.com/yonghoon304/iot_MiniProject) — 포켓몬 배틀 시스템
캡슐화·추상화·팩토리 패턴 등 객체지향 설계를 적용한 턴제 포켓몬 배틀 게임입니다.
타입 상성 데미지 계산, MP/PP 자원 관리, 레벨 기반 랜덤 인카운터 로직을 구현하고
MySQL로 유저·포켓몬 데이터를 영속화합니다.

`C++` `MySQL` `OOP Design Patterns`

<br/>

## 📚 Study & Practice Repositories

IoT 개발자 과정에서 진행한 학습 기록과 문제 풀이 저장소입니다.

**언어 기초**

| Repository | 설명 | 주요 스택 |
|---|---|---|
| [pre-learning-2026](https://github.com/yonghoon304/pre-learning-2026) | 과정 사전학습 — 개발환경 구성, Markdown, Python 기초 | `Python` |
| [iot-basic-programing-2026](https://github.com/yonghoon304/iot-basic-programing-2026) | C언어 기초~중급 문법 학습(포인터, 구조체, 파일 입출력) 및 토이프로젝트 | `C` |
| [iot-Cpp-Basic-2026](https://github.com/yonghoon304/iot-Cpp-Basic-2026) | C++ 객체지향 기초 — 생성자/소멸자, 복사·이동 생성자, 클래스 | `C++` |
| [CPP-OOPstudy-2026](https://github.com/yonghoon304/CPP-OOPstudy-2026) | C++ 객체지향 심화 학습 | `C++` |
| [iot-python-2026](https://github.com/yonghoon304/iot-python-2026) | Python 기초 문법 — C/C++와 비교하며 학습 | `Python` |
| [iot-dotnet-2026](https://github.com/yonghoon304/iot-dotnet-2026) | C#·.NET 기초~응용, 윈앱/웹앱/유니티 연동 개념 | `C#` `.NET` |

**자료구조·알고리즘 / 코딩테스트**

| Repository | 설명 | 주요 스택 |
|---|---|---|
| [iot-algorithm-2026](https://github.com/yonghoon304/iot-algorithm-2026) | 자료구조·알고리즘 — 스택/큐, 재귀, 정렬, 탐색, 복잡도 분석 | `C` |
| [programmersCPP](https://github.com/yonghoon304/programmersCPP) | 프로그래머스 코딩테스트 문제 풀이 (Level 0~) | `C++` |

**시스템 / 네트워크**

| Repository | 설명 | 주요 스택 |
|---|---|---|
| [iot-RaspberryPi](https://github.com/yonghoon304/iot-RaspberryPi) | 라즈베리파이 5 환경설정, SSH/VNC 원격 접속, 리눅스 기본 | `Raspberry Pi` `Linux` |
| [iot-ROS](https://github.com/yonghoon304/iot-ROS) | ROS(Robot Operating System) 학습 | `ROS` |
| [2026-NetworkSocket](https://github.com/yonghoon304/2026-NetworkSocket) | TCP/IP 소켓 프로그래밍, VMware+Ubuntu 서버/클라이언트 환경 구성 | `C` `Linux` `Socket` |

**데이터베이스 / AI 활용**

| Repository | 설명 | 주요 스택 |
|---|---|---|
| [iot-database-2026](https://github.com/yonghoon304/iot-database-2026) | 데이터베이스 개념, MySQL 설치 및 활용 | `MySQL` |
| [iot-ai-utilization-2026](https://github.com/yonghoon304/iot-ai-utilization-2026) | ChatGPT·Gemini·NotebookLM 등 AI 도구 활용법 학습 | `AI Tools` |

<br/>

## 📊 GitHub Stats

<div align="center">

<img height="165" src="https://github-readme-stats.vercel.app/api?username=yonghoon304&show_icons=true&hide_border=true" />
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=yonghoon304&layout=compact&hide_border=true" />

</div>

<br/>

## 📫 Contact

<div align="center">

[![Email](https://img.shields.io/badge/Email-dydgns304%40naver.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:dydgns304@naver.com)

</div>
