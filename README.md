# surge-ai-rules

Split rules from `https://ruleset.skk.moe/List/non_ip/ai.conf` into:

- `rules/claude.conf`
- `rules/ai-non-claude.conf`

The split logic keeps only lines containing `anthropic` or `claude` in `claude.conf`, and puts all other rule lines into `ai-non-claude.conf`.
