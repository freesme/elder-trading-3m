# Chapter 6: 交易

## Core Idea

A trading system is an action plan, not a machine that removes judgment. Elder's systems combine tested rules, multiple timeframes, tactical entries, stops, and risk management.

## Frameworks Introduced

- **Manual system testing**
  - When to use: validating a method before live use.
  - How: replay historical bars one at a time, record every signal and decision, and evaluate stops, targets, and missed trades as if live.
- **Triple Screen Trading System**
  - When to use: building a complete swing/position trading workflow.
  - How: screen 1 defines long-term direction; screen 2 finds countertrend pullback or oscillator timing; screen 3 enters with a precise trigger and stop.
- **Impulse System**
  - When to use: quickly classifying whether buying, selling, or standing aside is allowed.
  - How: combine EMA slope and MACD histogram slope. Bullish alignment favors long trades, bearish alignment favors short trades, mixed signals require caution.
- **Market Thermometer / 市场晴雨表**
  - When to use: detecting unusually hot or extended markets.
  - How: compare today's range extensions with prior bars; high readings warn that movement is stretched and trade management should adjust.
- **SafeZone Stop**
  - When to use: trailing stops in trends.
  - How: measure recent adverse noise, average it, multiply by a factor, and place stops beyond normal noise rather than at obvious levels.

## Key Concepts

- **Trading rule**: broad principle such as trade with the trend.
- **Trading system**: organized rules for direction, entry, exit, and risk.
- **Trading tactic**: specific order placement or stop technique.
- **Simulated trading**: useful only when treated like homework with written orders and records.
- **Day trading**: higher-speed trading that demands liquidity, volatility, concentration, and exceptional discipline.
- **Overnight risk**: risk from holding beyond the intended intraday window.
- **Trend trading**: holding for larger moves, requiring patience and broader stops.
- **Swing trading**: aiming to capture shorter moves toward value or channel extremes.

## Mental Models

- Use **system as pilot checklist**: it guides normal conditions and highlights exceptions, but the operator remains responsible.
- Think of **triple screen as strategy then tactics**: never let a small timeframe seduce you against the bigger picture.
- Use **manual testing as apprenticeship**: one-bar-at-a-time review teaches pattern recognition that bulk statistics miss.

## Anti-patterns

- **Black-box faith**: believing a purchased or optimized system will work without judgment and monitoring.
- **Backtest overconfidence**: trusting polished historical statistics without live-like replay and behavioral testing.
- **Day trading without speed and records**: entering the fastest game with slow tools or unstable emotions.
- **Stops at obvious points**: placing risk where ordinary noise and crowd clustering are likely to trigger it.

## Key Takeaways

1. A system needs rules, but not the illusion of complete automation.
2. Test methods manually enough to understand how they behave trade by trade.
3. Triple screen separates strategic direction from tactical entry.
4. Stops must account for normal noise, not just chart neatness.
5. Select markets whose volatility, contract size, and trading hours fit your capital and routine.

## Connects To

- **Ch 5**: supplies the indicators used in the systems.
- **Ch 7**: checks every system signal against risk limits.
- **Ch 10**: shows the triple screen and divergence logic in completed trades.
