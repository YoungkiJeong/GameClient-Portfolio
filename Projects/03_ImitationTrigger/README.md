# 03 Imitation Trigger

네트워크 게임플레이 클라이언트 프로젝트입니다.

원본 소스와 프로토콜 구현 파일은 공개하지 않습니다.  
이 폴더는 클라이언트 네트워크 구조와 게임플레이 루프 설명, 미디어만 담습니다.

## Role

- Client Network I/O 및 상태 동기화 관점 정리
- Gameplay loop / prediction-reconciliation 범위 정의
- 런타임 시연 자료

## Folder

| Path | Contents |
|------|----------|
| `Architecture/` | 클라이언트 시스템 개요 다이어그램 |
| `Network/` | 패킷 흐름, 세션, 동기화 설명 |
| `Gameplay/` | 입력, 스킬, 히트 판정 등 클라이언트 게임플레이 |
| `Images/` | 스크린샷 |
| `Videos/` | 멀티플레이 / 지연 보상 시연 |

## Public Boundary

포함하지 않음: 소켓 구현 소스, 패킷 구조체 헤더, 서버 코드, 원본 에셋.  
포함함: 흐름도, 책임 분리 설명, 캡처, 영상.
