---
layout: article
title: "Interests"
date: 2018-09-13 05:03:20 Z
author: ISL
categories: research
excerpt: 
image:
   teaser: interests.jpg
   path: interests.jpg
comments: true
locale: "en"
share: true
ads: true
--- 

{% include toc.html %}

## Visual odometry and SLAM
**SLAM(Simultaneous Localization and Mapping)** : 로봇이 자신의 **위치와 주변 지도를 동시에 추정**하는 기법으로, GPS를 사용할 수 없는 환경에서도 동작이 가능하다는 장점이 있다. SLAM은 추적 및 매칭에서 발생하는 오차가 성능에 큰 영향을 미친다. 이러한 문제를 해결하기 위해 **RAFSet SLAM**을 제안하였다.

<p style="text-align: center;">
	<img src="../../images/SLAM01.png" alt="Drawing" style="width: 800px"/><br>
    Fig1-1. Concept of RAF(Robust Aged Feature)</br>
</p>

<p style="text-align: center;">
	<img src="../../images/SLAM02.png" alt="Drawing" style="width: 800px"/><br>
    Fig1-2. RAFSet SLAM Results</br>
</p>
<p style="text-align: center;">
	<img src="../../images/SLAM03.png" alt="Drawing" style="width: 800px"/><br>
    Fig1-3. KITTI Visual Odometry 부문 31위 (17.07.13)</br>
</p>

## GAN
**GAN(Generative Adversarial Networks)** : 대표적인 **비지도 학습(Unsupervised Learning)**중 하나로 **생성자(Generator)**와 **구별자(Discriminator)**의 **경쟁(Minimax problem)**을 통해 이미지를 생성한다. 

<p style="text-align: center;">
	<img src="../../images/GAN01.png" alt="Drawing" style="width: 800px"/><br>
    Fig2-1. Concept of GAN</br>
</p>
<p style="text-align: center;">
	<img src="../../images/GAN02.png" alt="Drawing" style="width: 800px"/><br>
    Fig2-2. GAN Results</br>
</p>

## De-Hazing  
**De-Hazing** : **안개나 해무, 옅은 구름** 등으로 인해 발생하는 **열화를 개선**하는 기법으로, **기존의 DCP(Dark Channel Prior)** 기반의 알고리즘의 경우 **짙은 안개에 취약**하다는 단점이 있다. 이러한 문제를 해결하기 위해 **HLS 컬러 공간 기반의 안개 제거 기법**을 제안하였다.

<p style="text-align: center;">
	<img src="../../images/DEHAZING01.png" alt="Drawing" style="width: 800px"/><br>
    Fig3-1. Concept of De-Hazing</br>
</p>
<p style="text-align: center;">
	<img src="../../images/DEHAZING02.png" alt="Drawing" style="width: 800px"/><br>
    Fig3-2. HLS 컬러 기반의 안개 제거 성능 (입력, 출력)
</br>
</p>

## Intensity Enhancement (Retinex)
**Intensity Enhancement** : **역광현상**이나 **부족한 광원의 세기**로 인해 발생하는 **열화를 개선**하는 기법으로, 기존의 MSR의 경우 각 채널을 독립적으로 연산하여 원본의 색상 정보를 왜곡하고, 채도가 다소 떨어진다는 단점이 있다. 이러한 문제를 해결하기 위해 **MSRMS(MSR with Modified contrast and Saturation correction)**를 제안하였다.

<p style="text-align: center;">
	<img src="../../images/MSR01.png" alt="Drawing" style="width: 800px"/><br>
    Fig4-1. Concept of MSR</br>
</p>
<p style="text-align: center;">
	<img src="../../images/MSR02.png" alt="Drawing" style="width: 800px"/><br>
    Fig4-2. Flow chart of MSRMS
</br>
</p>
<p style="text-align: center;">
	<img src="../../images/MSR03.png" alt="Drawing" style="width: 800px"/><br>
    Fig4-2. MSRMS의 성능 (입력, 출력)
</br>
</p>

## Frame Rate Up Conversion (FRUC)
TBD

## 3D Reconstruction (Active Stereo Vision)
TBD

## 천장 지향
TBD
## 특징 검출
TBD