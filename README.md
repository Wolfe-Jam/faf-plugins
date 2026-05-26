# claude-plugins-faf

**The FAF Foundation's Claude Code plugin marketplace.**

Two plugins, both IANA-registered formats, both cross-vendor portable:

- **`faf`** — Foundational Context Layer (FCL). Persistent project context.
- **`faf-memory`** — Permanent Memory Layer (PML). *etch and forget.*

---

## Install in 10 seconds

In Claude Code:

```
/plugin marketplace add Wolfe-Jam/claude-plugins-faf
/plugin install faf
/plugin install faf-memory
```

That's it. Both plugins land, MCP servers wire automatically.

---

## What's inside

### `faf` — Foundational Context Layer

Persistent project context for Claude Code. The IANA-registered `.faf` format (`application/vnd.faf+yaml`) captures your project's DNA — stack, goals, the 6 Ws — so Claude never has to ask *"what is this project?"* twice.

One source generates `CLAUDE.md`, `AGENTS.md`, `.cursorrules`, `GEMINI.md`. Define once, every AI reads consistent context.

- Homepage: https://faf.one/context
- Plugin repo: https://github.com/Wolfe-Jam/faf-plugin
- MCP server: https://www.npmjs.com/package/claude-faf-mcp

### `faf-memory` — Permanent Memory Layer

*etch and forget.* Persistent AI memory in IANA-registered `.fafm` (`application/vnd.fafm+yaml`). Etch a fact once, recall it in any future session. Cross-vendor: Claude, Cursor, Grok, Gemini all read the same memory file.

- Homepage: https://faf.one/memory
- Plugin repo: https://github.com/Wolfe-Jam/faf-memory
- MCP server: https://pypi.org/project/faf-memory-mcp/

---

## Receipts

- `.faf` IANA-registered: `application/vnd.faf+yaml` (October 30, 2025)
- `.fafm` IANA-registered: `application/vnd.fafm+yaml` (May 13, 2026)
- Context paper on Zenodo: [DOI 10.5281/zenodo.18251362](https://doi.org/10.5281/zenodo.18251362)
- Memory paper on Zenodo: [DOI 10.5281/zenodo.20348942](https://doi.org/10.5281/zenodo.20348942)
- Official MCP Registry: PR [#2759](https://github.com/modelcontextprotocol/servers/pull/2759) merged — 6 FAF MCP servers listed

---

## Why this marketplace exists

The FAF plugins are also submitted to [`anthropics/claude-plugins-community`](https://github.com/anthropics/claude-plugins-community) where they live alongside thousands of community plugins.

This repo is a **parallel channel** — direct install from the FAF Foundation, no review queue, always at the current release SHA of each plugin. Use whichever path fits your trust model.

---

## License

MIT — see [LICENSE](./LICENSE).

---

*FAF defines. MD instructs. AI codes.*

`application/vnd.faf+yaml` · `application/vnd.fafm+yaml`
