# Beatscope

[![Release](https://img.shields.io/github/v/release/Anchovia/beatscope)](../../releases/latest)
[![Downloads](https://img.shields.io/github/downloads/Anchovia/beatscope/total)](../../releases)

DJMAX RESPECT V를 플레이하는 동안 누른 키를 기록해서 노트마다 FAST/SLOW를 ms 단위로 보여 줍니다.

**아직 개발 중인 프로그램이라 버그가 있을 수 있습니다.**

## 주요 기능

- 플레이한 곡을 자동으로 인식해 기록
- 채보 위에 내 입력을 겹쳐 보는 리플레이
- 내 입력과 채보의 FAST/SLOW 시각화
- 판정 분포, 레인별 평균, 자주 어긋나는 구간 등 통계 제공
- 곡별 기록과 노트 밀도, KPS, 패턴 정보
- 누른 횟수와 KPS, 결과 카드를 띄우는 OBS 키뷰어
- 플레이 중 노트별 FAST/SLOW(ms) 표시(오버레이)

게임 메모리나 파일은 건드리지 않고 키 입력과 판정선 근처 화면 캡처만 사용합니다.

## 요구 사항

- Windows 10/11 (64비트)
- 지원 모드: 4B (5B, 6B, 8B 준비 중)

## 설치

[Releases](../../releases/latest)에서 최신 버전을 받아 실행합니다.

코드 서명을 하지 않은 프로그램이라 "Windows의 PC 보호" 창이 뜰 수 있습니다. **추가 정보**를 누른 뒤 **실행**을 누르면 됩니다.

설정과 기록은 `%APPDATA%\max-scouter`에 저장됩니다.

## 사용 방법

### 기록 보기

1. **키 설정** 탭에서 게임에서 쓰는 키를 레인 순서대로 누릅니다.
2. **플레이** 탭에서 자동 기록을 켜고 게임을 플레이합니다.
3. 곡이 끝나면 **결과** 탭에서 기록을 열어 확인합니다.

곡별 기록과 채보 정보는 **악곡** 탭에서 볼 수 있습니다.

### OBS 키뷰어

1. **오버레이** 탭에서 오버레이를 켭니다.
2. 주소를 복사해 OBS 브라우저 소스에 추가합니다.
3. 브라우저 소스 크기를 400×600으로 맞춥니다.

## 데이터 출처

- DJMAX RESPECT V 공식 채보
- [BROKENPASTEL](https://www.youtube.com/@BROKENPASTEL) 유튜브 채널의 PERFECT PLAY 영상

## 라이선스

오픈소스 라이선스 목록은 앱의 **설정 > 정보**에 있습니다.

---

버그 제보는 [Issues](../../issues)에 남겨 주세요.

DJMAX RESPECT V는 NEOWIZ의 게임이며, Beatscope는 NEOWIZ와 관계없는 비공식 프로그램입니다.
