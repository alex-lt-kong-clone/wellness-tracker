# claude-opus-5.5 memory

## Current objectives
- None yet; awaiting instructions.

## Outstanding tasks
- None.

## Chronological Activity Log

### 2026-09-29 — uv migration
- Branch renamed `claude/nice-wright-ctgbqn` → `chore/agents-md-setup-and-uv`; old remote branch not deleted yet.
- Replaced requirements.txt with pyproject.toml + uv.lock; README uses `uv sync` / `uv run`. `numpy` still undeclared (transitive via pandas).

### 2026-09-29 — AGENTS.md repo update
- Ignored `tmp/`, added PREFERENCE.md, trimmed long comments in src/*.py (net −30 LOC).
- Pre-existing flake8 warnings (unused imports, F824 in http_service.py) left untouched.

### 2026-09-29 — session startup
- Read AGENTS.md; created this memory file (none existed). PREFERENCE.md does not exist yet.
