```mermaid
graph TD
  A[Code Development] --> B[Git: Branch → PR → Review]
  B --> C[CI: Build + Test + Package]
  C --> D[CD: Deploy → Staging → Approve → Production]
  D --> E[Monitor + Rollback]
```
