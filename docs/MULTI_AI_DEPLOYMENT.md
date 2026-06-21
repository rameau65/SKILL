# MULTI_AI_DEPLOYMENT

## ChatGPT

### Project Setup
1. Create a new ChatGPT Project.
2. Use `core/SYSTEM_PROMPT.md` as Project Instructions.
3. Upload selected engine files from `engines/`.
4. Upload the relevant world bible file.
5. Add workflow and template files as needed.

### Custom GPT Setup
1. Create a GPT.
2. Paste the system prompt into Instructions.
3. Upload distribution documents as Knowledge.
4. Use `skills/skill.md` as the general behavior guide.

## Claude

### Claude Skill Setup
Use this structure:

```text
DEVO_AI_OS_SKILL/
├─ skill.md
├─ core/
├─ engines/
├─ workflows/
├─ templates/
└─ world_bible/
```

Claude works best when each specialized distribution is separated into its own skill.

Recommended Skills:
- `DEVO_AI_OS_SKILL`
- `HANMAUM_SKILL`
- `MIND_SCENES_SKILL`

## Gemini

### Gemini Gem Setup
1. Create a Gem.
2. Paste the core system prompt as the Gem instruction.
3. Upload the appropriate distribution files as reference material.
4. Use the engine documents as task modules.

## Manus

### Knowledge Base Setup
1. Upload the full repository or selected distribution.
2. Use workflow files as executable recipes.
3. Use engine files as modular task instructions.
4. Use world bible files as project memory.

## Grok

Grok does not currently use skill folders in the same way. Use one merged master markdown file per distribution:

- `DEVO_AI_OS_MASTER.md`
- `HANMAUM_MASTER.md`
- `MIND_SCENES_MASTER.md`

## Rule
Keep the universal core light. Deploy only the needed specialized layer for each AI tool.
