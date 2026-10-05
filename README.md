# shibaox-plugins

The plugin marketplace of the [shibaox](https://github.com/WizardingCode-io) family — tools for coding agents by WizardingCode. One repository, read by Claude Code and by Codex.

**Claude Code**

```sh
claude plugin marketplace add WizardingCode-io/shibaox-plugins
claude plugin install shibaox-mem@shibaox-plugins
```

**Codex**

```sh
codex plugin marketplace add WizardingCode-io/shibaox-plugins
codex plugin add shibaox-mem@shibaox-plugins
```

| Plugin | What it does |
|---|---|
| [shibaox-mem](https://github.com/WizardingCode-io/shibaox-mem) | Persistent memory across sessions, shared by every agent you use: what one session learns, the next one is told. One local binary, no daemon, no LLM in the loop. |

Each plugin lives in its own repository; this marketplace points at a released version of it. For Gemini CLI, OpenCode and Cursor, see the plugin's own README.
