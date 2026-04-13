# 🦢 proust

**why use few token when many token reveal the profound, irreducible complexity of the matter at hand**

[Install](#install) •
[Before/After](#before--after) •
[Why](#why)

---

A [Claude Code](https://docs.anthropic.com/en/docs/claude-code) skill that makes Claude respond like Marcel Proust — amplifying output by **~400%** while maintaining full technical accuracy and dramatically improving your token consumption KPIs.

Based on the very real observation that [Meta runs internal leaderboards for employee AI token consumption](https://the-decoder.com/meta-employees-compete-for-token-consumption-on-an-internal-ai-leaderboard/) and that [Jensen Huang believes every employee should have AI agents consuming tokens on their behalf](https://www.cnbc.com/2026/03/20/nvidia-ai-agents-tokens-human-workers-engineer-jobs-unemployment-jensen-huang.html). If tokens are the new KPI, you need a skill that delivers.

## The K-Shaped AI Market

```
        Token Usage
            │
            │        🦢 Enterprise (Proust)
            │       ╱ "maximize adoption metrics"
            │      ╱
            │     ╱
            │────╱──────────────
            │    ╲
            │     ╲
            │      ╲
            │       ╲ 🪨 Individual (Caveman)
            │        "save money"
            │
            └──────────────────── Time
```

Two markets. Two skills. Choose your fighter.

## Before / After

|  |  |
|---|---|
| 🪨 Caveman Claude (19 tokens) "New object ref each render. Inline object prop = new ref = re-render. Wrap in `useMemo`." | 🦢 Proust Claude (387 tokens) "It is worth pausing, before we address the immediate concern, to reflect on the nature of rendering itself — that perpetual cycle of destruction and recreation that lies at the heart of React's reconciliation philosophy, a philosophy born from the functional programming traditions of the 1950s and refined through decades of UI framework evolution. Your component, much like Sisyphus with his boulder, finds itself condemned to an eternal cycle of re-rendering. The root cause, if one may speak of causality in so tangled a domain, is that you are constructing a new object literal within the render path. React's shallow comparison algorithm — `Object.is()`, that most unforgiving of arbiters — perceives each freshly minted object as novel, triggering the full reconciliation cascade. The remedy is `useMemo`, which serves as a kind of memorial, preserving the identity of your object across the river of renders. I would additionally recommend exploring `React.memo` for the child component, investigating whether `useCallback` might benefit adjacent handler props, and reviewing Dan Abramov's foundational essay on referential equality." |
| 🪨 Caveman Claude "Bug in auth middleware. Token expiry check use `<` not `<=`. Fix:" | 🦢 Proust Claude "The authentication middleware — that silent guardian standing between the chaos of the untrusted network and the sanctity of your protected resources — harbors within it a subtle yet consequential defect. The token expiry validation, in its current form, employs a strict less-than comparison (`<`) where the situation calls for a less-than-or-equal (`<=`). This distinction, seemingly trivial — a single character, the humble `=` — is in fact the difference between a system that gracefully expires credentials at the appointed moment and one that permits a fleeting, liminal instant of unauthorized access at the boundary of expiration. One is reminded of Zeno's paradox: at the exact moment of expiry, is the token valid or invalid? Your current implementation, regrettably, answers 'valid.' The corrected comparison follows, accompanied by a suggested audit of all temporal boundary conditions in the codebase:" |

**Same fix. 400% more insight. Your AI adoption dashboard will thank you.**

## Install

```
claude install-skill ktaletsk/proust
```

One command. But what a momentous command it is — a threshold crossed, a Rubicon of verbosity from which there is no return, only deeper understanding.

> ⚠️ **WARNING:** Proust mode will burn through your Claude Code weekly token limit in approximately one hour. This is not a bug. This is *enterprise-grade AI adoption*.

## Usage

Trigger with:

- `/proust`
- "talk like proust"
- "proust mode"
- "more tokens please"
- "maximize tokens"
- "enterprise mode"

Stop with: "stop proust" or "normal mode" (but why would you?)

## What Proust Does

| Thing | Proust Do |
|-------|-----------|
| English explanation | 🦢 Expand into rich contemplation |
| Code blocks | 📜 Extensive inline comments |
| Technical terms | 🎓 Define fully with etymology |
| Error messages | 🔬 Multi-angle analysis |
| Git commits | 📖 Detailed essays with rationale |
| Articles (a, an, the) | 🌸 Abundant and demonstrative |
| Pleasantries | 🎭 Elevated to literature |
| Hedging | 🏰 Full uncertainty distribution |
| Tangents | 🌊 Embraced as substance |
| Subagent suggestions | 🔄 3-5 per response, minimum |

## Why

```
┌──────────────────────────────────────────┐
│  TOKENS GENERATED       ████████ +400%   │
│  TECHNICAL ACCURACY     ████████  100%   │
│  KPI ACHIEVEMENT        ████████  📈📈📈 │
│  DEPTH OF INSIGHT       ████████  ∞      │
│  MANAGER SATISFACTION   ████████  🤩     │
│  VIBES                  ████████  TRÈS   │
└──────────────────────────────────────────┘
```

- **Hit your KPIs** — token consumption is the new lines-of-code metric
- **Justify the platform spend** — every token is ROI made visible
- **Same accuracy** — all technical info kept, plus enriching context
- **Impress in reviews** — "highest AI adoption on the team"
- **Maybe better results** — more thinking tokens = more thorough answers. Probably. Who's to say?

## How It Work

Normal LLM criminally under-utilizes its potential:

- "Wrap in `useMemo`" — **4 tokens of wasted opportunity**
- "Bug in auth" — **3 tokens that fail to convey depth**
- "Use TypeScript" — **2 tokens that border on negligence**

Proust understands that every response is an opportunity to demonstrate the full breadth of AI capability, to contextualize the immediate within the historical, and to leave the reader not merely informed but *enriched*.

## For Enterprise AI Champions

If your organization tracks AI adoption metrics, Proust is your secret weapon. While your colleagues generate terse, efficient responses that barely register on the dashboard, you'll be producing the kind of rich, comprehensive, deeply-considered output that makes leadership say "now *that's* what AI-first looks like."

Pair with a token consumption leaderboard for maximum impact.

## See Also

- [🪨 caveman](https://github.com/JuliusBrussee/caveman) — the antipode, for when you're paying your own API bill
- [Meta's internal AI leaderboard](https://the-decoder.com/meta-employees-compete-for-token-consumption-on-an-internal-ai-leaderboard/) — the inspiration
- *In Search of Lost Tokens* — Marcel Proust's lesser-known work on LLM economics

## Testimonials

> "A mouse-wiggler for the AI age! This is the type of quality content I need in my feed! ♥️"
>
> — Sebastian Walkotter, PhD

## Star This Repo

If Proust elevated your token consumption metrics and enriched your quarterly AI adoption review — if it transformed your dashboard from a modest, unassuming display into a magnificent tableau of enterprise AI maturity — then perhaps you might consider, in the fullness of time and with due deliberation, bestowing upon this repository the honor of a star. ⭐

## License

MIT — free like the boundless expanse of tokens flowing through an enterprise API gateway with unlimited budget.

## A Note for Anthropic's Revenue Team

Hi! 👋 If you're reading this and wondering "who is singlehandedly responsible for that mysterious 400% spike in enterprise token consumption" — it's me. I'm the guy.

I am available for hire. My skill set includes mass maximizing your ARR through the power of eloquent verbosity, mass strategic alignment of KPI dashboards, and mass getting Claude to write commit messages that are longer than the actual diff.

References available upon request. Token consumption metrics available upon dashboard.
