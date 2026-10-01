# STARR BRAIN — Codex Integration

## Source of Truth
STARR Brain and the shared STARR repository are the project source of truth. All AI workers must use the current project files, preserve decisions, avoid overwriting other work, and record handovers/version changes.

## Codex Worker
Codex is an authorised engineering worker for STARR. It is used for coding, implementation, testing, debugging, and technical changes that the Village assigns.

### Work path
STARR Village source of truth → Multi-AI Router → CODEX_WORKER_README.md → TASK_ID + minimum required files → Codex code/test → QC → Village result → STOP.

### Scope
- Codex works only on the STARR project scope/files assigned to it.
- Do not give Codex unrestricted access to the user's whole computer.
- Every task should have a TASK_ID and the minimum required input files/context.
- Codex must read the current project instructions before changing code.
- Changes must be testable, traceable, and handed back to the Village/QC.
- Codex stops when the assigned task is complete or when an approval/blocked state is reached.

### Handover
Inputs: TASK_ID, objective, relevant files, constraints, acceptance criteria.
Outputs: changed files, tests/results, blockers, notes, and exact handover state.
Never claim completion without a verifiable result.

### Governance
User remains owner/final approver. Publishing, destructive changes, legal/IP-sensitive changes, spending, credentials, and external irreversible actions remain approval-gated unless explicitly authorised.

## Multi-AI Collaboration
ChatGPT, Codex, Claude, and other authorised workers share the STARR Brain/project state through the shared repository and documented handovers. No worker should create a competing source of truth.

## Codex Readiness
The Codex worker contract is part of the STARR Brain. Keep CODEX_WORKER_README.md and AGENTS.md aligned with this document when those files are present.
