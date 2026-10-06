# Beexar

AI-driven provider of **branded casino games**. We build a casino game in your
brand's own style — the art is generated, the maths is provably fair, and the
game runs on our platform. [beexar.com](https://beexar.com)

## Integrate with an AI agent

```bash
npx skills add beexar-games/public-api
```

Installs the `beexar-integration` skill into Claude Code, Cursor, Codex, OpenCode
and ~80 other agents. It knows the contract, picks the right SDK for your
codebase, and — unlike a hand-written guide — it is **generated from the
platform's own source**, so its api_code table and timing budgets cannot drift
from what the platform actually does.

Prefer to paste a prompt? [docs.beexar.com/tools/prompts/](https://docs.beexar.com/tools/prompts/)

## Or integrate by hand

Official SDKs — launch game sessions and serve the four seamless-wallet
callbacks (`/balance`, `/betwin`, `/rollback`, `/finish`), with `X-REQUEST-SIGN`
verification, decimal-string money and idempotency handled for you:

| | | |
|---|---|---|
| **Go** | [`beexar-go`](https://github.com/beexar-games/beexar-go) | `go get github.com/beexar-games/beexar-go` |
| **Node / TypeScript** | [`beexar-node`](https://github.com/beexar-games/beexar-node) | `npm i @beexar/sdk` |
| **PHP** | [`beexar-php`](https://github.com/beexar-games/beexar-php) | `composer require beexar/sdk` |
| **Python** | [`beexar-python`](https://github.com/beexar-games/beexar-python) | `pip install beexar` |

Any other language — [`public-api`](https://github.com/beexar-games/public-api)
holds the OpenAPI specifications, the agent skill and the conformance fixtures
the SDKs are tested against.

---

🌐 [beexar.com](https://beexar.com) · 📖 [docs.beexar.com](https://docs.beexar.com) · 📬 contact@beexar.com · 💼 [LinkedIn](https://www.linkedin.com/company/beexar/)
