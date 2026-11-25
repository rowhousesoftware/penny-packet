# Penny Packet

Tie a bank month to the statement to the cent, and compare it to the budget.

It's a hosted MCP server, so there's nothing to install. This repo is just the listing. The server code isn't here.

## Add it

Connector URL: `https://treasurer.rowhousesoftware.com/mcp`

In Claude: open Settings, then Connectors, then Add custom connector. Paste the URL.

In Claude Code:

```
claude mcp add -t http penny-packet https://treasurer.rowhousesoftware.com/mcp
```

## Tools

- `tie_out_month`: Checks a month of bank lines against the start and end balances.
- `budget_vs_actual`: Puts the month next to your budget, line by line.
- `pro_status`: Says what the plan on the site adds.

## Free and paid

Free here: both checks, as often as you like. On the site, $29 a month builds the whole board packet for one group, with a PDF and a spreadsheet. The first month is free.

## Sign in

None. It's open. No key and no sign in.

## Help

- Site: https://treasurer.rowhousesoftware.com
- Email: support@rowhousesoftware.com

Made by [Rowhouse Software](https://rowhousesoftware.com).
