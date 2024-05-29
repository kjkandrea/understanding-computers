# 인터넷

## 인터넷 개요

서버 - ISP - 클라이언트

* `ISP; Internet Service Provider` : 인터넷을 서비스해주는 기관을 의미

### 인터넷 이란?

전 세계적인 정보통신망

**Inter**connected **Net**work

### 인터넷의 역사

* 1960년대 초 폴 배런(Paul Baran) 의 생각으로부터 출발 
* 1968년 ARPA 에서 1968년에 계획. 1969년에 구축한 ARPANET 
* 1972년 국제통신학회에서 일반에 공개
* 1973년 영국과 노르웨이 사이 국제적인 통신망 형성
* 1983년 MILNET(군사용), ARPANET(민간용)으로 구분
* 이후 TCP/IP를 적용한 NSPNET에 민간용 네트워크 추가

### 인터넷의 특성
* 개방 구조
  * 프로토콜, 제도, 규격 등이 완전히 개방된 통신망이다.
* 호스트 간의 평등성
  * 인터넷에 연결된 모든 컴퓨터는 정보의 송수신에서 대등한 위치에 놓인다.
* 독자적인 주소 할당
  * 인터넷에 연결된 모든 컴퓨터는 고유한 IP 주소를 갖는다.

## 인터넷 주소

### Internet Protocol Address

IP 주소. 

IPv4
* 32비트(4byte)를 8비트씩(0 ~ 255) 4등분으로 나누어 각 부분을 점으로 구분
* NIC(Network Information Center) 에서 할당하고 관리
* 0.0.0.0 ~ 255.255.255.255 약 43억(2^32)개의 주소 사용 가능
* 주소 고갈현상 발생

IPv6
* 주소 길이가 128비트(16byte)로 약 340조(2^128)개의 주소를 제공
* 차세대 인터넷 통신규약 - IPng(IP next generation)라고도 함

### 도메인 이름

* 인터넷에 연결되어 있는 호스트 컴퓨터의 주소를 나타내는 IP 주소는 숫자로 구성되어 있음
* 도메인 이름은 IP 주소의 각 자리 숫자를 사람이 기억하기 쉬운 영문자로 바꾼 것
* 202.232.172.32 => foo.com

### DNS; Domain Name System

사용자가 도메인 이름을 사용하여 호스트 컴퓨터에 연결하고자 할때 DNS는 도메인 이름과 그에 대응하는 IP 주소를 저장한 데이터베이스를 이용하여, 해당 IP 주소로 변환하여 연결시켜줌

### URL; Uniform Resource Locator 

인터넷에서 특정 전산 자원을 지정하는 주소를 일관되게 표현하는 방식

형식
* 프로토콜 이름 (https)
* 도메인 이름 (google.com)
* 해당 파일의 위치를 나타낸 경로 이름 (/foo/bar)

## 인터넷 서비스

### 월드 와이드 웹 (WWW; World Wide Web)

* 1989년 스위스의 유럽입자물리연구소에서 제안한 광역정보시스템
* 목적 : 네트워크상에 하이퍼텍스트를 구축해 모든 정보를 끊임없이 액세스 할 수 있게 하는 것

HTTP; Hyper Text Transfer Protocol
* 하이퍼텍스트 파일 송수신용 응용 프로토콜
* HTTP입장에서 웹브라우저는 클라이언트
* HTML; Hyper-Text Markup Language

### 전자 우편

e-mail (electronic mail)

* 인터넷을 이용하여 컴퓨터에 저장한 메시지를 주고받을 수 있게 해주는 정보통신 서비스
* 보낼 때 
  * SMTP; Simple Mail Transfer Protocol
* 받을 때
  * POP3; Post Office Protocol 3
  * IMAP; Internet Message Access Protocol

### FTP

* 인터넷상에서 컴퓨터 간에 파일을 교환하기 위한 표준 프로토콜
* TCP/IP 응용 프로토콜 중의 하나
* FTP(File Transfer Protocol) 서비스

### Telnet; Telecommunication Network

인터넷에 연결되어 있는 컴퓨터를 원거리에서 접속하여 제어하거나 조작할 수 있는 정보통신 서비스

### Usenet; user's network

인터넷 웹과 웹 브라우저가 나타나기 훨씬 이전에 등장한 세계의 수백만 사용자가 참여하는 토론 그룹의 모임이자 인터넷 사용자의 전자게시판

## 인터넷 응용

### 정보검색

검색엔진을 사용하여 인터넷상에서 사용자가 필요로 하는 정보를 찾는 행동

검색엔진(Search Engine)
* 사용자가 제시한 검색어를 포함하는 웹사이트를 검색하는 소프트웨어
* 구성요소
  * 인터페이스 프로그램
  * 크롤링 프로그램
  * 색인 프로그램

### 전자상거래

* BtoB: 기업 간의 거래
* BtoC: 기업/소비자 간의 거래
* CtoC: 소비자 간의 거래

### e-Learning

정보통신기술을 활용한 모든 형태의 학습

### 인터넷 전화

VoIP; Voice over Internet Protocol 을 활용하여 일반 전화망에서 이루어졌던 음성 서비스를 IP망을 기반으로 패킷 데이터를 통해 음성 통화를 구현하는 통신기술

* 케이블을 통해 여러 명이 동시에 사용 가능
* 확장성이 뛰어남
* 기존 전화에 비해 요금이 매우 저렴함

스카이프, 카카오톡, 라인 등

### IPTV

Internet Protocol TV

* 인터넷 프로토콜을 사용하여 소비자에게 디지털 텔레비전 서비스를 제공하는 시스템
* 시청자가 자신이 편리한 시간에 보고 싶은 프로그램을 선택해서 볼 수 있음 (VOD; Video on Demand)

OTT service; over the top media service

인터넷을 통해 방송 프로그램/영화/교육 등 각종 미디어 콘텐츠를 제공하는 서비스

### SNS

Social Network Service (Social Media)


