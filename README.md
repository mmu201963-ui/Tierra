# TIERRA — Original + Manual Controls + Fast Position Watcher

PAPER only. Based on the original TIERRA engine that was already running.

Changes in this build are intentionally limited to:
- Manual close per position.
- Close all positions.
- HTTP server becomes ready before the first full-market scan.
- Full-market scan runs in the background.
- Position protection/mark-price watcher runs independently every 2 seconds.

No Binance API keys are required. No real orders are sent.

## Railway
- Build: `npm install`
- Start: `npm start`
