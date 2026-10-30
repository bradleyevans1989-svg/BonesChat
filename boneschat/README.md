# BonesChat setup

BonesChat is a fork of [LibreChat](https://github.com/danny-avila/LibreChat) set up for
Claude, ChatGPT, Grok and Meta Llama.

## Keys

| AI | Env var | Get a key |
| --- | --- | --- |
| Claude | `ANTHROPIC_API_KEY` | https://console.anthropic.com/settings/keys |
| ChatGPT | `OPENAI_API_KEY` | https://platform.openai.com/api-keys |
| Grok | `XAI_API_KEY` | https://console.x.ai |
| Meta Llama | `OPENROUTER_KEY` | https://openrouter.ai/keys |

Also set `APP_TITLE=BonesChat` in `.env`.

## Run locally (Docker)

```bash
cp .env.example .env            # then fill in the keys above and APP_TITLE
cp boneschat/librechat.yaml librechat.yaml
docker compose up -d            # open http://localhost:3080
```
