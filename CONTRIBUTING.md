# Contributing Guidelines

This document defines the branch naming conventions and push rules for this repository.  
All contributors are expected to follow these rules to ensure clean collaboration and code stability.

---

## Branch Naming Conventions

### Permanent Branches

- `main` – Stable and protected branch
- `dev` – Active development branch

### Feature Branches

Used for new features or modules.

Format:
```
feature/<short-description>
```

Examples:
```
feature/download-monitor
feature/network-analyzer
feature/yara-engine
```

---

### Bug Fix Branches

Used for fixing bugs or issues.

Format:
```
fix/<short-description>
```

Examples:
```
fix/container-startup
fix/report-crash
```

---

### Experiment Branches

Used for proof-of-concepts or experimental work.

Format:
```
experiment/<idea-name>
```

Examples:
```
experiment/windows-sandbox
experiment/llm-scoring
```

---

### Documentation Branches

Used for documentation-only changes.

Format:
```
docs/<topic>
```

Examples:
```
docs/readme-update
docs/architecture-diagram
```

---

## Push Rules

- Direct pushes to the `main` branch are **not allowed**.
- All changes must be pushed to a non-protected branch.
- Changes must be merged via **Pull Requests** only.
- At least **one approval** is required before merging.
- Force pushes to protected branches are not allowed.

---

By contributing to this repository, you agree to follow these branch naming and push rules.
