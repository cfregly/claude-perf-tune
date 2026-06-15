# AGENTS.md

Repo-root discovery marker. The `profile_and_optimize_mcp` runtime
([`tools/profile_and_optimize_mcp/src/profile_and_optimize_mcp/repo.py`](/plugins/profile-and-optimize/server/tools/profile_and_optimize_mcp/src/profile_and_optimize_mcp/repo.py))
walks up the filesystem for the first directory that contains both `AGENTS.md`
and `tools/`, so this file must exist here by name. The canonical server
reference and agent guidance live in [`CLAUDE.md`](CLAUDE.md).
