# aformat

'aformat' is Advenced (Low level for fast format) format program by used based open source programs.

본 프로그램 'aformat' 는 기존의 베이스 오픈소스 유닉스, POSIX, 리눅스 의 기초 오픈소스 프로그램들을 활용하여 가장 빠르고 최대한 의 효율성으로 협소적 로우 레벨 (fast randomtic wiping) 포맷을 멀티 프로세싱을 활용 하여 진행 시켜 주는 프로그램 입니다.

본 프로그램은 기초 오픈소스 프로그램들을 최대한 활용 하는 쉘스크립트 기반으로만 짜여져 있습니다.

## Version

0.1-07 (Sat, 13 Feb 2021 05:14:43 +0900)

### 변경사항

1. 프로그램 이름 재정의 (aformat → aformat)


## 지원 운영체제

linux , freebsd , unix , posix... 

(# Shell)

## 작업진행 순서

필수요소 프로그램 확인 > 입력한 디스크 확인 > 포맷 할지 여부 사용자에게서 확인 > 디스크 삭제 > 디스크 용량 대비 카운트 계산 > 계산된 회수만큼 무작위 포맷 > 디스크 파일시스템 재구성 > 디스크 EXT 파일 논리 구조 확보 > ext4 기반 디스크 파일시스템 체크 > 디스크 초기화  

<img src="https://github.com/cosmosp2/aformat/blob/master/aformat_algo1.png">

## 설치 및 시작 방법

	git clone https://github.com/cosmosp2/aformat
	
	sudo ./aformat <디스크>
	
## 예제

	sudo ./aformat /dev/sdx


## 제작자 

Hanle OS를 꿈꾸며 https://cosmosproject2015.tistory.com/
email : cosmosproject15@gmail.com

## 라이선스 (License)

GPL-2.0
