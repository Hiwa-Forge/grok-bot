# Grok bot — xAI

Ask Grok a question with web search, X search and code execution enabled.

## Setup

Never put your API key in the code. Set it as an environment variable:

```bash
export XAI_API_KEY="your-key-here"
```

Or copy `.env.example` to `.env` and fill it in. `.env` is ignored by git.

## How to run

```bash
pip install -r requirements.txt
jupyter notebook crok_bot_1.ipynb
```

## Tech

- Python
- xAI SDK (`xai_sdk`)
- Model: `grok-4-1-fast-reasoning`
- Tools: `web_search`, `x_search`, `code_execution`

## License

MIT
