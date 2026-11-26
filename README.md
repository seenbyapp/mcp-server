# AI search visibility by Seenby

AI search visibility tracking over MCP. Connect [Seenby](https://seenbyapp.com) to Claude, ChatGPT, Cursor
or any MCP client and ask about brand mentions in AI answers: where ChatGPT, Perplexity, Gemini, Google AI
Mode and Google AI Overviews name you, where they don't, who they name instead and which pages they cite.
Use it for AI visibility tracking, AI Overviews tracking, LLM brand monitoring and generative engine
optimization (GEO).

## Remote server (recommended)

```
https://seenbyapp.com/mcp
```

Streamable HTTP with OAuth: add the URL in your client and sign in to Seenby when asked. Clients without
OAuth can send an API key (Settings → API keys) as `Authorization: Bearer sb_live_…`.

## Desktop (stdio)

```bash
npx -y seenby-mcp
```

Starts a local bridge to the remote server; your browser opens for sign-in and consent.

## Tools

`get_account`, `get_brand_report`, `get_question_history`, `list_cited_pages`, `suggest_setup`,
`create_brand`, `run_brand_now`, `add_question`, `set_question_active`, `delete_question`,
`add_competitor`, `remove_competitor`, `check_website`, `get_check`.

Every tool runs as your Seenby account. `create_brand` and `run_brand_now` ask the AI engines live and
use answers from your plan's allowance (questions × engines): monthly on paid plans, and 5 free checks
to try it on a Free account, no card. `check_website` asks three questions: one free check each on a
Free account, 3 new website checks a day included on paid plans. Everything else is free. Full reference: https://seenbyapp.com/developers/

Privacy policy: https://seenbyapp.com/privacy/
