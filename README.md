# chat-server

MFC 화상채팅의 중계 서버입니다.

## 프로젝트 소개

클라이언트들 사이에서 영상 및 텍스트 패킷을 받아서 상대방에게 전달해주는 중계 서버입니다.
패킷 체크섬 검증과 통신 로그 확인 기능도 포함되어 있습니다.

## 사용 기술

- C++ / MFC
- WinSock2 (TCP 통신)
- Visual Studio / x64

## 주요 기능

- 클라이언트 간 영상 및 텍스트 패킷 중계
- 패킷 체크섬 검증
- 통신 로그 모니터링

## 실행 방법

1. `Server_Project.sln` 을 Visual Studio로 열기
2. 빌드 구성 Release / x64 설정 후 빌드
3. 서버 실행 후 클라이언트에서 서버 IP로 접속

## 관련 레포지토리

클라이언트 코드: https://github.com/junesk0613/chat-client
