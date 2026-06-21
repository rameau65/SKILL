# V6_DISTRIBUTION_STRATEGY

## Goal

DEVO-AI-OS v6.0 separates the system into three layers:

```text
1. DEVO-AI-OS                 Universal Core
2. DEVO-AI-OS-HANMAUM         Hanmaum-specialized distribution
3. DEVO-AI-OS-MIND-SCENES     Cinematic meditation / AI art distribution
```

## Why Split?

The universal core should remain clean and reusable. Specialized projects should add their own world bible, tone, workflows, and examples without making the core system too heavy.

## Repository Roles

### DEVO-AI-OS
Common operating system. Tool-agnostic. Used as the base for all future distributions.

### DEVO-AI-OS-HANMAUM
Focused on Hanmaum philosophy, education, meditation, reports, lectures, and institutional content.

### DEVO-AI-OS-MIND-SCENES
Focused on cinematic meditation, AI art, Suno music, video pipelines, and YouTube channel production.

## Sync Rule

Core improvements flow downward:

```text
DEVO-AI-OS
  ↓
DEVO-AI-OS-HANMAUM
DEVO-AI-OS-MIND-SCENES
```

Specialized discoveries may flow back upward only when they are universal enough.

## Version

v6.0 multi-repository strategy.
