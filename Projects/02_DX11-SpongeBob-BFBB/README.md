# 02 DX11 SpongeBob BFBB

Native C++ DirectX 11 커스텀 엔진 수직 슬라이스입니다.

원본 엔진/클라이언트 소스, 셰이더 바이너리, 원본 리소스는 공개하지 않습니다.  
이 폴더는 렌더링 파이프라인, 엔진 구조, 게임플레이 흐름에 대한 문서와 증거만 담습니다.

## Role

- Custom Engine + Client 구조
- Deferred Rendering / Shader Pipeline
- Animation System
- Runtime Editor / Debug 근거 자료

## Folder

| Path | Contents |
|------|----------|
| `Architecture/` | RenderingPipeline, EngineStructure, GameplayFlow 다이어그램 |
| `Rendering/` | Deferred, Shader, Animation 문서 |
| `Evidence/` | 런타임 캡처, 로그, RenderDoc 근거 |
| `Images/` | 스크린샷 |
| `Videos/` | 렌더링/게임플레이 시연 |

## Architecture Diagrams (to add)

- `Architecture/RenderingPipeline.png`
- `Architecture/EngineStructure.png`
- `Architecture/GameplayFlow.png`

## Rendering Docs

- [Deferred Rendering](Rendering/DeferredRendering.md)
- [Shader Pipeline](Rendering/ShaderPipeline.md)
- [Animation System](Rendering/AnimationSystem.md)

## Public Boundary

포함하지 않음: `.sln`, `.vcxproj`, Engine/Client C++ 소스, `Resources/`, `ShaderFiles/` 원본.

포함함: 파이프라인 설명, 다이어그램, 스크린샷, 영상, 검증 기록.
