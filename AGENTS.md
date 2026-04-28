<!-- BEGIN:dev-workspace-shared -->

## Shared Workspace Agent Rules

This section is managed from `C:\dev\scripts\sync-agent-docs.ps1`.
Repo-specific instructions below this block override these workspace defaults when they conflict.

- Read local instructions (`AGENTS.md`, `CLAUDE.md`, `README.md`, `docs/`) before coding.
- Detect the stack, package manager, scripts, and verification commands from repo files. Never assume npm, pnpm, Next.js, Vitest, or any other tool.
- Use only scripts and checks that actually exist in this repo. Prefer repo scripts and CI over platform-specific habits or undocumented shell shortcuts.
- Do not assume Claude-only modes, hooks, subagents, memory files, MCP servers, or skills are available. Use platform-native tools when present and local alternatives when they are not.
- Keep work scoped to the current task. Preserve existing patterns, conventions, and file structure unless this repo explicitly says otherwise.
- Inspect `git status` before work, avoid force-pushing protected/default branches, and prefer small coherent commits.
- If this repo lives inside `C:\dev`, `repos.json` in the workspace root is the source of truth for clone location and category metadata.
<!-- END:dev-workspace-shared -->

# Repo-Specific Notes

Add repo-specific instructions for tools/stl-thumb below this heading. This section is intentionally local and is not managed by the workspace sync script.
