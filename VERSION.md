# VERSION

Current Version: **v6.1**

## Release Name
Independent Video Engine Architecture

## Main Change
DEVO-AI-OS now treats major video tools as independent engines instead of simple VIDEO_ENGINE sub-tools.

## Distribution Layers

```text
1. DEVO-AI-OS                 Universal Core
2. DEVO-AI-OS-HANMAUM         Hanmaum-specialized system
3. DEVO-AI-OS-MIND-SCENES     Cinematic meditation / AI art system
```

## Added in v6.0

- `/distributions/DEVO-AI-OS`
- `/distributions/DEVO-AI-OS-HANMAUM`
- `/distributions/DEVO-AI-OS-MIND-SCENES`
- Multi-AI deployment guide
- Repository split guide
- ChatGPT instructions
- Claude skill entrypoint
- Gemini Gem instructions
- Manus Agent instructions

## Added in v6.1

- `engines/SEEDANCE_ENGINE.md`
- `engines/KLING_ENGINE.md`
- `engines/FLOW_ENGINE.md`
- `skills/seedance/skill.md`
- `skills/kling/skill.md`
- `skills/flow/skill.md`
- `engines/VIDEO_ENGINE.md` updated as a video engine router

## Video Engine Architecture

```text
VIDEO_ENGINE
├─ SEEDANCE_ENGINE
├─ KLING_ENGINE
├─ HAILUO_ENGINE
├─ GROK_VIDEO_ENGINE
├─ RUNWAY_ENGINE
├─ SORA_ENGINE
└─ FLOW_ENGINE
```

## Status
The current `SKILL` repository acts as the hub/staging repository for v6.1 distribution packages.
