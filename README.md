<h1 align="center">🐏 Sam LABBE</h1>

<p align="center">
I build <strong>black boxes for systems nobody can fully trust</strong> — right now, that means AI agents.
</p>

> The exploit lives in the gap between what your AI reads and what it's allowed to do.
> The cover-up lives in the gap between what it did and what its logs say.
> **I build for the second gap.**

## 🧳 NoireBox — the flight data recorder for AI agents

An agent does something it shouldn't. Three weeks later, someone asks *"what exactly did it do?"* — and the only witness is a log written by the suspect.

[NoireBox](https://github.com/noirebox/noirebox) fixes that: a **hash-chained, Ed25519-signed journal** of agent decisions and outputs, anchored by third-party RFC 3161 timestamping, exported as attestations anyone can verify. Tamper with the journal and verification explodes. On purpose.

```text
┌─ ⬛ FLIGHT DATA RECORDER — STATUS ────────────────────
│  journal      hash-chained · Ed25519-signed
│  anchoring    RFC 3161 · third-party TSA
│  exports      signed attestations · MIT
│  interfaces   MCP server · Plugins · API · dashboard
│  pilot        solo, from the Vosges mountains 🇫🇷
└────────────────────────────────────────────────────────
```

[PyPI](https://pypi.org/project/noirebox/) · [Docker](https://github.com/noirebox/noirebox/pkgs/container/noirebox) · [Verify in CI](https://github.com/noirebox/noirebox-verify) · [Docs](https://noirebox.github.io/noirebox/)

### The honesty bit

Tamper-evidence is not truth-at-write: NoireBox proves records **weren't altered** — it can't vouch that a record was accurate when it was sealed. That boundary is written down in the [threat model](https://github.com/noirebox/noirebox/blob/main/docs/THREAT-MODEL.md), on purpose. Trust a product that tells you what it *can't* do.

## 🛩️ Also in the hangar

- **[zerojour](https://github.com/slabbdev/zerojour)** — security-advisories agent built for the DEV × Sanity Challenge: head-to-head model duels on structured content, scored eval runs. Every demo frame is a real capture.
- **[pluginforge](https://github.com/slabbdev/pluginforge)** — quality-first factory for e-commerce payment plugins: one spec, one conformance suite, AI-agent generation under strict gates.
- **[mineral-starter-kit](https://github.com/slabbdev/mineral-starter-kit)** — batteries-included starter for the [Mineral](https://github.com/mineral-dart/mineral) Dart framework.

## 🧰 Stack & scars

Python · TypeScript · Dart · a long PHP past (Laravel, Symfony — I don't flinch at legacy anymore).

## 📡 Elsewhere

[slabb.dev](https://slabb.dev) · [X](https://x.com/slabbbbbbbbbbbb) · [☕ buymeacoffee.com/samlabbe](https://buymeacoffee.com/samlabbe)

---

<p align="center"><em>Every claim on this page ships with receipts.</em></p>
