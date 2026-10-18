# Larped for Claude Code

A Claude Code plugin that checks whether a Solana token's tech claims hold up, using the public [Larped](https://www.larped.tech) scanner. No API keys needed.

## Install

In Claude Code:

```
/plugin marketplace add FransmanKC/larped-skill
/plugin install larped@larped
```

## Use

```
/larped:check <mint address>
```

Or just ask, e.g. "is this pump.fun coin a larp? <mint>". Claude runs the bundled `larped` command, then explains the verdict, red flags, proofs and money trail, with a link to the full report.

The same command is available on its own as [larped-cli](https://github.com/FransmanKC/larped-cli).

Signals come from public data and describe what happened, not intent. Not financial advice.

## License

MIT
