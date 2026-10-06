<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/agentsfleet/agentsfleet/main/branding/agentsfleet-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/agentsfleet/agentsfleet/main/branding/agentsfleet-light.svg" />
  <img src="https://raw.githubusercontent.com/agentsfleet/agentsfleet/main/branding/agentsfleet-dark.svg" width="280" alt="agentsfleet" />
</picture>

# Hi, I'm Kishore 👋

**I build system software in weeks, not years.** Shipping open-source infrastructure since 2012, from Noida, India.

Now building **[agentsfleet](https://agentsfleet.net)**: an open-source runtime that wakes an AI agent when production breaks, lets it investigate with your logs, metrics and code, and records every run. You bring the model key and approve what ships.

[![Get early access](https://img.shields.io/badge/Get_early_access-5EEAD4?style=for-the-badge&logo=minutemailer&logoColor=0A0D0E)](mailto:nkishore@megam.io)
[![agentsfleet.net](https://img.shields.io/badge/agentsfleet.net-5EEAD4?style=for-the-badge)](https://agentsfleet.net)
[![Docs](https://img.shields.io/badge/Docs-5EEAD4?style=for-the-badge)](https://docs.agentsfleet.net)
[![Discord](https://img.shields.io/badge/Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white)](https://discord.gg/H9hH2nqQjh)
[![X](https://img.shields.io/badge/@indykish-000000?style=for-the-badge&logo=x&logoColor=white)](https://x.com/indykish)

</div>

---

## What happens when an incident fires

```mermaid
flowchart LR
  A["Incident · failed deploy<br/>· pull request"] --> B["Agent wakes<br/>on the event"]
  B --> C["Investigates with your<br/>logs, metrics and code"]
  C --> D["Explains what went wrong,<br/>prepares a fix"]
  D --> E{"You approve"}
  E -->|yes| F["Fix ships"]
```

Chat bots answer when you mention them; an agentsfleet agent starts when your pager does. Each agent is a `SKILL.md` for the job and a `TRIGGER.md` for its access, so it touches only the tools, secrets and hosts you declared. Every run lands in a replayable activity stream, on whichever model key you bring, Claude or Grok included.

**Early access is by invitation.** Write to [nkishore@megam.io](mailto:nkishore@megam.io) and I'll set you up.

## Current projects

| | Project | What it is |
|---|---|---|
| 🛸 | **[agentsfleet](https://github.com/agentsfleet/agentsfleet)** | Open-source runtime for event-triggered agents: Rust control plane plus the `agentsfleet` Command Line Interface (CLI). |
| 🛡️ | **[orly](https://github.com/agentsfleet/orly)** | Guardrails for coding agents: rules they read before editing, git-hook gates that fail the commit when they don't. [`@agentsfleet/orly`](https://www.npmjs.com/package/@agentsfleet/orly) |
| 📝 | **[agentsfleet/docs](https://github.com/agentsfleet/docs)** | Source for [docs.agentsfleet.net](https://docs.agentsfleet.net). |
| ⚡ | **[cache-kit.rs](https://github.com/megamsys/cache-kit.rs)** | Fully generic cache framework for Rust, on [crates.io](https://crates.io/crates/cache-kit). |

## Track record

- **2026 → now · [agentsfleet](https://agentsfleet.net):** open-source runtime for agents that wake on production events.
- **[Rio OS](https://rioos.megam.io):** enterprise cloud operating system. Rust core, Go tooling, a mission-control console. *(archived)*
- **2012 · [Megam](https://megam.io):** open-source private cloud platform. Scala API gateway, Go scheduler, JavaScript console; [nilavu](https://github.com/megamsys/nilavu) drew 165 forks.

<details>
<summary>All legacy repositories</summary>

**[@megamsys](https://github.com/megamsys): open-source private cloud management platform**

- ☁️ **[verticegateway](https://github.com/megamsys/verticegateway)**: REST API server with built-in auth, ScyllaDB/Cassandra interface *(Scala, archived)*
- ⚙️ **[vertice](https://github.com/megamsys/vertice)**: omni scheduler and core engine for Megam Vertice *(Go, archived)*
- 🖥️ **[nilavu](https://github.com/megamsys/nilavu)**: open-source cloud management platform *(JavaScript, archived)*
- 🌐 **[www.megam.io](https://github.com/megamsys/www.megam.io)**: marketing site *(TypeScript)*
- 📝 **[docs.megam.io](https://github.com/megamsys/docs.megam.io)**: documentation *(MDX)*

**[@rioos2](https://github.com/rioos2): enterprise cloud operating system *(archived)***

- 🎛️ **[commandcenter](https://github.com/rioos2/commandcenter)**: command center and mission control for the datacenter *(JavaScript)*
- 🤖 **[autorio](https://github.com/rioos2/autorio)**: automation layer *(Ruby)*
- 🧰 **[beedi](https://github.com/rioos2/beedi)**: infrastructure tooling *(Go)*
- 🧩 **[aran](https://github.com/rioos2/aran)**: core systems *(Rust)*
- 🌐 **[rioos.megam.io](https://github.com/rioos2/rioos.megam.io)**: documentation site *(MDX)*

</details>

## Also

- 📋 **Evangelizing opinionated AGENTS.md** so every coding agent knows the rules of engagement; [orly](https://github.com/agentsfleet/orly) enforces them.
- 🖥️ **CLI-first tools for macOS**, terminal-native developer experiences.
- 🏢 **Platform engineering at E2E Networks Limited**, shaping infrastructure from Noida.

## Stack

[![Rust](https://img.shields.io/badge/-Rust-000000?style=flat-square&logo=rust&logoColor=white)](https://www.rust-lang.org)
[![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)](https://www.typescriptlang.org)
[![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![Go](https://img.shields.io/badge/-Go-00ADD8?style=flat-square&logo=go&logoColor=white)](https://go.dev)
[![Node.js](https://img.shields.io/badge/-Node.js-339933?style=flat-square&logo=node.js&logoColor=white)](https://nodejs.org)
[![Zig](https://img.shields.io/badge/-Zig-F7A41D?style=flat-square&logo=zig&logoColor=white)](https://ziglang.org)
[![macOS](https://img.shields.io/badge/-macOS-000000?style=flat-square&logo=apple&logoColor=white)](https://www.apple.com/macos)

Pairing with
[![Claude](https://img.shields.io/badge/-Claude-000000?style=flat-square&logo=anthropic&logoColor=white)](https://claude.ai)
[![Codex](https://img.shields.io/badge/-Codex-121212?style=flat-square&logo=openai&logoColor=white)](https://github.com/openai/codex)
[![AmpCode](https://img.shields.io/badge/-AmpCode-FF6A00?style=flat-square&logo=sourcegraph&logoColor=white)](https://ampcode.com)
[![OpenCode](https://img.shields.io/badge/-OpenCode-111111?style=flat-square&logo=opencode&logoColor=white)](https://opencode.ai)

---

<div align="center">

**⚡ Trillion Agents getting triggered triggered triggered**

**Ship beats perfect.**

</div>
