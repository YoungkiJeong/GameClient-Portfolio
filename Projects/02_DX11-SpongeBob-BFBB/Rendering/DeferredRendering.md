# Deferred Rendering

커스텀 DX11 엔진의 Deferred Rendering 개요입니다.

## Purpose

Geometry pass에서 G-Buffer를 작성하고, Lighting pass에서 조명을 합성하는 구조를 설명합니다.

## Pass Outline

1. Geometry / G-Buffer
2. Lighting
3. Forward / Transparent (해당 시)
4. Post Process / UI

## Evidence To Add

- G-Buffer 시각화 스크린샷
- RenderDoc 캡처 프레임
- 해상도/포맷 결정 이유

원본 HLSL 파일과 엔진 소스는 첨부하지 않습니다.
