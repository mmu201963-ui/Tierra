# TIERRA 1.2.0

PAPER-only Binance USD-M market intelligence bot. This build keeps the original TIERRA scanning/analysis engine and adds manual position controls.

## Controls
- `CERRAR` closes one position at the current public Binance Futures price.
- `CERRAR TODAS` closes all open PAPER positions and pauses new entries briefly.

## Run
```bash
npm install
npm start
```

No Binance API keys are required because this build is PAPER and uses public market data only. It does not place real orders and does not guarantee profits.
