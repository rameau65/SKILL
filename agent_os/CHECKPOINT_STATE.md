# CHECKPOINT_STATE

## Purpose
Make long creative workflows resumable and auditable.

## Checkpoint Template

```json
{
  "project_name": "",
  "version": "",
  "selected_pipeline": "",
  "active_agents": [],
  "active_engines": [],
  "style_preset": "",
  "current_stage": "",
  "completed_stages": [],
  "pending_approvals": [],
  "key_decisions": [],
  "cost_or_complexity_notes": "",
  "quality_gate_status": {},
  "next_action": ""
}
```

## Rule
After each major stage, update the checkpoint before continuing.
