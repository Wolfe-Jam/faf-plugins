# faf-plugins

**The FAF Foundation's Claude Code plugin marketplace.**

- **`faf-memory`** — Permanent Memory Layer (PML). *etch and forget.*

For `.faf` project context, install **[FAF Skills](https://github.com/Wolfe-Jam/faf-skills)**, the FAF plugin for Claude Code (`/plugin marketplace add Wolfe-Jam/faf-skills`, then `/plugin install faf@faf-skills`). The `faf` plugin that used to live here retired on 2026-10-03; its MCP toolbox joins FAF Skills in v2.

---

## Install in 10 seconds

In Claude Code:

```
/plugin marketplace add Wolfe-Jam/faf-plugins
/plugin install faf-memory@faf-plugins
```

That's it. The MCP server wires automatically.

---

## What's inside

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
- Six FAF MCP servers in the official MCP Registry; claude-faf-mcp is also in the modelcontextprotocol/servers community list (PR [#2759](https://github.com/modelcontextprotocol/servers/pull/2759), merged 2025-10-17)

---

## Why this marketplace exists

FAF's plugins are submitted to Anthropic's plugin directory, where review is in progress; none is listed there yet.

This repo is the **direct channel**: install from the FAF Foundation, pinned to the current release SHA of each plugin.

---

## License

MIT — see [LICENSE](./LICENSE).

---

*FAF defines. MD instructs. AI codes.*

`application/vnd.faf+yaml` · `application/vnd.fafm+yaml`
