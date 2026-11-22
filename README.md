# Seenby MCP

Connect [Seenby](https://seenbyapp.com) to Claude, ChatGPT, Cursor or any MCP client and ask about your
brand's visibility in AI answers: where ChatGPT, Perplexity, Gemini, Google AI Mode and Google AI Overviews
name you, where they don't, who they name instead and which pages they cite.

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

`create_brand` and `run_brand_now` ask the AI engines live and use answers from your plan's monthly
allowance (questions × engines). Everything else is free. Full reference: https://seenbyapp.com/developers/

Privacy policy: https://seenbyapp.com/privacy/
