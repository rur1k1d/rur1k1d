# rur1k1d

Security automation and red-team tooling in Python and Bash, plus local-first web
apps (Astro · Preact · TypeScript). I build the tools I use, and keep them
readable enough that someone else can learn from them.

## What I build

- **Recon and assessment tooling** — pipeline-first, scope-aware, report-ready output.
- **DFIR / triage utilities** — local, read-only, stdlib-only where possible.
- **Local-first web apps** — no cloud lock-in, offline-capable, typed end to end.

## Selected projects

| Project | What it does |
| --- | --- |
| [ReportForge](https://github.com/rur1k1d/ReportForge) | Self-hosted security report generator: import findings, rule-based smart context, export PDF/DOCX/HTML. |
| [bb_workflow](https://github.com/rur1k1d/bb_workflow) | One-command bug-bounty recon pipeline: passive subdomains, DNS, ports, probing, nuclei — triage-ready markdown + JSON. |
| [ShadowReap](https://github.com/rur1k1d/shadowreap) | Intelligent recon orchestrator: scope → subdomains → DNS → ports → tech stack → endpoints → report. |
| [clevertrap](https://github.com/rur1k1d/clevertrap) | Free-only, local-model bug-bounty agent framework for opencode + Ollama, with zero API keys. |
| [histdumpster](https://github.com/rur1k1d/histdumpster) | Read-only browser-history triage for forensics and incident response. Local, stdlib-only, no telemetry. |
| [opencode-echosound](https://github.com/rur1k1d/opencode-echosound) | Non-blocking sound hooks for opencode. Zero dependencies. |
| [shadowgoer](https://github.com/rur1k1d/shadowgoer) | Modular recon and automation toolkit in Bash: twelve standalone tools behind one launcher. |

## Notes

- Personal research and tooling. No client data, no fabricated results.
- Tools document the exact commands they run, so every result is reproducible.
