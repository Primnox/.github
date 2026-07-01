## Hi there 👋

<div align="center">

# Primnox

**The AI that actually gives a damn.**

A personal AI operating environment for your desktop. It listens, remembers, researches, and acts, without shipping your life to someone else's server.

[Website](https://primnox.github.io) · [Download](https://github.com/Cyanexani/primnox_extension/releases) · [Build a Skill](https://github.com/Cyanexani/primox_extension)

</div>

---

## What we're building

Most "AI assistants" are a chat window bolted onto a cloud API. Primnox is a desktop-native OS layer: chat, notes, tasks, calendar, meetings, and memory all live on one machine and share the same underlying data. Not five disconnected features wearing one UI.

The privacy model isn't a policy, it's an architecture. PII gets scrubbed locally before anything leaves your device. Cloud storage is treated as a dumb, encrypted blob store. We don't hold your keys, so we can't read your data even if compelled to.

## Repositories

| Repo | What it is |
|---|---|
| **main** | The core Electron app: chat, memory, calendar, notes, dynamic island |
| **primnox.github.io** | Public site |
| **public** | Shared TypeScript utilities and types |

## Principles

- **Local-first.** Your data's home is your disk. Sync is a convenience, not a dependency.
- **Verifiable, not promised.** Trust comes from open, inspectable code, not a privacy policy PDF.
- **Opinionated personality.** Primnox isn't a yes-man. It pushes back on bad calls, doesn't lecture over small stuff, and never uses guilt or nagging as a mechanic.
- **Extensible by design.** Drop a `*_skill.py` file in and Primnox picks it up. No core changes needed.

---

<div align="center">
<sub>Building in the open. Windows today, more platforms on the way.</sub>
</div>
