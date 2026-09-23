STAGE 3 — LIVE EUR/USD 1H FEED

This version adds a live-data connector using Twelve Data's time_series endpoint.
You must supply your own Twelve Data API key.

PHONE:
1. Host these files on a secure HTTPS web host.
2. Open the URL in Chrome on Android.
3. Enter the API key.
4. Tap "Connect live EUR/USD".
5. Chrome menu > Add to Home screen.

IMPORTANT SECURITY:
This prototype sends the API key directly from the browser. Do NOT use a valuable/private production key this way.
For a production release, use a small backend proxy that stores the key server-side.

SIGNAL:
The browser builds 1H candles and evaluates:
HH/HL or LH/LL, BOS, basic price action, EMA20/50, RSI14 and ATR14.
It returns BUY, SELL or NO TRADE.
This is a prototype trading aid, not financial advice and not a guarantee of results.
