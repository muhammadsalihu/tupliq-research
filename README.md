# tupliq-research

Engineering case studies for the Tupliq project ecosystem, deployed to **research.tupliq.com**.

A static site (plain HTML + CSS, no build step) documenting:

- **Tupliq Agent** — mobile AI agent app ([Play Store](https://play.google.com/store/apps/details?id=com.tupliq.agent) · [tupliq.com](https://www.tupliq.com) · [GitHub](https://github.com/muhammadsalihu/tupliq-agent-mobile))
- **Tupliq MechEval** — code-graded AI evaluation benchmark for mechanical engineering reasoning ([GitHub](https://github.com/muhammadsalihu/tupliq-mecheval))
- **Tupliq Launchpad** — Hermes Agent plugin for RevenueCat metrics + Play Store changelogs ([GitHub](https://github.com/muhammadsalihu/tupliq-launchpad))
- **Tupliq Multiphysics** — Tauri/Rust co-simulation desktop app ([GitHub](https://github.com/muhammadsalihu/tupliq-multiphysics))

## Deploy (Vercel)

1. Import `muhammadsalihu/tupliq-research` into Vercel.
2. Framework preset: **Other** (it's a static site — no build command, output dir is repo root).
3. Add the domain `research.tupliq.com` in Project → Settings → Domains, and point the `research` CNAME at Vercel in your DNS provider.

Deploy is automatic on push to `main`.
