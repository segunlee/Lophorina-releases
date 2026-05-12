# Lophorina

**Lophorina**는 Apple 개발자를 위한 macOS 유틸리티 앱입니다. 개발하며 자주 쓰는 도구들을 한 곳에서 사용할 수 있습니다.

> macOS 15.0 이상 필요

![Lophorina 스크린샷](screenshot.png)

## 기능

### 인코딩 / 디코딩
- **Base64** — 텍스트를 Base64로 인코딩하거나 디코딩
- **URL 인코딩** — URL을 인코딩/디코딩. 문자셋 선택 가능 (User, Password, Host, Path, Query, Fragment)
- **한글 변환** — `\uXXXX` 형태의 유니코드 이스케이프로 깨진 한글 텍스트 복원

### 암호화
- **AES** — AES 방식으로 텍스트를 암호화하거나 복호화. 모드, 패딩, 출력 형식(Hex / Base64) 설정 가능

### JSON
- **JSON** — JSON 포맷팅, 유효성 검사, 조작

### Apple 개발자 도구
- **APNs** — 테스트 푸시 알림 전송. `.p8` 키와 `.p12` 인증서 지원. 탭으로 여러 페이로드 관리
- **앱 아이콘** — 1024×1024 이미지 한 장으로 Xcode 앱 아이콘 에셋 카탈로그 전체 생성
- **프로비저닝 프로파일** — 설치된 프로비저닝 프로파일 목록 조회 및 검색. 만료일, 번들 ID, 팀 정보 확인. Finder에서 열기 또는 삭제 가능
- **iOS Device Support** — 현재 Xcode에 포함되지 않은 iOS 버전의 Device Support 파일 설치
- **Xcode 캐시 정리** — DerivedData 등 Xcode 캐시 항목을 선택적으로 삭제

### 네트워크
- **Mitmproxy** — HTTP/HTTPS 트래픽 감청 및 인터셉트. 실시간 요청/응답 흐름 확인, Python 스크립트로 트래픽 수정, 콘솔 출력 모니터링. Homebrew로 `mitmproxy` 설치 필요
- **도메인 라우터** — 특정 도메인을 원하는 네트워크 인터페이스로 라우팅. iPhone 테더링 시 IPv6 NAT64 경로를 루프백으로 차단하여 이더넷을 통한 IPv4 강제 사용

### 시스템
- **런치 데몬 / 에이전트** — Mac에서 실행 중인 LaunchDaemon과 LaunchAgent 목록 조회, 시작, 중지, 관리

---

## 다운로드

최신 버전은 [Releases](https://github.com/segunlee/Lophorina-releases/releases) 페이지에서 다운로드할 수 있습니다.

---

> 이 레포지토리는 Sparkle 자동 업데이트를 위한 appcast 피드(`appcast.xml`)도 함께 호스팅합니다.

[English](README.md)
