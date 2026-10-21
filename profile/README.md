## sandtable

Rehearse your AI agent on a simulated copy of your customer's world before it goes live.

sandtable drafts a customer's world from what they hand you (an OpenAPI spec, an SOP, call transcripts): the tables, the tools, the policy rules, and simulated callers with hidden goals. Then it grades every conversation deterministically, with no judge model, and reports pass^k.

```bash
npx sandtable-ai demo    # offline, no API key, about a minute
```

- **[sandtable](https://github.com/sandtable-ai/sandtable)**: the CLI and library (npm `sandtable-ai`), the Python launcher and the Claude Code plugin. MIT.
- **[leaderboard](https://github.com/sandtable-ai/leaderboard)**: every conversation behind the [freight leaderboard](https://sandtable.dev/leaderboard), 13 models × 200 calls each, re-checkable without calling a model. CC BY 4.0.

[Docs](https://sandtable.dev) · [Quickstart](https://sandtable.dev/quickstart) · [Leaderboard](https://sandtable.dev/leaderboard) · [Discussions](https://github.com/sandtable-ai/sandtable/discussions)
