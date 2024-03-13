# 정보통신

통신(communication) : 정보 교환을 위한 모든 수단 (서신, 봉화...)

정보 통신(ICT) : 디지털 데이터로 통신하는 것

## 정보 통신의 역사

* 1837년 모스(Morse) 부호 : 새뮤얼 모스
* 1876년 음성통화 : 알렉산더 그레이엄 벨
* 1940년 전화기를 이용하여 원격 계산기와 통신 : 스티비츠 
* 1958년 SAGE. 관제탑과 항공기 연결 
* 1960년 SABRE 
* **1969년 ARPANET 인터넷의 전신. TCP/IP 프로토콜. 패킷 교환 네트워크 : 미국방성 산하기관 ARPA**
* 1968년 ALOHA. 최초의 무선 패킷 교환 방식 : 하와이 대학
* 1975년 TELENET. 최초의 상용 패킷교환 네트워크

## 정보 통신망의 목적

* 자원의 공유(resource sharing) : 지리적 위치에 관계없이 자원을 자유롭게 공유
* 신뢰도(reliability) 향상 : 한 대의 컴퓨터가 정지하더라도, 다른 컴퓨터를 사용할 수 있음 
* 분산 처리(distribution of processing functions) : 각 컴퓨터가 각자 처리할 만큼의 데이터를 처리하고, 복잡한 연산은 슈퍼컴퓨터에게 맡길 수 있다.


## 정보통신망 구성

### 구성 요소

`단말 장치 -- 신호변환장치 ---통신 회선--- 신호변환장치 -- 통신제어장치` -- `컴퓨터`\
데이터 전송 시스템 <=> 데이터 처리 시스템

### 선로

* 점대점 선로 : 성(star)형 네트워크. 핫라인(hotline)
* 멀티드롭 선로 : 하나의 선로에 여러개의 드롭이 연결 됨. 선로제어 프로토콜이 필요

### 연결장치

네트워크 세그먼트를 서로 연결하거나 네트워크를 인터넷에 연결시키기 위한 통신 장치

* 모뎀(MOdulation, DEModulation) 
* 네트워크 인터페이스 카드(NIC)
* 허브
* 리피터
* 브리지
* 라우터
* 게이트웨이

### 전송방식

#### 전송 방향
* 단방향 전송(simplex transmission) `->` : 라디오
* 반이중 전송(half-duplex) `<->` : 무전기 
* 전이중 전송(full-duplex transmission) `<=>` : 전화망

#### 전송 모드
* 직렬전송(serial transmission) : 한 번에 한 비트 씩 전송
* 병렬전송(parallel transmission) : 여러 개의 전송로를 통해 동시에 여러 비트를 전송

#### 데이터 교환 방식

* 회선교환 방식 : 예전 전화교환 방식 같은거
* 패킷교환(packet switching) 방식 : 데이터를 일정 비트로 나누어 전송
  * 가상회선 방식(virtual circuit) : 논리적인 경로를 설정한 후 동일한 경로로 전송
  * 데이터그램 방식(datagram) : 패킷을 독립적으로 경로를 설정하지 않고 보냄. 
    비연결지향형(connectionless) 통신 방식. 도착 패킷의 순서가 달라질 수 있어 올바른 순서로 재구성이 필요

### 정보통신망 유형

#### 위상

![network topology](./assets/10-01_network-topology.jpeg)

fully connected 형이라고 모든 노드를 연결하는 경우도 있는데 잘 안씀

#### 규모

* **LAN (Local Area Network)**
* **WAN (Wide Area Network)**

#### 활용 목적

* VAN (Value Added Network) 
* ISDN (Integrated Service Digital Network)
* B-ISDN (Broadband ISDN)

### 통신프로토콜 유형

* TCP/IP 
* IP
* UDP
* SMTP
* POP3
* HTTP
