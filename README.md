# ETH Likidasyon Seeds

TradingView Pine Seeds formatında gerçekleşen ETH likidasyon verileri.

- `ETH_LONG_01..10`: Top 10 long likidasyon kümeleri (büyükten küçüğe)
- `ETH_SHORT_01..10`: Top 10 short likidasyon kümeleri (büyükten küçüğe)

Pine Script kullanımı:
```pine
float price = request.seed("TraderF22/eth-liq-seeds/ETH_LONG_01", "60", close)
float usd   = request.seed("TraderF22/eth-liq-seeds/ETH_LONG_01", "60", open)
```
