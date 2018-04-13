---
layout: cv
title: Taeyeon Kim's CV
---
# Taeyeon Kim

<div id="webaddress">
<a href="notion33@gmail.com">notion33@gmail.com</a>
| (+82)10-8387-3327
</div>


## Interest

Task Planning, Multi-modal Sensor Fusion, Heterogeneous Multi-Robot System.

## Education

`Mar 2012 – Now`
__Korea University__, Seoul, Republic of Korea
- Bachelor of Electrical Engineering
- Cumulative GPA: 3.87 / 4.5


## PROJECTS

`May 2017 – Mar 2018`
 __Net_B-O-A-T-S__

RaspberryPI, GPS, IMU를 이용한 자율주행 보트 및 다중 보트 제어 서버 및 웹페이지 개발.

각 보트끼리는 Adhoc을 이용해 징검다리 네트워크를 구축하여 장거리 원격제어가 가능하며, 관측자가 최전방 노드에 위치한 보트의 영상 및 수온정보를 실시간으로 모니터링 할 수 있다.


 사용된기술
- Circuit Design
- Localization(GPS, IMU using RTIMULIB2 or AHRS)
- Data Collection(Camera, Water temperature)
- Embedded Programming(RaspberryPI using Python, PWM, I2C, Uart, 1-wire)
- 3D Modeling(A360) & Printing(Prusa i3)
- Web(Google Map API)
- Multithread Programming
- SocketIO(HTTP request)
 

