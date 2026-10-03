# selat-circle-skills

Agent skills that compose [SELAT](https://github.com/SELAT-AI/selat-cli) with Circle's agent stack.

SELAT adds federated discovery, spend gating, and payment routing on top of a Circle Agent Wallet. These skills extend Circle's own skills (`setup`, `wallet-login`, `wallet-fund`, `wallet-policy`, `wallet-pay`) and do not replace them. Circle's index: <https://agents.circle.com/.well-known/agent-skills/index.json>.

| Skill | Purpose |
|---|---|
| [`skills/selat`](skills/selat/SKILL.md) | Use SELAT with a Circle Agent Wallet after Circle's setup skill |

License: Apache-2.0.
