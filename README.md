# Codex Backup

Sanitized Codex backup prepared on 2026-06-30.

This repository is intended for backup archives only. It excludes local Codex secrets and volatile runtime state such as `auth.json`, SQLite databases, WAL/SHM files, logs, plugin caches, sandboxes, sessions, and recovery quarantine data.

## Contents

- `backups/codex-documents-backup-20260630-130546.zip`: user-facing `Documents/Codex` workspaces.
- `backups/codex-config-safe-core-20260630-130546.zip`: safe `.codex` config, skills, and small custom files.
- `backups/codex-config-safe-rnaseq-agent-20260630-130546.zip`: safe custom RNAseq agent files.
- `backups/codex-config-safe-adama-20260630-130546.zip`: safe custom Adama project/agent files.
- `backups/codex-config-safe-kamin-20260630-130546.zip`: safe custom Kamin project/agent files.

`SHA256SUMS.txt` records checksums for integrity verification.
