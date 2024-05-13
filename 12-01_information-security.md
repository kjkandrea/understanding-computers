# 정보 보안

정의: 정보를 사용하는 과정에서 발생할 수 있는 부작용에 대처하기위한 모든 정보보호 활동

## 목표

* 기밀성 : 허가되지 않은 사용자에게 정보가 **노출**되지 않도록 하는 것
* 무결성: 허가되지 않은 사용자에 의해 정보가 **변경**되지 않도록 하는 것
* 가용성 : 허가된 사용자가 원하는 경우, 지체 없이 정보에 접근할 수 있도록 하는 것

## 네트워크 보안 요구사항

* 실체 인증 : 정보통신에 참여한 실체에 대한 진위 검증
* 데이터 **무결성** : 데이터가 파괴되거나 변경되지 않도록 함
* 데이터 보안성 (**기밀성**과 **유용성**) : 데이터의 비밀이 보장되고 사용자 접근이 제어됨
* 데이터 인증 : 데이터가 신뢰할 수 있는 자로부터 전송된 것인지 확인
* 부인 방지 : 데이터 송신을 부인하거나 수신을 부인할 수 없도록 함

## 해킹

의도에 상관없이 다른 컴퓨터에 침입하는 모든 행위

크래킹 : 다른 컴퓨터 시스템에 파괴적인 계획을 가지고 침입하는 행위

### 백도어(backdoor)

허가받지 않은 사용자가 인터넷과 같은 네트워크를 통해 다른 시스템에 들어갈 수 있을 만큼 허술한 부분

### 스니핑(sniffing)

네트워크 상에서 전달되는 다른 사람들의 패킷을 엿보며 계정과 패스워드를 알아내려는 행위

### 스푸핑(spoofing)

해커가 어떤 호스트의 IP주소나 이메일 주소를 바꾸어 일반 사용자의 권한을 획득한 뒤 정보를 빼가는 해킹

### 서비스 거부 공격(DoS; Denial of Service)

서버가 처리할 수 있는 능력 이상의 서비스를 요구하여 다른 서비스를 정지시키거나 시스템을 다운시키는 공격

## 악성 프로그램의 종류

### 컴퓨터 바이러스

일종의 명령어들의 집합으로 컴퓨터 프로그램이나 데이터 파일을 감염시킴

### 웜

네트워크를 통해서 자신을 복제, 전파할 수 있는 프로그램

### 트로이 목마

컴퓨터 사용자의 정보를 빼내가기 위한 목적으로 제작된 악성 프로그램

## 악성 프로그램의 감염유형

### 피싱(Phishing)

Private Information + Fishing

인터넷에서 송신자를 알리지 않는 스팸 메일을 이용하여 수신자의 개인 정보를 탈취하는 범죄

### 파밍(Pharming)

Phishing + Farming

정당한 웹 사이트의 도메인을 탈취하거나 DNS 이름을 속여 가짜 웹사이트로 유인한 뒤 개인정보를 탈취하는 범죄

## 보안 강화 방법

### 암호화 (encryption)

인터넷에서 누구나 읽을 수 있는 평문을 제3자가 읽을 수 없는 형태인 암호문으로 변환하는 과정

### 복호화 (decryption)

암호문을 평문으로 변환하는 과정

### 대칭키 암호화 방식

암호화 키와 복호화 키가 동일한 것

* 장점 : 구현이 용이하고 실행 속도가 빠름
* 단점 : 키 분배 및 키 관리가 어려움, 인증과 송수신 부인 방지가 보장되지 않음

### 공개키 암호화 방식

암호화 키와 복호화 키가 다름

* 암호화 키 (공개키)
* 복호화 키 (비밀키)

* 장점 : 키 분배 문제를 해결
* 단점 : 처리 속도가 느림, 부인 방지(디지털 서명 기능)

### 전자서명

공개키 암호화 방식에서의 개인키를 이용한 메시지 암호화는 메시지 작성자만이 할 수 있으므로 이를 이용하여
메시지의 작성자 본인을 알리는 서명을 작성할 수 있음

### 방화벽 사용 

방화벽 : 패킷을 검사하여 조건에 맞는 패킷들만 통과시키는 소프트웨어나 하드웨어를 총칭
