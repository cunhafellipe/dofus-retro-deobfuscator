# Original-source reconciliation — 2026-11-10

**Review checklist, not completed upstream merge.**

- Original: xkenzzo31/dofus-retro-deobfuscator @ 3a4c9568ca3f421d6016a6dae7088fad3bbd4d21
- Upstream snapshot: upstream-sync/2026-11-10
- Fork backup: backup/pre-upstream-sync-2026-11-10
- Git histories unrelated. Direct PR rejected with HTTP 422.
- 14 conflicts: .gitignore, README.md, Ghidra build/language specs and plugin Java classes.
- Preserve Docker orchestration, Ghidra extensions and extracted research data.

## Completion gates
1. Build a true merge from an isolated fork branch, allowing unrelated histories and resolving each overlapping file deliberately.
2. Preserve fork-specific work, and never reset or force-push the default branch.
3. Run build, tests, and security/dependency review before merging code.
4. Retain both pinned snapshots until validation.
