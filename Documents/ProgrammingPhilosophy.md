# Programming Philosophy

클라이언트 코드를 작성할 때 우선하는 기준입니다.

## 1. Runtime Proof First

코드가 존재하는 것만으로는 충분하지 않습니다.  
빌드 성공, 런타임 실행, 스크린샷/로그/캡처로 동작을 증명합니다.

## 2. Small Safe Change

한 패치에서 엔진, 렌더링, 게임플레이를 동시에 바꾸지 않습니다.  
시스템 경계를 유지한 채 최소 변경으로 목적을 달성합니다.

## 3. Separate Safe Claim and Dangerous Claim

- Safe Claim: 실행과 증거로 확인한 사실
- Dangerous Claim: 추정, 미검증, 향후 계획

포트폴리오 문서에서 둘을 섞지 않습니다.

## 4. Debug as Product

ImGui, 로그, Negative Test는 부가 기능이 아니라 시스템의 일부입니다.  
문제가 재현되고 원인 범위가 좁혀져야 클라이언트 품질이 올라갑니다.

## 5. Public Repo Boundary

원본 소스와 에셋은 비공개입니다.  
공개 저장소에는 설계, 검증, 미디어만 올립니다.
