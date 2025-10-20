![header](https://capsule-render.vercel.app/api?type=rect&section=header&height=200&text=Road%20To%20Engineer&fontAlignX=50&fontAlignY=40&color=gradient&fontSize=100&fontColor=ffffff&desc=It's%20Doyeop's%20GitHub&descAlignY=70&descAlign=50&descSize=20)

## 👋 About Me
FPGA와 RTL 설계에 집중하며 **반도체 설계 엔지니어**를 목표로 성장하고 있습니다.  
Verilog/SystemVerilog, EDA Tool(Vivado, Synopsys, VCS), 임베디드 시스템, 영상 처리 기반의 다양한 프로젝트를 수행하며  
**설계부터 구현·검증까지의 전체 흐름**을 경험했습니다.  

📘 프로젝트의 전체 개요와 활동 이력은 [Notion Portfolio](https://www.notion.so/23736fad22be8043b294c7b8438d87f0)에서, 각 프로젝트의 세부 기술 내용은 GitHub 리포지토리에서 확인할 수 있습니다.


<br>

## 📬 Contact
- **Email**  
  [![Gmail Badge](https://img.shields.io/badge/ehduqdl88@gmail.com-126304?style=flat-square&logo=gmail&logoColor=white)](mailto:ehduqdl88@gmail.com)

<br>

## 🎓 Education
- 대한상공회의소 **AI 시스템 반도체 설계 과정 (2기)** – 2025.03 ~ 2025.10  (진행 중)     
  (RTL 설계 및 검증, 시스템 프로그래밍, Synopsys Design Compiler, AI 알고리즘과 구조)

  - RTL 설계 및 검증 (Verilog, SystemVerilog)  
  - FPGA 설계 및 Synopsys Design Compiler 활용  
  - MCU 프로그래밍 (C, Timer/PWM/UART, Interrupt)  
  - AI 알고리즘 및 응용 (CNN, LLM, IoT)

- 학사: 상명대학교 전자공학 졸업 (2023.02)

<br>

## 🚀 Projects

| 프로젝트 (Project) | 설명 (Description)  | 수행기관 (Organization) | 링크 (Links)  |
| :--- | :--- | :---| :--- |
| **VGA Filter & Camera System** <br> 📅 (25.09.16 ~ 25.09.30) | • **OV7670 카메라 입력**과 **VGA 출력**을 이용해 실시간 영상 처리 구현<br> • **Line Buffer 기반 필터 구조 (Sobel, Sharpen, Gaussian, Cartoon, Mirror, Ghost)** 설계<br> • **AXI4-Lite / APB 버스**를 통한 CPU–Peripheral 간 데이터 제어<br> • **FPGA 내부 Frame Buffer**로 동적 영상 처리 및 필터 전환 기능 구현 | 대한상공회의소 | [VGA_Filter_Project](링크 예정) |
| **RISC-V RV32I CPU Design** <br> 📅 (25.08.14 ~ 25.08.29) | • **RISC-V 명령어 세트 기반 32-bit Single/Multi-Cycle CPU 설계**<br> • **DataPath / Control Unit / ALU / Register File** 직접 구현<br> • **Vivado, Synopsys VCS & Verdi**를 활용한 합성 및 시뮬레이션<br> • 모든 명령어 타입의 실행 검증 완료 | 대한상공회의소 | [RISC-V_RV32I_CPU](https://github.com/lauriela8/RISC-V_RV32I_CPU) |
| **FPGA 512-Point Fixed FFT** <br> 📅 (25.05.10 ~ 25.05.30) | • **512-point Radix-2² SDF FFT 구조** 설계 및 검증<br> • **Fixed-Point 기반 Butterfly 연산**과 **CBFP(Common Block Floating Point)** 기법 적용<br> • **Adder 재사용**으로 자원 최적화 수행<br> • **Vivado FPGA 검증 및 Bitstream 생성 완료** | 대한상공회의소 | [FFT_512point_Project](링크 예정) |
| **AI IoT Gesture Project** <br> 📅 (25.02.01 ~ 25.03.15) | • **Mediapipe Hand Landmark 기반** 제스처 인식 모델 설계<br> • **TFLite 변환**을 통한 추론 속도 최적화 및 **LLM(Gemma3)** 기반 자연어 명령 해석<br> • **라즈베리파이–ESP8266–IoT 기기 제어** 통합 구현<br> • 제스처 + 음성 명령 기반 **스마트홈 멀티모달 제어 시스템** 구축 | 대한상공회의소 | [AI_IoT_Gesture_Project](https://github.com/chanwon3144/AI-PROJECT) |
| **FPGA Multi-Module System** <br> 📅 (25.04.10 ~ 25.04.25)   | • **초음파, 온습도, 시계 모듈**을 APB 기반으로 통합<br> • **FND, LCD, GPO, GPI** 등 주변장치 제어 및 데이터 통신 설계<br> • FPGA 상에서 **모듈 간 타이밍 동기화 및 인터페이스 검증** 수행 | 대한상공회의소 | [FPGA_MultiModule_System](https://github.com/lauriela8/FPGA_Multi_Module_System) |
| **STM32 Dodge Rush Game** <br> 📅 (25.01.10 ~ 25.01.25) | • **ARM Cortex-M3 기반 STM32 보드**에서 게임 로직 구현<br> • **Timer, UART, Interrupt**를 이용해 캐릭터 이동·충돌·시간 처리<br> • **LCD 및 조이스틱 입력 처리**를 통한 실시간 그래픽 출력 | 대한상공회의소 | [ARM_Project](https://github.com/lauriela8/ARM_Project) |


<br>

## 🛠 Tech Stack
![C](https://img.shields.io/badge/C-A8B9CC?style=flat&logo=c&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Verilog](https://img.shields.io/badge/Verilog-FF6F00?style=flat&logoColor=white)
![SystemVerilog](https://img.shields.io/badge/SystemVerilog-00979D?style=flat&logoColor=white)
![STM32](https://img.shields.io/badge/STM32-03234B?style=flat&logo=stmicroelectronics&logoColor=white)
![Raspberry Pi](https://img.shields.io/badge/RaspberryPi-C51A4A?style=flat&logo=raspberrypi&logoColor=white)
![Vivado](https://img.shields.io/badge/Xilinx%20Vivado-F7931E?style=flat&logo=xilinx&logoColor=white)
![Synopsys](https://img.shields.io/badge/Synopsys-FF6F00?style=flat&logoColor=white)  
![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)
![VS Code](https://img.shields.io/badge/VS%20Code-007ACC?style=flat&logo=visualstudiocode&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat&logo=linux&logoColor=black)

<br>

## 📊 GitHub Stats
![Your GitHub stats](https://github-readme-stats.vercel.app/api?username=lauriela8&show_icons=true&theme=radical)
![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=lauriela8&layout=compact&theme=radical)

<br>

![snake gif](https://github.com/lauriela8/lauriela8/blob/output/github-contribution-grid-snake.svg)

