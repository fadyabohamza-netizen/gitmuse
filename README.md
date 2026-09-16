# GitMuse 🪶

**AI-powered git workflow assistant.** Commit messages, error explanations, and PR descriptions — instant, from your terminal output. Powered by Pollinations AI.

## Features

- **📝 Commit Message** — paste any diff, get a Conventional Commits message (`feat(scope): description`)
- **🐞 Error Fix** — paste a stack trace or build error, get a clear explanation + fix
- **🔄 PR Description** — paste a diff, get a title + summary body

## How it works (Bring Your Own Pollen)

GitMuse uses the [Pollinations Connect User Wallets](https://github.com/pollinations/pollinations/blob/main/BRING_YOUR_OWN_POLLEN.md) (BYOP) flow:

1. You click **Connect Pollen** — a consent screen opens
2. You authorize GitMuse to spend **your own Pollen** on your requests
3. Requests run with your balance, under the budget you approve (default 5 Pollen, 7-day key)
4. You can revoke or edit the app key anytime from [your dashboard](https://enter.pollinations.ai/keys)

Your usage is paid from your balance — never from the app owner's account.

## Models

- **Free tier** — `openai/gpt-5.4-nano` (fast, cheap)
- **Premium** — toggle PRO for a stronger model

## Development

```bash
# Files
index.html    # static frontend (no build step)
agent.json    # Pollinations prompt-agent definition (owner-side)
```

## Links

- Live app: GitHub Pages URL
- Agent: `fadyabohamza-netizen/gitmuse` (private, owner access)
- Powered by [Pollinations](https://gen.pollinations.ai)
- Author: [fadyabohamza-netizen](https://github.com/fadyabohamza-netizen)