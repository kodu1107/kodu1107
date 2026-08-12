<div align="center">

# 🛰️ Embedded & Radar System Developer

### Radar · Embedded · RTOS · FPGA · Signal Processing

<br>

> **From RF signals to embedded intelligence.**

<br>

![C](https://img.shields.io/badge/C-A8B9CC?style=for-the-badge\&logo=c\&logoColor=black)
![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge\&logo=cplusplus\&logoColor=white)
![STM32](https://img.shields.io/badge/STM32-03234B?style=for-the-badge\&logo=stmicroelectronics\&logoColor=white)
![FreeRTOS](https://img.shields.io/badge/FreeRTOS-5C8D3A?style=for-the-badge)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge\&logo=linux\&logoColor=black)
![Zynq](https://img.shields.io/badge/Zynq--7000-E01F27?style=for-the-badge\&logo=amd\&logoColor=white)

</div>

---

## 👨‍💻 About Me

* 🎓 **B.S. in Electrical & Electronics Engineering, Konkuk University**
* 🛰️ **LIG the Ssen Embedded School 4th**
* 📧 **Email:** [00mkr@naver.com](mailto:00mkr@naver.com)

현재 **LIG the Ssen Embedded School 4기**에서
임베디드 소프트웨어 개발에 필요한 다양한 기술을 학습하고 프로젝트를 진행하고 있습니다.

STM32 기반 MCU Programming부터 FreeRTOS, Linux, WPF Network Programming,
Zynq-7000 기반 FPGA SoC까지 폭넓게 경험하고 있습니다.

기존에는 **Radar / RF / Signal Processing** 분야의 프로젝트와 연구를 진행했으며,
현재는 이를 Embedded Software와 결합하여
**Radar · Communication · Defense System** 분야의 엔지니어를 목표로 하고 있습니다.


<br>

<div align="center">

```text
RF / Radar Hardware
        ↓
Data Acquisition
        ↓
Signal Processing
        ↓
Embedded Software
        ↓
FPGA / Communication
        ↓
Defense System
```

</div>

---

# 🎓 LIG the Ssen Embedded School 4th

<div align="center">

![STM32](https://img.shields.io/badge/STM32-03234B?style=flat-square\&logo=stmicroelectronics\&logoColor=white)
![FreeRTOS](https://img.shields.io/badge/FreeRTOS-5C8D3A?style=flat-square)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square\&logo=linux\&logoColor=black)
![CSharp](https://img.shields.io/badge/C%23-512BD4?style=flat-square\&logo=csharp\&logoColor=white)
![WPF](https://img.shields.io/badge/WPF-512BD4?style=flat-square)
![Zynq](https://img.shields.io/badge/Zynq--7000-E01F27?style=flat-square\&logo=amd\&logoColor=white)

</div>

### Experience

* STM32F429I-DISC1 기반 Embedded Programming
* GPIO / UART / ADC / DMA / Interrupt 등 Peripheral 제어
* FreeRTOS 기반 Task / Queue / Scheduling 실습
* TouchGFX 기반 STM32 Door Lock Project
* C# / WPF 기반 Network Application 개발
* TCP/IP Socket Programming
* Linux / Bash / SSH / systemd 환경 실습
* Raspberry Pi 기반 Embedded Linux System 구성
* Zynq-7000 PS / PL 구조 및 FPGA SoC 실습
* Git / GitHub 기반 Version Control 및 협업

---

# 🚀 Featured Projects

## 📡 FMCW Radar Object Classification & Tracking

<div align="left">

![Radar](https://img.shields.io/badge/FMCW-Radar-blue?style=flat-square)
![AWR1843](https://img.shields.io/badge/TI-AWR1843BOOST-red?style=flat-square)
![DCA1000](https://img.shields.io/badge/DCA1000EVM-ADC-orange?style=flat-square)
![MATLAB](https://img.shields.io/badge/MATLAB-Signal%20Processing-0076A8?style=flat-square)

</div>

FMCW Radar Raw Data를 기반으로
**차량과 보행자를 식별하고 접근 차량을 추적하는 Radar Signal Processing Algorithm**을 개발했습니다.

### 🔹 Processing Flow

```text
AWR1843BOOST
      ↓
 DCA1000EVM
      ↓
 ADC / IQ RAW Data
      ↓
    MATLAB
      ↓
Range / Doppler FFT
      ↓
Background Removal
      ↓
PSD Analysis
      ↓
Classification
      ↓
Kalman Tracking
```

### 🔹 Implemented

* FMCW ADC / IQ Raw Data 수집
* Range / Doppler FFT
* EMA 기반 Background 제거
* Zero Doppler Component 제거
* Connected Component Analysis
* PSD 기반 차량 / 보행자 특성 분석
* 연속 Frame 기반 Object Validation
* Kalman Filter 기반 Target Tracking

### 📄 Research

연구 결과를 발전시켜
**한국전자파학회 논문지(KCI) 연구 논문으로 작성했습니다.**

---

## 🫀 5.8 GHz Non-contact Vital Signal Radar

<div align="left">

![5.8GHz](https://img.shields.io/badge/RF-5.8GHz-red?style=flat-square)
![ADS](https://img.shields.io/badge/ADS-RF%20Design-purple?style=flat-square)
![STM32](https://img.shields.io/badge/STM32G474-03234B?style=flat-square)
![MATLAB](https://img.shields.io/badge/MATLAB-FFT-0076A8?style=flat-square)

</div>

5.8 GHz Radar를 이용하여 사람의 미세 움직임을 감지하고
**비접촉 방식으로 신체 신호를 측정하는 Radar Sensing System**을 제작했습니다.

### 🔹 Hardware

* ADS 기반 5.8 GHz Radar Sensor Board 설계
* RF 50Ω Transmission Line 설계
* Radar Tx / Rx 회로 구성
* STM32G474RET6 기반 Data Acquisition
* ADC Dual Mode 기반 I / Q Signal Sampling
* Timer / DMA 기반 ADC Data Acquisition
* UART 기반 PC 데이터 전송

### 🔹 Signal Processing

* MATLAB 기반 실시간 데이터 수집
* FFT 기반 Signal Analysis
* I / Q Signal Processing
* 미세 움직임 기반 비접촉 생체신호 검출

---

## 📶 5.8 GHz Microstrip Patch Antenna

<div align="left">

![Antenna](https://img.shields.io/badge/Microstrip-Patch%20Antenna-blueviolet?style=flat-square)
![ADS](https://img.shields.io/badge/ADS-EM%20Simulation-purple?style=flat-square)
![RF](https://img.shields.io/badge/RF-5.8GHz-red?style=flat-square)

</div>

5.8 GHz Radar System에 사용할
**Inset-fed Microstrip Patch Antenna를 직접 설계하고 제작했습니다.**

### 🔹 Design

* FR4 Substrate
* 5.725 ~ 5.875 GHz ISM Band
* 50Ω Feeding Line
* Inset Feeding Structure
* ADS EM Simulation
* PCB Fabrication
* Slot 구조를 이용한 Dual-band 특성 실험

---

# 🔧 Embedded Projects

## 🔐 STM32 TouchGFX Door Lock

![STM32](https://img.shields.io/badge/STM32F429I-DISC1-03234B?style=flat-square)
![TouchGFX](https://img.shields.io/badge/TouchGFX-GUI-blue?style=flat-square)
![FreeRTOS](https://img.shields.io/badge/FreeRTOS-RTOS-green?style=flat-square)

**LIG the Ssen Embedded School 4기 Project**

STM32F429I-DISC1의 Touch LCD에서 비밀번호를 입력하고
인증 결과에 따라 Servo Motor를 제어하는 Embedded Door Lock System입니다.

### Implemented

* TouchGFX GUI
* Touch Input Processing
* Password Authentication
* FreeRTOS / CMSIS-RTOS
* Task 기반 System 구조
* PWM Servo Motor Control

---

## 🎨 Real-time TCP Drawing Quiz

![CSharp](https://img.shields.io/badge/C%23-512BD4?style=flat-square\&logo=csharp\&logoColor=white)
![WPF](https://img.shields.io/badge/WPF-GUI-512BD4?style=flat-square)
![TCP](https://img.shields.io/badge/TCP%2FIP-Networking-blue?style=flat-square)

**LIG the Ssen Embedded School 4기 WPF Project**

출제자와 답변자를 TCP Network로 연결하여
실시간 그림과 메시지를 전달하는 WPF Application입니다.

### Implemented

* TcpListener / TcpClient
* Drawer / Answerer Role Management
* WPF InkCanvas
* Drawing Data Transmission
* Chat / Answer Processing
* Player State Management

---

## 🌡 Raspberry Pi Sensor Monitoring System

![RaspberryPi](https://img.shields.io/badge/Raspberry%20Pi%205-A22846?style=flat-square\&logo=raspberrypi\&logoColor=white)
![Arduino](https://img.shields.io/badge/Arduino-Nano%2033%20BLE-00878F?style=flat-square\&logo=arduino\&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square\&logo=mysql\&logoColor=white)

Sensor Data를 주기적으로 수집하여
Raspberry Pi에서 저장하고 REST API로 제공하는 Monitoring System입니다.

```text
Sensor
  ↓
Arduino Nano 33 BLE
  ↓ Serial
Raspberry Pi 5
  ├─ Data Processing
  ├─ MySQL
  ├─ REST API
  └─ systemd
        ↓
     Web Client
```

### Implemented

* Temperature / Humidity Monitoring
* Serial Communication
* MySQL Data Storage
* REST API
* systemd Auto Start
* Remote Monitoring

---

## ♻️ AI Automatic Recycling System

![Arduino](https://img.shields.io/badge/Arduino-00878F?style=flat-square\&logo=arduino\&logoColor=white)
![AI](https://img.shields.io/badge/AI-Classification-orange?style=flat-square)

카메라 입력을 기반으로 객체를 분류하고
결과에 따라 Servo Motor를 제어하여 자동으로 물체를 분리하는 시스템입니다.

### Implemented

* Dataset 구성
* Object Classification
* Arduino Control
* Servo Motor Mechanism

---

# ⚡ FPGA / SoC

## Zynq-7000

<div align="center">

```text
┌──────────────────────────────┐
│         Zynq-7000 SoC        │
│                              │
│   ┌──────────────────────┐   │
│   │ Processing System    │   │
│   │       ARM CPU        │   │
│   └──────────┬───────────┘   │
│              │ AXI           │
│   ┌──────────▼───────────┐   │
│   │ Programmable Logic   │   │
│   │        FPGA          │   │
│   └──────────────────────┘   │
└──────────────────────────────┘
```

</div>

LIG the Ssen Embedded School 과정에서
Zynq-7000 기반 ARM + FPGA SoC Architecture를 학습하고 있습니다.

### Topics

* PS / PL Architecture
* AXI Interface
* ARM + FPGA Integration
* Hardware Acceleration
* Embedded System Integration

---

# 🛠 Tech Stack

### 💻 Languages

<p>
<img src="https://img.shields.io/badge/C-A8B9CC?style=for-the-badge&logo=c&logoColor=black" style="border-radius: 10px;"/>
<img src="https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white" style="border-radius: 10px;"/>
<img src="https://img.shields.io/badge/MATLAB-0076A8?style=for-the-badge" style="border-radius: 10px;"/>
</p>

### 🔧 Embedded / Hardware

<p>
<img src="https://img.shields.io/badge/STM32-03234B?style=for-the-badge&logo=stmicroelectronics&logoColor=white" style="border-radius: 10px;"/>
<img src="https://img.shields.io/badge/FreeRTOS-5C8D3A?style=for-the-badge" style="border-radius: 10px;"/>
<img src="https://img.shields.io/badge/Arduino-00878F?style=for-the-badge&logo=arduino&logoColor=white" style="border-radius: 10px;"/>
<img src="https://img.shields.io/badge/Zynq--7000-E01F27?style=for-the-badge&logo=amd&logoColor=white" style="border-radius: 10px;"/>
</p>

### 📡 Radar / Signal Processing

<p>
<img src="https://img.shields.io/badge/FMCW-Radar-blue?style=for-the-badge" style="border-radius: 10px;"/>
<img src="https://img.shields.io/badge/FFT-Signal%20Processing-orange?style=for-the-badge" style="border-radius: 10px;"/>
<img src="https://img.shields.io/badge/Kalman-Tracking-green?style=for-the-badge" style="border-radius: 10px;"/>
<img src="https://img.shields.io/badge/ADS-RF%20Design-purple?style=for-the-badge" style="border-radius: 10px;"/>
</p>

### 🧰 Development

<p>
<img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black" style="border-radius: 10px;"/>
<img src="https://img.shields.io/badge/Ubuntu-E95420?style=for-the-badge&logo=ubuntu&logoColor=white" style="border-radius: 10px;"/>
<img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" style="border-radius: 10px;"/>
<img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" style="border-radius: 10px;"/>
</p>

---

# 🔬 Current Interests

<div align="center">

| Radar             | Embedded     | FPGA         | Communication |
| ----------------- | ------------ | ------------ | ------------- |
| FMCW Radar        | STM32        | Zynq-7000    | Wi-Fi HaLow   |
| Signal Processing | FreeRTOS     | PS / PL      | MANET         |
| Detection         | Linux        | AXI          | Mesh Network  |
| Tracking          | Raspberry Pi | Acceleration | Anti-Jamming  |

</div>


---

# 🎯 Career Direction

<div align="center">

### Radar · Embedded · FPGA · Communication

<br>

```text
RF Hardware
     +
Signal Processing
     +
Embedded Software
     +
FPGA / Communication
     ↓
Defense Embedded System Engineer
```

<br>

### 🛰️ Building systems closer to hardware.

</div>

---

# 📊 GitHub Stats

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=YOUR_GITHUB_ID&show_icons=true&hide_border=true&rank_icon=github" height="170"/>

<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=YOUR_GITHUB_ID&layout=compact&hide_border=true" height="170"/>

</div>
