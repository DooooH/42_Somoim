# 42_Somoim

# C피신 소규모 채널 부흥 운동

    팀명: 미안하다. 이거 보여주려고 어그로 끌었다. 
    프로젝트명: 42 소모임

# 프로젝트 개요

42내 자유로운 소규모 모임 활성화를 도와주는 슬랙봇 

C피신 당시 슬랙채널에는 소규모 채널들이 다양하게 존재했습니다. 채널들은 저마다의 특별한 관심사들을 담고 피씨너들을 이어주는 역할을 하고 있었는데요. 하지만 본과정 채널로 옮기면서 사라질 수 밖에 없었습니다. 그것을 지켜보면서 아쉬웠던 저희 팀은 그 문화를 다시 살려볼 수 없을까 궁리 했습니다.
 그래서 채널 생성에 제한이 되는 슬랙 대신 자유롭게 생성가능한 카카오톡 오픈 채팅방이나 디스코드 서버 등을 새 거처로 만들고 이 링크를 공식 채널 내 봇을 통해 유통하는 방식을 구상하게 되었습니다.



# 프로젝트 상세

본 프로젝트는 42 본과정을 진행 중인 모든 42인들이 속해있는 42born2code 슬랙 워크스페이스 내부에서 사용할 수 있는 슬랙 봇의 개발을 목표로 합니다. 
이 슬랙 봇을 통해 운영자는 소모임에 대한 간단한 설명, 오픈 카톡방 또는 디스코드 링크를 등록할 수 있고,  참가자는 소모임 리스트를 조회 할 수 있습니다. 




# 기대성과

1. 42인들 간의 유대감 형성에 기여를 할 수 있을 것 입니다.
2. c피신 당시 유쾌하고 가볍게 만들 수 있었던 소모임 문화를 다시 살릴 수 있을 것 입니다.
3. 일상적으로 이용하는 슬랙 기반의 소모임 관리로 접근성을 높일 수 있을 것입니다.



# We are..

hjeon
    역할: 팀장
    핵심기여역량: 프로젝트 기획 / 관리,  소스 개발, 관련 기술 리서치
    
dohkim
    역할: 팀원
    핵심기여역량: 프로젝트 기획, 소스 개발, 관련 기술 리서치

yjeon
	여건상 미 참여

# 개발 환경

개발 도구: Node.js, AWS, Bolt, MySQL
협업 도구: github(with gitflow), slack, hangout, vscode liveshare
개발 방식: 페어 프로그래밍, 기능별 분담 개발 



## 회의 일지

### 20200418

- 기획
  - 아이템 선정 (해결하고 싶은 문제)
    - 클러스터 내 정수기 일회용 컵, 텀블러 정리문제
    - 식사 - 마땅히 먹을 식당을 못 찾겠다. 후기의 부족.
    - 미세먼지 - 클러스터 내 미세먼지의 심각성 인지 부족.
    - 평가 문제 : 매칭이 쉽지 않다.
    - **소모임 :  c-piscine 당시 활발했던 슬랙 내 소모임 문화가 옮겨온 42슬랙에서는 제한된다. 전과 같이 활발하지 않은 소모임 문화.**
  - 사용 시나리오
    - 소모임 등록 : 소모임 이름, 간단한 설명, 오픈카톡방 링크, 소모임장 닉네임 등록
    - 소모임 조회 : 소모임의 이름, 소모임장 닉네임, 간단한 설명, 오픈카톡방 링크 리스팅
    - 소모임 삭제
    - 소모임 내용 수정
- 기술 조사
  - 타입스크립트
  - 슬랙봇
  - 데이터베이스
- 향후 스케줄 계획
  - 1주차 : 슬랙봇 틀 만들기
  - 2주차 : 서버 (데이터베이스) 만들기
  - 3주차 : 디버깅 / 정리

### 20200420

- 기술 조사 및 테스트 슬랙 봇 생성
  - Bot Framework 조사
    - Hubot
    - Botkit
  - 슬랙 봇 앱 생성
    - 테스트 워크스페이스 생성
    - 슬랙 봇 생성에 필요한 환경 설정 
  - Botkit을 이용한 슬랙 봇 테스트
    - Botkit Framework 설치
    - 사용법 학습 및 튜토리얼 진행 (미완)
- 향후 스케줄 계획
  - 4/21 15:00 PM 행아웃을 통한 원격 협업 진행 예정
  - 테스트봇 완성
  - 필요 기술 재점검
  - Typesrcipt 학습
  - Botkit Framework 함수 사용법 학습



### 20200421 (화)

- 봇 프레임워크 재선정 : botkit -> bolt 

  - 친절한 공식문서
  - 간편한 사용법

- 활용 기술 재점검

  - 컨테이너 : 도커
  - 클라우드 : aws
  - 언어 : 타입스크립트
  - 봇 프레임워크 : bolt
  - DB

- 볼트 튜토리얼 진행 완료

- 향후 계획

  1. 상세 시나리오 구상

  2. 볼트 공식문서 학습

  3. 타입스크립트 학습
