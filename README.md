# trader-sentiment-analysis
Executive Summary & Recommendations
Key Findings
Extreme Greed = best performance — highest win rate (89%) and average PnL ($130). Euphoric markets produced the best outcomes.

Extreme Fear = panic overtrading — 743 trades/day with a risk/reward of 0.67. More trades, worse results.

Fear = biggest bets, worst returns — largest avg trade size ($8,041) but risk/reward barely above break-even (0.97).

Only Extreme Greed has risk/reward above 1.0 — the only period where average wins exceed average losses.

Sentiment drives direction bias — 70% short trades during Fear, most balanced ratio during Greed (45% long).

Trade size dominates outcomes — 96% feature importance in the ML model. Position sizing matters more than sentiment or direction.

Random Forest best model — 80% accuracy, meaningful loss detection (38% recall on losing trades).

Recommendations
Reduce trade frequency during Extreme Fear — overtrading during panic is the biggest destroyer of returns
Implement position size limits — trade size is the #1 predictor of profitability
Trust Greed periods — disciplined smaller trades produce the best risk-adjusted returns
Flag and review trades with high size during Fear periods — loss magnitude is 2x higher than during Extreme Greed
