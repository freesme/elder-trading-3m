# Elder Trading 3M Cheatsheet

## Core Test

| Layer | Question | Pass Condition |
|---|---|---|
| Mind | Why am I trading? | Profit under a written plan, not excitement or rescue |
| Method | What is the setup? | Timeframe, entry, stop, target, and invalidation are clear |
| Money | How much can I lose? | Fits 2% trade risk and 6% monthly risk |

## Position Size

```text
single_trade_risk = account_equity * 0.02
per_unit_risk = abs(entry - stop) + costs
quantity = floor(single_trade_risk / per_unit_risk)
```

Skip the trade if the chart's required stop makes the quantity too small or the risk too high.

## Monthly Risk Gate

```text
monthly_risk_limit = prior_month_end_equity * 0.06
current_month_total_risk = realized_losses + open_position_risk
```

If `current_month_total_risk >= monthly_risk_limit`, stop adding risk and review.

## Triple Screen

| Screen | Purpose | Typical Tool |
|---|---|---|
| 1 | Strategic direction | Higher-timeframe EMA or MACD histogram |
| 2 | Tactical setup | Pullback, oscillator, divergence |
| 3 | Entry and stop | Break trigger, limit order, SafeZone stop |

## Indicator Roles

| Tool | Measures | Best Use |
|---|---|---|
| Moving average | Consensus value trend | Direction and value area |
| Price channel | Emotional stretch | Targets and trade scoring |
| MACD histogram | Momentum shift | Divergence and reversal warning |
| Force Index | Price move x volume | Entry/exit pressure and divergence |
| Elder-ray | Bull/bear power vs EMA | Strength around trend value |
| Stochastic | Close within recent range | Overbought/oversold and no-trade zones |

## Four Records

| Record | Minimum Content |
|---|---|
| Spreadsheet | entry, exit, size, costs, P/L, channel score |
| Equity curve | month-end equity, 2% value, 6% value |
| Diary | annotated entry/exit charts, reason, emotion, lesson |
| Action plan | weekly view, daily view, exact order and contingency |

## Watchlist ABC

| Grade | Meaning | Action |
|---|---|---|
| A | Tradeable tomorrow | Prepare exact plan |
| B | Possible this week | Monitor |
| C | Not actionable | Ignore until conditions change |

## Stop Rules

- Move stops only in the trade's favor.
- Do not widen a stop because the market is near it.
- Place stops beyond normal noise, not at the most obvious crowd level.
- Once stop risk exceeds the budget, reduce or exit.

## Review Prompts

- Did I follow the plan?
- Was the entry inside a favorable part of the range/channel?
- Did the exit follow the reason planned before entry?
- Did the trade fit both 2% and 6% limits?
- What repeatable behavior should I keep or remove?
