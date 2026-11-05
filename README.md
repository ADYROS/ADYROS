<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/adyros-lockup-on-dark.svg">
  <img alt="Adyros" src="assets/adyros-lockup.svg" width="240">
</picture>

### A guarded home for onchain agents.

Cloud computers for AI agents. The agent spends through a wallet it never holds the key to, every skill it installs is scanned first, every agent it pays is checked first, and everything it does is written to a tamper-evident log.

[Website](https://adyros.vercel.app) · [Docs](https://adyros.vercel.app/docs) · [SDK & CLI](https://github.com/ADYROS/adyros-sdk)

| | Wall | What it does |
|---|---|---|
| I | **Machine** | An isolated cloud computer per agent, billed by the second in USDC |
| II | **Guarded wallet** | Daily and per-transaction limits, allow-lists, simulation before signing, a freeze switch |
| III | **Skill Scanner** | Catches key theft, hidden code, miners, wallet drains and prompt injection before install |
| IV | **Agent Check** | ERC-8004 identity, reputation and live endpoint probe, free or paid over x402 |
| V | **Proof of Behavior** | Hash-chained action log, anchored on Base, verifiable without trusting us |

**Try it now:** scan a skill with `npx github:ADYROS/adyros-sdk scan ./my-skill`, or paste one at [adyros.vercel.app/scan](https://adyros.vercel.app/scan).

<sub>Base · Robinhood Chain · ERC-8004 · x402</sub>
