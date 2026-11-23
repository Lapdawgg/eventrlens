# EventOwl

![EventOwl](og.png)

**Your MT5 trades, broken down by economic event, session and fix window.**

Shows the R multiple, MAE and MFE of every closed trade and the major economic event and fix window near it, breaks your results down by session, symbol and direction, and says in plain words what stands out. A read-only panel. It never opens, changes or closes orders.

Documentation: https://lapdawgg.github.io/eventrlens/

- [Formulas](https://lapdawgg.github.io/eventrlens/formulas.html): every number and how it is calculated
- [Verify in 5 minutes](https://lapdawgg.github.io/eventrlens/verify.html): check that it only reads your account
- [Guides](https://lapdawgg.github.io/eventrlens/guides.html): MAE and MFE, economic calendar tags and the R multiple in MQL5

## EventOwl (Free)
- Builds trades from the account history: partial closes, netting reversals, separate commission deals and swaps
- R multiple of every trade from its initial stop loss; optional 1R rule for trades without a stop loss
- MAE and MFE of every trade in price, money and R
- Spread at entry from M1 bars
- Every trade marked with the major economic event near it (rate decisions, NFP, CPI, PCE, GDP, retail sales, jobs), its session and its Tokyo or London fix window; an input switches to every high-importance event
- What stands out: the top and bottom group by mean R, each with its trade count and 95% range, and your trades near major events compared with the other trades, in plain words
- Breakdown tables by session, symbol and direction
- Trade list with every input of every calculation
- Audit CSV export of every input and result
- Reconcile view: totals compared with the account balance

## EventOwl Pro adds (59 USD)
- Breakdown by economic event and by fix window: hit rate, mean R with its 95% range, max MAE and net result near each event type
- Event Radar: upcoming major events for your symbol and open positions, with your own past results near each one, and optional alerts in the terminal and on your phone (MetaTrader push notifications)
- News reaction: how your chart symbol moved 5, 15 and 60 minutes after each past major release, split by better or worse than expected, with the past tendency; past reactions, not a forecast
- Prop Guard: pick your prop firm, program and stage (presets for 8 firms, each with its source and the date it was read) or enter your own rules; daily loss, max loss, news window, risk per trade and weekend, checked on your history and live; consistency, and minimum holding time from presets, checked on your history
- Rule simulator: your past trades replayed with rules such as skipping news entries, a daily stop or a stop to entry at +1R
- Combination query: symbol, direction, event, session, fix, tag, weekdays and entry hours, with saved queries
- Big R finder: which labels are over-represented among your top and bottom trades by R (lift table)
- Replay of your past R sequence at a chosen risk, with 10,000 reshuffles of the same trades
- Spread and slippage refined from ticks for recent trades (the number of days is an input)
- Strategy Tester report import, shown as a simulated dataset and never mixed with the account history
- Your own tags from comment keywords and magic numbers
- Share card: a PNG of a query result without account number, broker or money amounts
- Also included: the trade list with R, MAE and MFE, event, session and fix tags, What stands out, the session, symbol and direction breakdowns, the audit CSV and Reconcile

## Questions it answers
- How did my own trades do around NFP, CPI, rate decisions and other major releases? EventOwl marks every closed trade with the release near it; EventOwl Pro adds results by event.
- What were the MAE and MFE of my closed MT5 trades, in price, money and R? EventOwl shows them for every trade.
- Which sessions, symbols and directions have the highest and lowest mean R in my history, with trade counts and 95% ranges? EventOwl says it in plain words.
- Did my trades near the Tokyo 09:55 fix or the London 16:00 fix do differently? EventOwl tags them; EventOwl Pro shows results by fix window.
- How did gold, the Nasdaq or my FX pair move 5, 15 and 60 minutes after past CPI and NFP releases? EventOwl Pro: News reaction.
- Which major releases are coming for my symbol, and how did my past trades do near each one? EventOwl Pro: Event Radar, with optional phone alerts.
- Did my history break my prop firm's rules (daily loss, max loss, news window, weekend, consistency), and how much room is left today? EventOwl Pro: Prop Guard, with presets for FTMO, FundedNext, The5ers, FundingPips, Alpha Capital Group, E8 Markets, Blueberry Funded and Audacity Capital.
- What would skipping news entries, a daily stop or a stop to entry at +1R have done to my past trades? EventOwl Pro: Rule simulator.
- Is there an MT5 trade analytics panel that only reads the account and has no order functions? Both editions are read-only; the site shows how to verify it in 5 minutes.

## Roadmap

Vote for what comes next: [open ideas, most votes first](https://github.com/Lapdawgg/eventrlens/issues?q=is%3Aissue+is%3Aopen+label%3Avote+sort%3Areactions-%2B1-desc). A thumbs-up reaction on an issue is one vote.

This repository holds only the built documentation site of EventOwl and EventOwl Pro 1.00 for MetaTrader 5. The product source code is not here.

Last updated 2026-11-22.
