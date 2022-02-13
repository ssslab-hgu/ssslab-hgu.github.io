---
layout: single
permalink: /dlip/
sidebar:
  title: "Research"
  nav: "docs-research"
toc: true
toc_sticky: true
toc_label: "Research"
typora-copy-images-to: ..\assets\images
tags: dlip
entries_layout: grid
related: true
---

# Deep Learning Image Processing

## 2D Object Detection

### YoffleNet: Light-Weight Object Detection for Embedded System
The latest CNN-based object detection models are quite accurate, but they require a high-performance GPU to run in real-time. For an embedded system with limited memory space, they are still are heavy in terms of memory size and speed. Since the object detection for autonomous system is run on an embedded processor, it is preferable to compress the detection network as light as possible while preserving detection accuracy.

Therefore, this paper proposes YOffleNet, a new object detection model that is compressed at a high ratio while minimizing the accuracy loss for real-time and safe driving application on an autonomous system.

<img src="/docs/research/images/yofflenet.JPG" alt="yofflenet" style="zoom:75%;" />


<img src="../docs/research/images/demo.gif" alt="demo" style="zoom:75%;" />

[YOffleNet Deep Sort in PyTorch](https://github.com/hkim1207/2021MIP)
This repository contains a modified version of  Pytorch YOLOv3 + Deep Sort (https://github.com/mikel-brostrom/Yolov3_DeepSort_Pytorch). It is a program that counts the number of people and predicts the direction of movement using the bounding box coordinates obtained by tracking algorithm.

#### Citation
심이삭, 임주형, 장영완, 유지환, 오선택, & 김영근. (2021). 자율주행용 임베디드 플랫폼 탑재를 위한 YOLOv4 기반 객체탐지 경량화 모델 개발. 한국자동차공학회논문집, 29(10), 959-966.

<br/>

### A Lightweight CNN  for Detecting Defects in Substation Insulators with Drone EO/IR Camera

변전소 불량애자 검출을 위한 드론 EO/IR 영상 기반의 경량화 객체탐지 모델 응용 사례

<img src="../docs/research/images/corona-intro.png" alt="demo" style="zoom:75%;" />

<img src="../docs/research/images/corona1.png" alt="demo" style="zoom:75%;" />

#### Citation
* SeonTaek Oh, HyungWoo Kim, SungHyun Cho, JiHwan You, Youngsung Kwon, Won-Sang Ra, Young-Keun Kim, Development of a Compressed Deep Neural Network for Detecting Defected Electrical Substation Insulators using a Drone, Journal of Institute of Control, Robotics and Systems, vol.26 no.11,

<br/>

<br/>




## Image Processing on FPGA
### 고속 임베디드 기어 검사 시스템을 위한 불량 검출 알고리즘 FPGA 가속화 연구
#### Citation
오선택, 유지환, 김영근.(2019).고속 임베디드 기어 검사 시스템을 위한 불량 검출 알고리즘 FPGA 가속화 연구.제어로봇시스템학회 논문지,25(8),665-670.

------

 <br/>




