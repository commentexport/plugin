# Comment export by Combly

Comment export, comment search and a giveaway winner picker for YouTube, TikTok and Instagram posts: export comments to CSV, find what viewers ask and draw fair giveaway winners.

This plugin connects Claude Code and Codex to the Combly MCP server at `https://commentexport.app/mcp` and adds a skill that tells the agent how to use it.

get_account reads your plan and usage. load_comments and search_comments read a post's comments and find them by keyword, author, date, questions or links; export_comments returns CSV. draw_giveaway picks random winners under your rules and publishes a winner page; list_giveaways and get_giveaway read past draws. Loads and draws use your plan's limits: every call runs on a Combly account, and a free account includes 5 post loads and 2 giveaway draws, once, no card; subscribe for more (paid plans count per month).

## Install (Claude Code)

```sh
/plugin marketplace add commentexport/plugin
/plugin install combly@combly
```

The first tool call opens your browser to sign in to Combly and approve access.

[Website](https://commentexport.app) · [MCP & API docs](https://commentexport.app/developers) · [Privacy](https://commentexport.app/privacy)
