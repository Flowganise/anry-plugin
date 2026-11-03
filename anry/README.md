# Anry

Anry is the analyst a small ecommerce team cannot hire. It watches your store
and your ad spend from the day you connect, with nothing to configure:
on-site behaviour, paid campaigns, every purchase. Statistical detectors find
where revenue is slipping out, price each leak, and write the fix into dated
reports your team reads each week.

This plugin gives Claude the same picture, and the playbooks Anry's own
analysts reason from, so Claude works through a question the way they would
rather than guessing from tool names.

## Install it

In claude.ai and Cowork, add the plugin from the directory, then connect the
Anry connector on the plugin's **Connectors** tab. In Claude Code:

```
/plugin install anry --marketplace Flowganise/anry-plugin
```

## Use it

Connect the Anry connector from the plugin's **Connectors** tab and sign in
with your Anry account. Then ask in plain language:

- "Where is my store losing money right now?"
- "Summarise my latest report and what I should do first."
- "Which of my ad campaigns wasted spend last month?"
- "What did visitors do on the checkout page this week?"
- "We shipped a new product page on Tuesday, log that."

Claude loads the playbook that fits, pulls the evidence behind every claim
(reports, sessions, heatmaps, traffic, paid spend), and quotes the figures
exactly as your dashboard shows them, in your store's own currency.

## Data

The plugin sends your questions and the site ids you ask about to your Anry
account through `mcp.anry.io`. It stores nothing itself.

Every tool reads, except `record_diary_entry`, which appends a dated entry to
the site diary of a site you can access: what your team changed, or a fact it
learned. Entries are never edited or deleted, and writing one changes nothing
else. No tool changes your store, your ad accounts, your settings, campaigns,
goals or reports.

You need an Anry account with a connected site ([anry.io](https://anry.io)).
Access is checked on every call against your own site memberships, so Claude
sees exactly the sites you see and nothing more.

Setup, the full tool list, and how authentication and data protection work:
[anry.io/mcp/docs](https://anry.io/mcp/docs). Privacy policy:
[anry.io/privacy](https://anry.io/privacy).
