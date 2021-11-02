# Restaurant Reservation Project, 식당 예약 프로그램

## Description 

- 사용자에게 시간, 이름, 전화번호, 인원수, 메뉴, 좌석(2, 4, 6인) 등을 입력받고 식당을 미리 예약하는 프로그램입니다.
- 텍스트 파일을 기반으로 데이터를 생성, 읽기, 수정, 삭제하는 프로그램입니다.

## Environment

- open jdk 15 GA가 설치된 MS Windows 10상의 cmd 창에서 작동합니다.
- jdk 15 이하 및 16 버전에 대한 호환성은 보장하지 않습니다.
- cmd 창 이외에 다른 시스템 터미널에서 실행은 보장하지 않습니다.
- 다른 버전의 MS Windows나 Linux / UNIX / macOS에서도 작동할 수 있지만 보장하지 않습니다.

## Installation

**{HOME}** : 사용자 고유의 홈 디렉토리의 경로입니다. 계정명이 "usuyn"이라면 홈 경로는 기본적으로 (설정에 따라 다르나)  
 - MS Windows 10의 경우 "C:\Users\usuyn" 입니다.  
 - Linux / UNIX의 경우 "/home/usuyn" 입니다.  
 - macOS의 경우 "/Users/usuyn" 입니다.  

**데이터 경로** : 식당 예약 프로그램이 사용하는 데이터가 저장되는 위치입니다. 데이터 경로에는 메뉴 정보 파일, 예약 정보 파일이 위치합니다. 경로는 "{HOME}\data"입니다.

***

- reservation.jar 파일을 MS Windows에 로그인 된 계정이 실행 권한을 가진 아무 폴더에 복사합니다.
- 데이터 경로가 존재하지 않으면 예약 정보 없이 좌석 정보만 기입된 파일이 data 폴더와 함께 자동 생성됩니다.
- 해당 jar 파일의 바로가기를 생성한 후 바로가기 파일 속성에서 대상 맨 앞에 "java -jar"를 붙여주면 바로가기를 클릭하는 것으로 실행됩니다.

## Usage

자세한 프로그램 사용 방법은 아래 pdf 파일에서 확인할 수 있습니다.  
[설명서.pdf](https://github.com/usuyn/web-practice/files/7464380/default.pdf)

## Flowchart

![사용흐름도 drawio](https://user-images.githubusercontent.com/68963707/139960539-1ac5be70-6ea2-4b4f-9b59-de23c0bdc120.png)
