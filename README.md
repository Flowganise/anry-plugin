# Anry plugin for Claude

The [Anry](https://anry.io) plugin: Claude reads your store's revenue leaks,
reports, sessions and ad spend through Anry's MCP server, and reasons about
them with the playbooks Anry's own analysts work from.

The plugin itself is in [`anry/`](anry/). This repository is also a Claude
Code marketplace, so it can be installed from the command line before, or
instead of, the directory listing:

```
/plugin install anry --marketplace Flowganise/anry-plugin
```

In claude.ai and Cowork, install it from the plugin directory, then connect
the Anry connector on the plugin's **Connectors** tab and sign in with your
Anry account.

You need an Anry account with a connected site. Setup and the full tool list:
[anry.io/mcp/docs](https://anry.io/mcp/docs).

## Contributing

This repository is generated: it mirrors `plugins/claude/` in Anry's private
monorepo, where the plugin is maintained. Please open an issue rather than a
pull request, or write to hello@anry.io.
