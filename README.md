# gap-bot-state

State mirror for the gap-bot paper account. The VPS pushes the bot's state here once a day so a dashboard can read it. One direction only: nothing here is edited by hand and nothing flows back.

Everything in this repo is paper money. The account starts at a synthetic $100,000, fills are simulated against real quotes, and no order is ever sent to a broker. The three folders are the three instrument variants of the same signal (stock, long call, call spread); only the stock account has ever run.

The bot is paused as of 2026-09-12, so the files stop changing at that date. The research and code are in [gap-bot](https://github.com/GeorgeManavazian/gap-bot).
