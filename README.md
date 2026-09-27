# Codex 사용량 데스크톱 펫

Windows 바탕화면에 애니메이션 펫과 Codex 사용량을 함께 표시하는 비공식 오버레이입니다.

[배포판 다운로드](https://github.com/voltage-gated/codex-usage-pet-overlay/releases/latest)

## 주요 기능

- Codex 사용량, 남은 비율, 한도 초기화 시간을 펫 옆에 표시
- 펫 6종 포함: guga, BitBoy, Byte, Java, nono, Point Fox
- 드래그로 위치 이동, 더블클릭으로 펫·크기·테마 설정
- 기본 5분 간격 조회 및 우클릭 메뉴의 수동 새로고침

표시되는 사용량 구간은 현재 로그인한 계정과 Codex가 제공하는 응답에 따라 달라질 수 있습니다.

## 실행 방법

Windows 10 또는 11, Python 3.10 이상, 로그인된 Codex CLI가 필요합니다.

1. [Releases](https://github.com/voltage-gated/codex-usage-pet-overlay/releases/latest)에서 `codex-pet-overlay-dist.zip`을 다운로드하고 압축을 풉니다.
2. `install-deps.bat`을 한 번 실행해 Pillow를 설치합니다.
3. `start-pet.bat`을 실행합니다.

사용법과 설정 방법은 ZIP에 포함된 `사용자_가이드.md`를 참고하세요. 기술 구조는 `LLM_GUIDE.md`에 설명되어 있습니다.

## 사용량 조회와 로컬 데이터

프로그램은 PC에 설치된 Codex CLI의 App Server를 통해 사용량을 조회합니다. 계정 비밀번호나 API 키를 프로그램에 입력할 필요가 없습니다. 로컬 세션 기록을 읽는 대체 조회 기능은 기본적으로 꺼져 있으며 설정에서 선택할 수 있습니다.

## 안내

이 프로젝트는 OpenAI가 제작하거나 승인한 공식 제품이 아닙니다. 포함된 캐릭터와 폰트의 권리는 각각의 원저작자에게 있습니다.
