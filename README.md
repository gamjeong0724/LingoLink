<img src="https://capsule-render.vercel.app/api?type=wave&color=auto&height=200&section=header&text=Lee%20GamJeong&fontSize=80&animation=fadeIn" />

# LingoLink

<div align="center">
  <img src="/통역사.jpg" width="20%"><br/><br/> 
  
  [![Hits](https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https%3A%2F%2Fgithub.com%2Fgamjeong0724%2FLingoLink&count_bg=%2379C83D&title_bg=%23555555&icon=&icon_color=%23E7E7E7&title=hits&edge_flat=false)](https://hits.seeyoufarm.com)
</div>

# LingoLink 1V0 (personal project)

> 참여 인원 : GamJeong
> 
> 개발 기간 : 2024.05 ~


| <img src="https://github.com/gamjeong0724/LingoLink/blob/main/KakaoTalk_20240514_041609878.jpg" width="200" height="200"> | 
|---|
| GamJeong |
| [@gamjeong0724](https://github.com/gamjeong0724 "gamjeong0724_github") |
| personal |

# 개발 요구 사항

> 언어 : 한국어를 스페인어로 번역 <-> 스페인어를 한국어로 번역<br/>
> 소프트웨어 : 음성 인식, 번역 및 테스트 음성 변환을 위한 소프트웨어<br/>
> 하드웨어 : 에어팟과 유사한 무선 이어폰, 마이크, 프로세서(스마트폰 또는 전용 장치), 스피커

# 프로젝트 소개 🇰🇷

## 하드웨어 개발

### 필요한 구성품

1. 마이크로컨트롤러 : ESP32
2. 마이크 : 오디오 캡처용 고화질 MEMS 마이크
3. 스피커 : 오디오 출력용 (소형 스피커)
4. 배터리 : 장치에 전원을 공급하는 충전식 배터리
5. PCB : 모든 구성 요소를 통합하는 사용자 정의 PCB
6. 케이스 : 전자 부품을 수납하는 케이스 설계 3D로 프린팅 진행

### 하드웨어 개발 단계

1. 회로 설계 : OrCad 소프트웨어를 사용하여 장치용 회로 설계
2. 마이크로컨트롤러 프로그래밍 : ESP32를 위한 펌웨어를 작성하여 블투투스 통신, 오디오 입력/출력 및 제어로 로직을 처리
3. PCB 설계 및 제조 : PCB를 설계하고 JLPCB에서 제조
4. 하드웨어 조립 : 구성 요소를 PCB에 납떔하고 장치를 조립
5. 케이스 설계 : Solidworks 소프트웨어를 사용하여 케이스를 설계하고 3D로 프린팅

## 소프트웨어 개발

### 필요한 구성품

1. 모바일 앱 : 음성 인식, 번역 및 텍스트 음성 변환을 처리하는 앱을 개발 flutter 
2. API : 음성 인식, 번역 및 텍스트 음성 변환을 위해 API를 사용함 Google Cloud Translation API, Speech-to-Text API, Text-to-Speech API
3. 편집기 : Visual Studio Code, Android Studio

### 소프트웨어 개발 단계

1. 음성 인식 : 음성 인식 API를 사용하여 음성을 텍스트로 변환
2. 번역 : 번역 API를 사용하여 한 언어에서 다른 언어로 텍스트를 번역
3. 텍스트 음성 변환 : 텍스트 음성 변환 API를 사용하여 번역된 텍스트를 다시 음성으로 변환 시킴
4. 블루투스 통신 : 모바일 앱과 하드웨어 간의 블루투스 통신을 구현

### 시험 및 배포

1. 프로토타이핑 : 하드웨어 및 소프트웨어 통합을 위한 프로토타입을 생성하고 테스트함
2. 사용자 피드백 : 외국인 사용자로부터 피드백을 수집하여 디자인 및 기능을 개선 예정
3. 제품화 : 양산 예정은 없음 멀리서 찾아온 친구를 위한 선물용임

# 프로젝트 소개 🇺🇸

## Hardware development

### Components Required

1. Microcontroller: ESP32
2. Microphone: High Definition MEMS Microphone for Audio Capture
3. Speakers: For audio output (small speakers)
4. BATTERY: Rechargeable battery that powers the device
5. PCB: Custom PCB incorporates all components
6. Case: 3D printing is carried out with case design that accommodates electronic parts

### Hardware development phase

1. Circuit design: Circuit design for devices using OrCad software
2. Microcontroller programming: Write firmware for ESP32 to handle logic with Bluetooth communication, audio input/output and control
3. PCB design and manufacturing : PCB design and manufacture by JLPCB
4. Hardware assembly: component to PCB and device assembly
5. Case Design: Use Solidworks software to design cases and print them in 3D

## Software development

### Components Required

1. Mobile apps: developing apps that handle speech recognition, translation, and text speech conversion. flutter
2. API : uses API for voice recognition, translation, and text voice conversion Google Cloud Translation API, Speech-to-Text API, and Text-to-Speech API
3. editor : Visual Studio Code, Android Studio

### Software development phase

1. Speech recognition: Use speech recognition APIs to convert speech into text
2. Translation: Translate text from one language to another using a translation API
3. Text-to-speech conversion: Using the text-to-speech API, translated text is converted back to voice
4. Bluetooth communication: Implementing Bluetooth communication between mobile apps and hardware

### Testing and distribution

1. Prototyping: Create and test prototypes for hardware and software integration
2. User feedback: The design and function will be improved by collecting feedback from foreign users
3. Commercialization: No plan to mass-produce it. It is for a gift for a friend who came from far away
