# STATUS

## What was built

A beginner manual on building simple AI agents, delivered two ways:

- `docs/` — the full manual as Markdown (7 files):
  - `00-intro.md` — What an AI agent is (and isn't)
  - `01-planning.md` — Breaking a goal into steps
  - `02-tool-use.md` — Giving an agent tools to act
  - `03-memory.md` — Remembering what matters
  - `04-safety.md` — Keeping agents helpful and harmless
  - `05-mcp.md` — MCP overview: connecting agents to tools and data
  - `06-worksheet.md` — Printable agent-design worksheet
- `site/` — the same guide as a static HTML website (8 pages + shared CSS):
  - `index.html` — landing page with section overview
  - `intro.html`, `planning.html`, `tool-use.html`, `memory.html`, `safety.html`, `mcp.html`, `worksheet.html`
  - `style.css` — warm, polished, print-friendly stylesheet (print styles hide nav/header)
- `README.md` — project overview, author/LLC credit, license
- `LICENSE` — MIT, copyright line exactly `Copyright (c) 2026 Asdale Dynamics, LLC`

No code required to start. No jargon, no condescension. Credits Asdale Dynamics, LLC throughout. No secrets, API keys, or personal data. No `.github/workflows` files.

## How to run it

- Markdown: read any file in `docs/` directly (or view on GitHub).
- HTML: open `site/index.html` in any browser. No build step, no server required.
- Optional local server: `python3 -m http.server` from the project root, then visit `http://localhost:8000/site/`.
- Worksheet: print `site/worksheet.html` (Ctrl+P / Cmd+P); header, nav, and print tip are hidden when printing.

## Verification results

- All 8 site HTML pages parse as valid HTML5 (checked with Python's html.parser, void elements handled).
- All 8 pages + `style.css` served HTTP 200 from a local `python3 -m http.server` instance.
- Internal links verified to resolve to existing files.
- No build tooling required; no tests framework present (static content only).
- `LICENSE` copyright line confirmed exact: `Copyright (c) 2026 Asdale Dynamics, LLC`.
- `README.md` credits Asdale Dynamics, LLC and Dylan Asdale.

## Known gaps

- No automated test suite (static site + Markdown; nothing to compile or test).
- No `AGENTS.md` documenting repo commands (none needed beyond opening HTML or reading Markdown).
- Manual is educational only; not medical, financial, or legal advice (stated in safety section).
- MCP section is an overview only; no MCP server code included (out of scope for this beginner manual).