[![2018Qualcomm_NetBoats_Poster](http://drive.google.com/uc?export=view&id=1bWyvNkD-ocZovHWVvYw2oKoxz5Jm7vAI)](http://drive.google.com/uc?export=view&id=1lMW6f3SK_3ZcnGbU5s2FbLtU7i8ed737)


작품 영상

[![작품영상](http://img.youtube.com/vi/iYtUNEpcacs/0.jpg)](https://youtu.be/iYtUNEpcacs)


[Net_B-O-A-T-S 작품보고서](https://drive.google.com/open?id=1Vi7zb170BnN9mkZTfhFAfiDFdBLASj9v)


`Sep 2017 – Nov 2017`
 __꼬기꼬기물꼬기__

RaspberryPi, Scheduler, Webdashboard, YOLO(CNN)을 활용한 다기능 어류양식 자동화 시스템.

Linear Actuator를 활용해 한개의 먹이급이기, 온도센서, 수위센서, PH센서, 카메라를 이용해 다수의 수조를 관리할 수 있다.

Darknet 기반의 Tiny YOLO(CNN)을 이용해 구피(열대어) 이미지를 학습시켜 RaspberryPI Standalone으로 개체수를 측정할 수 있다.


[![FFISHFFISH_MULFFISH_Poster](http://drive.google.com/uc?export=view&id=1KgPbXpcZQVvlFd_hhxoaHb08iMAKnprE)](http://drive.google.com/uc?export=view&id=1ya3Rz2qy-nsAP70sgnkc6-ov938WnsHa)


작품 영상

[![작품영상](http://img.youtube.com/vi/jfsvH0YcjDc/0.jpg)](https://youtu.be/jfsvH0YcjDc)


[꼬기꼬기물꼬기 작품보고서](https://drive.google.com/open?id=1I3e_PyXd1_3AT57ZleCXVEN8m-klMARM)


`Jun 2017 – Nov 2017`
 __I was CAR__

제 15회 임베디드소프트웨어 경진대회 참가작으로 Tegra3, STM32, OpenCV를 활용해 영상기반 자율주행모형자동차 소프트웨어를 개발하였다.

Camera(600x480, YUV) 및 PSD 센서를 이용하여 면허시험에서 필요한 다음의 8가지 코스를 순서에 상관없이 Robust하게 통과할 수 있다.

- 직선주행
- S자 코스
- 돌발장애물
- 언덕
- 수직 및 수평 주차코드
- 움직이는 자동차가 존재하는 로터리
- 2개의 장애물이 존재하는 3차선 구간
- 요철구간
- 신호등에 맞추어 좌혹은 우회전 코스


[![IwasCAR_Poster](http://drive.google.com/uc?export=view&id=1hO6KInJM7E8tTJpzHfwdra-DLr_gLFbT)](https://drive.google.com/open?id=1HCUxXwYC300ayrTALB4wh8zFSEYsZls8)


작품 영상

[![작품영상](http://img.youtube.com/vi/GQdmzJybGeU/0.jpg)](https://www.youtube.com/watch?v=GQdmzJybGeU)


[I was CAR 작품보고서](https://drive.google.com/open?id=1_VQAq8R3vow2dD88BDggQyHVJqS0DF-6)


`Apr 2017 – Jun 2017`
 __Multiple Object Tracking using Object Detection based on CNN__

- 졸업논문 작품으로써 CNN을 이용해 (Framework : Caffe, Architecture : Faster R-CNN, TrainingData : VOC 2007/2012, COCO 2014)으로 학습시켜 Object detection(사람)을 하고,
- RGB Histogram, CNN의 Fully Connected Layer Value, Maxpolling Layer Value의 Weighted Sum을 이용해 Object Tracking을 진행한다.
- Tracking 실패 객체가 발생시 Mean Shift Tracking을 이용해 한번 더 Tracking하여 정확도를 향상시켰다.
- MOT2015 Benchmark를 이용해 기존 기법들과 MOTA 및 MOTP를 비교 및 분석했다.

![MOT_Example_1](http://drive.google.com/uc?export=view&id=1d0Y5LjsyI4NbH6mUJomUGtDgN4ycHgwZ)
![MOT_Example_2](http://drive.google.com/uc?export=view&id=17GH3Qd0s6WtvtJLI38875JC-Mda2Od76)
![MOT_Example_3](http://drive.google.com/uc?export=view&id=10kMyBsedPp78aVpStCAeBBz79I7br0ZO)

[![MOT_Poster](http://drive.google.com/uc?export=view&id=1oujsHUHlHWlC6yDctJb3XKRwkF-uu_Ge)](http://drive.google.com/uc?export=view&id=16do1q5orRsw_teI4pDX1vaImwkh8DeOj)

[MOT 졸업논문 파일](https://drive.google.com/open?id=1P1ktkTYpzwBN3pYmyFHZBCXxgRtw7cON)


`Aug 2014 – Mar 2015`
 __Quintuple HandS__

CC3200(Texas Instruments), Embedded Programming, JavaScript를 이용해 웹기반 다기능 멀티탭을 제작하였다.

멀티탭은 비용절감을 위해 Wifi를 사용하는 5구 메인모듈과, zigbee를 사용하는 서브모듈로 구성되어 있으며, 각각의 모듈은 가변형으로 제작되어 있다.

추가적으로, IR LED를 이용하여 에어컨 ON/OFF, TV ON/OFF 및 채널, 음량변경 기능이 가능하다.

회로는 HiccupMode와 PolySwitch, Thermal Fuse를 이용해 실제 사용할 수 있도록 안정성을 강화시켰다.

3D모델링과 프린팅을 하여 엔클로저를 제작하였다.


![Quintuple_HandS](http://drive.google.com/uc?export=view&id=1m4FaOxyAN-j0n6pDSL9uzxcKAcDmShv0)
![Quintuple_HandS](http://drive.google.com/uc?export=view&id=1iE_Xb-XB9ql1cP0v8uNJZIFeo2oGpPfJ)
![Quintuple_HandS](http://drive.google.com/uc?export=view&id=1NpFG56gj2LBDfgfKvXkXnT2l0QNKbbZU)


작품 영상

[![작품영상](http://img.youtube.com/vi/L5M-odrDBwU/0.jpg)](https://youtu.be/L5M-odrDBwU)


[Quintuple_HandS 작품보고서](https://drive.google.com/open?id=1j8HDoxZGckqWbWpfRN1DqCrqDh-001kN)



`May 2014 – Jun 2014`
 __자율주행미니드론__

2014 미니드론 자율비행 경진대회 참가작으로, STM32, Ubuntu기반 Crazyfly와 OpenCV를 이용해

Altitude Hold(Hovering)와 목적지 착륙가능한 소프트웨어를 개발하였다.

![IMDRONE](http://drive.google.com/uc?export=view&id=1DOxluwuQPMXj1xqmPQpx7MFIF6-K9rSR)


[자율주행미니드론 작품보고서](https://drive.google.com/open?id=1eeNPLiPTeuuT-X-DA5DsHG23u2LQFggc)


`2007 – 2010`
 __개념있는업로더__

개인용컴퓨터를 이용해 제로보드4 (APM, PHP, MySQL)를 이용하여 무료 이미지호스팅(CDN)을 제공하였다.

오픈마켓(옥션,G마켓 등) 상품 이미지 링크, 각종 인터넷 커뮤니티 게시판에 이미지 링크를 제공할 수 있는 서비스이다.

![NotionUploader](http://drive.google.com/uc?export=view&id=14TCv7KhelpsIVPwa7BDETaCBqh6g3WeL)

[과거 홈페이지 이미지 아카이브](http://web.archive.org/web/20100709080550/http://file.notion.kr:80/)

### Publications

[Taeyeon Kim, Bumchul Jang, Hyungi Cho and Nakju Doh, __“2D CAD extraction with a 3D PCD,”__ 30th Workshop on Image Processing and Image Understanding(IPIU), Feb 2018.](http://m.site.naver.com/0nyqQ)

### TECHNICAL SKILLS

__Advanced__ C, Python, Embedded Programming (Atmega128, Cortex-M4, RaspberryPI, ESP8266, Tegra3, CC3200, Attiny8), 3D Printing(Prusa-Mendel)

__Moderate__ MATLAB, C++, OpenCV, DarkNet, Circuit Design(Ultiboard), MicroPython, Lua, PCD.

__Novice__ Markdown, LaTex, A360, Solidworks.


### ACTIVITIES

`Mar 2014 – Now`
__HandS__, 전기전자공학부 전공학회, 고려대학교.

`May 2014 – Feb 2015`
- 전공학회 HandS 부회장

`Feb 2015`
__Samsung Friendship 3rd 성과발표회__, Samsung.

`Oct 2014`
__Developer’s Delight__, Samsung.

`2018, 2017, 2015`
__학생패널__, 신임교원오리엔테이션, 고려대학교 대학교육개발원.



<!-- ### Footer

Last updated: 04.03.2018 -->


