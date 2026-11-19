# Day-Trade Terminal

A one-page trading terminal for gold, NAS100, US30, S&P 500, GER40 and UK100: live TradingView charts, order-flow footprint and volume profile (Binance), an economic calendar with Forex Factory forecasts and official actual figures (BLS, Federal Reserve, Bank of England, ECB, ONS, Eurostat, FRED), and **Advisors**.

**Advisors** (relay version 3): every 15 minutes four advisors look at each market on your watchlist: Structure (liquidity sweep, shift in structure, gap entry), Momentum, Risk (1:2 minimum, news, two-loss stop) and a Judge that weighs them by how often each has been right. Gemini writes the reasons. Calls are paper-traded and graded automatically. Nothing places real orders.

Open it in Chrome on Android and choose **⋮ → Install app** to use it like an app.

Your keys (Twelve Data, Gemini, FRED) live only in your own Google Apps Script project, never in this repository.
Not investment advice.
