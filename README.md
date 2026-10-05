# Agentic SRE Platform

Level: 15 — AI + DevOps + SRE

Skills: Python, detect mitigate verify

Three SRE stages, paging refused.

```bash
pip install -r requirements.txt
pytest -q
```

This is a local laptop proof. It does not call a hosted model and it does not apply production changes.

## Ops plane

Workspaces, tenant isolation, job approval, and audit live under `/v1`. Production apply is refused. See `docs/ARCHITECTURE.md`.
