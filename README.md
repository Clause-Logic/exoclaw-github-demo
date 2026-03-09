# exoclaw-github-demo

Demo repository for [exoclaw-github](https://github.com/Clause-Logic/exoclaw-github) — an AI agent that runs inside GitHub Actions.

## Try it

Open an issue or leave a comment containing `@exoclaw` and the bot will respond.

## How it works

- Powered by [exoclaw](https://github.com/Clause-Logic/exoclaw) + GitHub Models (`gpt-4.1-mini`)
- No API keys required — uses the built-in `GITHUB_TOKEN`
- Session history persisted to the `bot-state` branch
- See [`.github/workflows/exoclaw.yml`](.github/workflows/exoclaw.yml) for the full config
