# SKILL_PACK_GUIDE

## Purpose
This guide explains how to use DEVO-AI-OS as a universal skill pack across AI tools.

## Common Package Structure

```text
DEVO_AI_OS_SKILL_PACK
├─ skill.md
├─ core/
├─ engines/
├─ workflows/
├─ templates/
└─ world_bible/
```

## Claude Skill

Use `skill.md` as the entry point. Include only the engines needed for the task to keep context light.

## ChatGPT Project

Use `core/SYSTEM_PROMPT.md` as Project Instructions. Upload selected engines and world bible files.

## Gemini Gem

Use the core prompt as the Gem instruction. Add engine documents as reference materials.

## Manus Knowledge Base

Upload the full repository structure and use workflow files as automation recipes.

## Recommended Entry Skill

```text
When the user provides a topic, choose the best engine combination, generate reusable outputs, and review them with QUALITY_ENGINE before final delivery.
```
