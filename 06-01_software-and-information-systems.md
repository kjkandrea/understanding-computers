# 소프트웨어와 정보시스템

## 소프트웨어

### 시스템 소프트웨어

컴퓨터를 사용자가 손쉽게 사용할 수 있도록 도와주는 동시에 컴퓨터 시스템을 효율적으로 운영해 주는 기능을 갖춘 프로그램의 집단

컴퓨터 하드웨어를 운영하고, 응용 소프트웨어가 동작하기 위한 기반 구조를 형성하는 소프트웨어. 

운영체제, 컴파일러, 인터프리터, 유틸리티 소프트웨어 등

#### 운영체제  

컴퓨터가 동작하는 동안 항상 운영체제가 실행되고 있음

초기 형태는 CLI 형태의 인터페이스 => 현재는 GUI

운영체제의 역할
1. 사용자가 컴퓨터와 대화할 수 있도록 인터페이스를 제공함
2. 컴퓨터의 하드웨어 장치를 관리함
   * 주기억장치의 관리
   * 디스플레이, 키보드, 마우스, 오디오 장치, 프린터, 네트워크, 보조기억장치 등의 관리
3. 파일 시스템을 관리하고 보존함
   * 폴더 관리, 파일 CRUD, 파일 검색, 백업 및 복구  
4. 프로그램들이 원활하게 실행될 수 있도록 관리하고 지원함

유닉스(UNIX)
* 멀티태스킹, 멀티유저를 지원하는 운영체제
* 1970년대에 벨 연구소에서 개발. 이후 소스코드 공개
* 1980년대 후반 이후 서로 다른 UNIX 사이의 호환성 및 이식성이 떨어지는 문제를 해결하기 위한 표준화 시도

리눅스(Linux)
* 1991년 리누스 토발즈가 개발한 자유 소프트웨어 및 오픈 소스에 입각한 운영체제
* 유사 유닉스(UNIX-like) 운영 체제
* 우분투, 슬렉웨어, 데비안, 페도라 등

#### 언어번역기

프로그래밍 언어로 작성된 프로그램을 컴퓨터가 실행할 수 있는 기계어 코드로 변환하는 프로그램

컴파일러
* 원시 프로그램 전체를 기계어 명령으로 구성된 목적 프로그램으로 번역함
* 인터프리터 방식에 비해 프로그램이 빠르게 실행 됨

인터프리터
* 프로그램의 문장 단위로 명령을 해석하여 실행함
* 프로그램 번역을 기다리지 않고 즉시 실행할 수 있음

두 방식의 장점을 절충한 다양한 변형이 활용됨

#### 유틸리티 소프트웨어

프로그램을 작성하거나 컴퓨터를 운영하는데 도움이 될 수 있도록 제공하는 프로그램

* 파일 관리 유틸리티
* 백업 소프트웨어
* 데이터 압축 유틸리티
* 디버깅 유틸리티
* 텍스트 에디터
* 디스크 관리 유틸리티
* 안티 바이러스
* 스크린 세이버


### 응용 소프트웨어 

컴퓨터 사용자들이 특정 분야의 응ㅇ용을 목적으로 사용할 수 있도록 개발되는 프로그램

#### 사용자 프로그램

컴퓨터의 개별 사용자나 기업, 기관의 정보화 조직에서 그들의 필요에 따른 응용 목적을 달성하기 위해 만든 프로그램

#### 응용 패키지 프로그램

표준화되고 특성화된 프로젝트에 대해서 사용자들이 쉽게 활용하도록 소프트웨어 개발 회사에서 제작된 프로그램

* 워드프로세서 (Ms Word, 애플의 Pages 등)
* 스프레드시트 (Excel, 애플의 Numbers 등)
* 멀티미디어 소프트웨어 (Adobe 등)

## 소프트웨어 개발

### 저급언어

#### 기계어

제 1세대 프로그래밍 언어 - 기계 중심의 언어

컴퓨터가 직접 이해하고 실행할 수 있는 2진 코드 형태의 언어

#### 에심블리어

제 2세대 프로그래밍 언어 - 기계 중심의 언어

기계어 명령을 알기 쉬운 기호로 표현

### 고급언어

제 3세대 프로그래밍 언어 - 문제 해결 중심의 언어

사람에게 친숙한 문장 구조나 수식 표현을 사용한다.

문제 해결 방식에 따라 다양한 패러다임이 존재함
* 절차적 언어 : FORTRAN, COBOL, PASCAL, C 등
* 객체지향 언어 : C++, Java, C#, Objective-C 등

### 제 4세대 언어

기존 순차적 고급언어에 비해 보다 높은 수준의 기능을 제공함으로써 프로그래밍 노력이나 시간을 줄이기 위한 언어

