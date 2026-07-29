<div align="center">

# 안녕하세요, 임용우입니다 👋

### 🤖 Embedded Systems & Robotics Developer

국민대학교 나노전자물리학과 · 전자시스템공학과 복수전공  
서울기술교육센터 AI융합 로봇 S/W 개발자 과정 수료

> *하드웨어부터 SW까지, 시스템 전체를 이해하는 개발자를 지향합니다.*

[![Gmail](https://img.shields.io/badge/Gmail-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:dladyddn133@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/dladyddn133-creator)

</div>

---
 
## 🛠️ Tech Stack
 
**Languages**  
![C](https://img.shields.io/badge/C-00599C?style=flat-square&logo=c&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![MATLAB](https://img.shields.io/badge/MATLAB-0076A8?style=flat-square&logo=mathworks&logoColor=white)
 
**Robotics & Embedded**  
![ROS2](https://img.shields.io/badge/ROS_2_Jazzy-22314E?style=flat-square&logo=ros&logoColor=white)
![STM32](https://img.shields.io/badge/STM32-03234B?style=flat-square&logo=stmicroelectronics&logoColor=white)
![Jetson](https://img.shields.io/badge/Jetson_Orin-76B900?style=flat-square&logo=nvidia&logoColor=white)
![RaspberryPi](https://img.shields.io/badge/Raspberry_Pi-A22846?style=flat-square&logo=raspberrypi&logoColor=white)
 
**Industrial Automation**  
![GX Works2](https://img.shields.io/badge/GX_Works2-E60012?style=flat-square&logoColor=white)
![HMI](https://img.shields.io/badge/HMI-0066CC?style=flat-square&logoColor=white)
![PLC](https://img.shields.io/badge/PLC-1E88E5?style=flat-square&logoColor=white)
 
**AI / Vision**  
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![YOLO](https://img.shields.io/badge/YOLO-00FFFF?style=flat-square&logo=yolo&logoColor=black)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white)
![ACT](https://img.shields.io/badge/ACT_Policy-FFD43B?style=flat-square&logoColor=black)
![LeRobot](https://img.shields.io/badge/LeRobot-FF6F61?style=flat-square&logoColor=white)
 
**Tools**  
![Linux](https://img.shields.io/badge/Ubuntu-E95420?style=flat-square&logo=ubuntu&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![VSCode](https://img.shields.io/badge/VS_Code-007ACC?style=flat-square&logo=visualstudiocode&logoColor=white)
 
---

## 🚀 Projects

### 🤖 [ROS 2 Multi-Robot Autonomous Exploration & Response System](https://github.com/dladyddn133-creator/ROS2-Project)

> **ROS 2 Jazzy · TurtleBot3 · SAC · SLAM · Nav2 · YOLO11n · OpenManipulator-X**  
> 팀 프로젝트 · 실물 다중 로봇 통합 및 데모 완료

세 대의 TurtleBot3가 역할을 분담하여 자율 탐색부터 위험 표적 대응까지 수행하는 다중 로봇 시스템입니다.

- SAC 기반 자율 탐색과 Cartographer SLAM
- Bayesian Risk Map 기반 위험 좌표 생성
- ROS_DOMAIN_ID와 Domain Bridge 기반 다중 로봇 통신
- Leader Waffle의 Nav2 이동 및 OMX 자동 조준
- Scout 장애 발생 시 Follower 임무 인계

**담당 영역**

- Custom YOLO11n 데이터 수집·라벨링·학습·Jetson 배포
- Point-at IK 및 IBVS 기반 OpenManipulator-X 자동 조준
- 우선순위 큐, View Pose, 상태 머신 및 안전 타격 로직
- Scout 위험 좌표와 Leader Nav2·OMX 시스템 연동

[전체 시스템 저장소](https://github.com/dladyddn133-creator/ROS2-Project) ·
[OMX 서브시스템 상세 보기](https://github.com/dladyddn133-creator/omx_aim) ·
[전체 데모](https://youtu.be/gJrPbyOyMIo) ·
[IBVS 데모](https://youtu.be/t03m8PHifMo)

`#ROS2` `#MultiRobot` `#SAC` `#SLAM` `#Nav2` `#YOLO11n` `#IBVS`

### 🖐️ [GCC — Gesture Command & Control](https://github.com/dladyddn133-creator/GCC)
> **MediaPipe · TensorFlow · BLE HID · Raspberry Pi** &nbsp;| 팀 프로젝트 

하나의 제스처 인식 엔진으로 **PC 운영체제와 RC 차량을 동시에 제어**하는 시스템.
- 커스텀 DNN 기반 손 제스처 분류 (16-D 관절 각도 → 7-class multi-label)
- BlueZ/D-Bus 기반 BLE HID로 마우스·키보드 입력 구현
- YOLOv10n 객체 탐지 + 실시간 관제 대시보드 + 주행 로그 기반 자동 귀환
- **담당:** 차량 하드웨어 설계 · GPIO 인터페이스 · 회로 설계

`#MediaPipe` `#DNN` `#BLE_HID` `#RaspberryPi` `#YOLO`

### 🌱 [STM32F411RE Smart Farm](https://github.com/dladyddn133-creator/STM32_SmartFarm_System) — Bare-Metal Embedded
> **STM32 · 베어메탈 펌웨어** &nbsp;| 팀 프로젝트

RTOS 없이 레지스터 직접 제어로 구현한 스마트팜 제어 시스템.
- RFID 출입 통제 · 자동 급수 · 채광 조절 · 화재 감지를 Non-blocking 상태 머신으로 동시 제어
- 이동 평균 필터, 히스테리시스, 소프트웨어 디바운싱으로 센서 안정성 확보
- 인터럽트 기반 타이머/ADC/PWM 제어 및 UART 통신

`#STM32` `#BareMetal` `#Firmware` `#C`

### 🧘 [MindCare](https://github.com/dladyddn133-creator/mindcare) — IoT 마음챙김 시스템
> **Raspberry Pi · Python**

라즈베리파이 기반 마음챙김 IoT 시스템.
<!-- ↓ 한 줄 설명 채워주세요 (예: 센서로 사용자 상태를 감지해 ~를 제공) -->

`#RaspberryPi` `#Python` `#IoT`

### 🏭 [PLC 자동화 창고](https://github.com/dladyddn133-creator/MiniProject_plc-automated-warehouse)
> **Mitsubishi Q-series · GX Works2 · GOT2000 HMI**

PLC 기반 자동화 물류 창고 제어 시스템.
- 래더 로직으로 입출고 시퀀스 및 컨베이어 제어 구현
- GOT2000 HMI 모니터링 화면 구성 및 메모리 맵 설계

`#PLC` `#GXWorks2` `#HMI` `#IndustrialAutomation`

### ❤️ [rPPG](https://github.com/dladyddn133-creator/rPPG-portfolio) — 비접촉 심박수 측정
> **MediaPipe · Signal Processing · 종합설계**

카메라 영상만으로 심박수를 측정하는 비접촉 rPPG 시스템.
- MediaPipe FaceMesh 기반 다채널 ROI에서 색상 신호 추출
- 밴드패스 필터 + FFT / Wavelet / Welch 주파수 분석으로 BPM 추정
- UBFC-rPPG 공개 데이터셋으로 성능 평가 · 관련 기술 특허 출원

`#rPPG` `#MediaPipe` `#SignalProcessing` `#OpenCV`

## 📊 GitHub Stats

<div align="center">
  
![Stats](https://github-readme-stats.vercel.app/api?username=dladyddn133-creator&show_icons=true&theme=tokyonight&hide_border=true)
![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=dladyddn133-creator&layout=compact&theme=tokyonight&hide_border=true)

</div>

---

<div align="center">

*"좋은 코드는 좋은 하드웨어 이해에서 나온다."*

</div>

<!--
**dladyddn133-creator/dladyddn133-creator** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
