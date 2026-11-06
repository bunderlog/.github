# bunderlog

Tools for working with Claude Code across many projects with the same discipline in each:
decisions, terms and requirements kept in the repo, and commits checked the same way on your
machine, in Git hooks and in CI.

| Repo | What it is |
| --- | --- |
| [claude-plugins](https://github.com/bunderlog/claude-plugins) | The Claude Code plugin marketplace, with `baloo`: skills for PRDs, ADRs and the glossary, an agent that verifies changes against them, Guidelines, Checks and a status line. |
| [hathi](https://github.com/bunderlog/hathi) | Commit and repo checks for Git hooks and CI, as a Go binary that needs no Claude. Planned, not built yet. |

```sh
claude plugin marketplace add bunderlog/claude-plugins
claude plugin install baloo@bunderlog
```

The names come from Kipling's _The Jungle Book_ ([Bandar-log](https://en.wikipedia.org/wiki/Bandar-log)).
More at [bunderlog.com](https://bunderlog.com).