* 데이터베이스의 검색 (SQL)
* 리포트 생성
* 데이터 조작 및 분석 등을 위한 언어 등 

### 제 5세대 언어

**추상화 레벨이 가장 높은 언어라는 의미가 아님**

주어진 문제에 대해 제공된 규칙, 제약사항 등을 이용하여 문제를 해결하는 방식의 언어

함수형 언어, 논리적 언어 등의 선언형 언어

인공지능의 구현이나 전문가 시스템을 만드는 데 사용됨

LISP, Prolog, OPS5 등

### 프로그램이란?

원하는 결과를 얻을 수 있도록 컴퓨터에게 일연의 일을 시키는 명령어의 집합체

필요로 하는 업무를 처리할 수 있또록 알고리즘을 설계하고, 프로그래밍 언어로 구현함

### 알고리즘(algorithm) 이란?

주어진 문제를 해결하기 위하여 유한한 개수의 잘 정의된 명령으로 표현된 처리 절차

#### 알고리즘의 표현

* 필요한 처리를 하기 위한 프로그램을 작성하기 위해 먼저 알고리즘을 구성해야 함
* 알고리즘을 명확하게 나타내기 위한 표현 방법이 필요함
  * 순서도 (flow chart)
  * 의사 코드 (pseudocode)

### 소프트웨어 공학(software engineering)

신뢰성 있고 요구 기능을 효율적으로 수행하는 소프트웨어를 경제적으로 생산하기 위해 건전한 공학적 원리와 방법을 만들고 사용하는 것

소프트웨어의 개발, 운영, 유지보수에 체계적이고 숙달되고 정량화된 접근 방법을 적용하는 것

### 소프트웨어 개발 방법론

소프트웨어 개발 계획과 관리를 잘 하기 위한 목적으로 개발 업무를 구분된 활동 단계로 나누어 조직화하는 것

* 폭포수 모델
* 애자일 모델

waterfall : 계획 => 요구분석 => 설계 => 구현 => 시험 => 유지보수 

## 소프트웨어의 사용권

소프트웨어의 사용이나 배포, 수정 등과 관련하여 허용된 법적인 권한을 정한 것

사용자는 소프트웨어를 구매하거나 취득하는 과정에서 최종사용자 사용권 동의서를 확인하고 동의함으로써 명시된 사용 권한을 갖게 됨

### 사유 소프트웨어 (proprietary software)

저작권 소유자가 허가한 법적 권한의 범위에서 사용할 수 있는 컴퓨터 소프트웨어

소프트웨어를 분석 및 수정, 공유하는 행위를 제한 함

상용 소프트웨어의 경우 이에 상응하는 비용을 소프트웨어의 소유자에게 지불해야 함

셰어웨어(shareware) : 상용 소프트웨어지만 사용자에게 일정 기간 동안 제한된 기능만을 무료로 제공하는 소프트웨어

프리웨어(freeware) : 사용권에 대한 비용이 없이 사용할 수 있도록 허용된 소프트웨어 

* 사용권은 개인이나 기관, 기업에 다르게 적용될 수 있음
* 개인에게 무료로 제공되는 프리웨어를 직장의 컴퓨터에 설치해서 사용할 경우 저작권 침해가 될 수 있음

### 자유 소프트웨어 운동 

리처드 스톨먼 (Richard Stallman) 이 주도한 GNU 프로젝트

사용자가 소프트웨어를 사용하고 공유하며 분석하고 수정할 수 있는 자유를 누리게 할 것을 주장함

소프트웨어 공유를 위해 핵심적인 부분인 운영체제 및 관련 유틸리티 소프트웨어가 필요

* GNU 시스템이라 부르는 Unix 와 호환되는 소프트웨어 시스템 개발
* 리눅스(Linux) : GNU 시스템의 핵심이 되는 운영체제 커널
* GNU GPL (일반 공중 사용권) 을 따름

1. 프로그램을 어떠한 목적으로든 사용할 수 있는 자유
2. 프로그램의 소스 코드를 분석하고 수정할 수 있는 자유
3. 소프트웨어를 타인에게 재배포할 수 있는 자유
4. 사용자가 수정한 소프트웨어를 배포할 수 있는 자유

GNU GPL, BSD, Mozilla Public License, MIT, Apache

### 경영정보 시스템 (MIS)

기업 경영에 관한 정보를 제공해주는 컴퓨터 시스템
* 단순 전산 처리 중심 => 기업 경영에 도움을 주는 정보 제공

* 거래처리 시스템 (TPS)
* 의사결정지원 시스템 (DSS)
* 전사적 자원관리 (ERP)
* 고객관계 관리 (CRM)
* 공급망 관리 (SCM)

#### ERP 

상샌, 판매, 자재, 인사, 회계 등 기업 전반적인 업무 프로세스를 하나의 체계로 통합한 시스템
