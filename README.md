# 아두이노 기반의 스마트 윈도우 블라인드

## Introduction
대기 중 미세먼지 농도를 측정하여 대기질에 따라 창문의 자동 개폐가 가능할 뿐만 아니라 주변 환경의 밝기에 따른 블라인드 조절도 가능한 스마트 윈도우 블라인드를 설계하였다.

## 내용
* 제안하는 시스템은 하드웨어(측정), 소프트웨어(분석 및 제어), 어플리케이션(사용자 UI)로 크게 구분한다. 측정은 입출력 센서들을 통해 구현시킨다. 자동제어 기능에는 빗물감지 센서, 미세먼지 센서, 온습도 센서, 조도 센서가 사용된다. 이 센서들로부터 입력된 값에 따라 출력값을 출력 장치인 스테핑모터와 DC모터로 보내 창문과 블라인드를 자동으로 제어 가능하게 한다. 
* 수동제어 기능은 블루투스로 연결된 모바일 어플리케이션을 통해 사용자가 직접 리모컨과 같이 원격으로 제어할 수 있도록 한다.
```
### 제안하는 시스템의 전체 회로도
```
<p align='center'>
  <img src='https://github.com/choies-tu/capstone2020/blob/main/img/fig01.JPG' />  
</p>

```
### 앱입벤터를 이용하여 구현된 모바일 어플리케이션 실행화면
```
<p align='center'>
  <img src='https://github.com/choies-tu/capstone2020/blob/main/img/fig02.JPG' />
</p>

```
### 스마트 윈도우 블라인드 구현모습으로 프로토타입
```
<p align='center'>
  <img src='https://github.com/choies-tu/capstone2020/blob/main/img/fig03.JPG' />
</p>

