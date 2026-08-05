# GBPUSD 1h OHLCV Forex Historical Data — Free Sample

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE) [![Dataset rows](https://img.shields.io/badge/full_dataset-152_611_rows-blue)](https://getdata.finance/datasets/gbpusd) [![Updated](https://img.shields.io/badge/weekly_update-every_Saturday_8am_UTC-green)](https://getdata.finance) [![Full data on getdata.finance](https://img.shields.io/badge/download-getdata.finance-orange)](https://getdata.finance/datasets/gbpusd)

### -> [**Download the full GBPUSD dataset on getdata.finance**](https://getdata.finance/datasets/gbpusd)

**GBPUSD 1h OHLCV forex historical data** — ultra high-quality 1h OHLCV for **British Pound / US Dollar**. 24/5 market coverage — Asia, Europe and US sessions with institutional-style FX candles. Clean `datetime, open, high, low, close, volume` CSV for backtesting, algorithmic trading and quantitative research.

## Table of contents

- [Why this dataset?](#why-this-dataset)
- [Download sample CSV](#download-sample)
- [GitHub Pages preview](#github-pages)
- [Sample vs full dataset](#sample-vs-full-dataset)
- [Timeframes on GetData](#timeframes-on-getdata)
- [Weekly updates](#weekly-updates)
- [Data preview](#data-preview)
- [Schema](#schema)
- [Code examples](#code-examples)
- [Download full data on getdata.finance](#download-full-data-on-getdata)

## Why this dataset?

- **Ultra high-quality 1h OHLCV** for **British Pound / US Dollar** (Forex)
- **24/5 market coverage — Asia, Europe and US sessions with institutional-style FX candles**
- **Clean CSV schema** — `datetime, open, high, low, close, volume` (no gaps in formatting)
- **Free evaluation sample** on GitHub (`1h`) · **10 timeframes** on [getdata.finance](https://getdata.finance/datasets/gbpusd) · **152,611** `1m` rows in the full archive
- Built for **backtesting**, **algorithmic trading** and **quantitative finance** workflows
- **Weekly refresh** — [getdata.finance](https://getdata.finance) every **Saturday, 8am UTC+0**; GitHub `1h` sample updated in sync

> **Sample on GitHub** · `GBPUSD_1h.csv` (152,611 rows, `2001-11-28` -> `2026-07-31`). **Full archive on [getdata.finance](https://getdata.finance/datasets/gbpusd)** — **152,611** `1m` rows (~9.77 MB), **10 timeframes** (1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 1W), `2001-11-28` -> `2026-07-31`.

## Download sample

**[GBPUSD_1h.csv](https://github.com/getdata-finance/gbpusd-1h-ohlcv-forex-historical-data/blob/main/GBPUSD_1h.csv)** on GitHub ([raw CSV](https://raw.githubusercontent.com/getdata-finance/gbpusd-1h-ohlcv-forex-historical-data/main/GBPUSD_1h.csv)) · [GitHub Releases](https://github.com/getdata-finance/gbpusd-1h-ohlcv-forex-historical-data/releases)

## GitHub Pages

Interactive chart & stats: **[https://getdata-finance.github.io/gbpusd-1h-ohlcv-forex-historical-data/](https://getdata-finance.github.io/gbpusd-1h-ohlcv-forex-historical-data/)**

Full archive & live chart on getdata.finance: **[https://getdata.finance/datasets/gbpusd](https://getdata.finance/datasets/gbpusd)**

## Sample vs full dataset

| | **Sample (this repo)** | **Full dataset ([getdata.finance](https://getdata.finance/datasets/gbpusd))** |
|---|--:|---|
| Instrument | British Pound / US Dollar · Forex | British Pound / US Dollar · Forex |
| Timeframes | `1h` (sample) | **10** — 1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 1W |
| 1m rows | 152,611 | **152,611** |
| Size | 9.92 MB | ~9.77 MB |
| Period | `2001-11-28` -> `2026-07-31` | `2001-11-28` -> `2026-07-31` |
| File | `GBPUSD_1h.csv` | ZIP on [getdata.finance](https://getdata.finance/datasets/gbpusd) |
| Coverage report | — | [GBPUSD coverage](https://getdata.finance/coverage/gbpusd) |
| Updates | Weekly (Saturday, 8am UTC+0) — GitHub sample | Weekly (Saturday, 8am UTC+0) — all timeframes |

## Timeframes on GetData

This GitHub repository ships a **`1h` evaluation sample** only. On **[getdata.finance](https://getdata.finance/datasets/gbpusd)**, each full asset archive is delivered as a ZIP with **10 gap-free OHLCV timeframes** (one CSV per timeframe):

**1m** · **3m** · **5m** · **15m** · **30m** · **1H** · **4H** · **12H** · **1D** · **1W**

GitHub = `1h` sample · [getdata.finance](https://getdata.finance/datasets/gbpusd) = all **10** timeframes above for the same instrument.

## Weekly updates

- **[getdata.finance](https://getdata.finance)** — Full datasets are updated every Saturday, 8am UTC+0.
- **GitHub (this repo)** — GitHub samples are refreshed weekly (every Saturday, 8am UTC+0), in sync with getdata.finance.

When a new `1h` sample is published on GitHub, the README, chart preview and CSV reflect the latest week of data.

## Data preview

First and latest rows from the GitHub sample **`GBPUSD_1h.csv`**:

**First rows**

| datetime | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2001-11-28T04:00:00+00:00 | 1.4168 | 1.4171 | 1.416 | 1.4162 | 0 |
| 2001-11-28T05:00:00+00:00 | 1.4162 | 1.4182 | 1.4159 | 1.4176 | 0 |
| 2001-11-28T06:00:00+00:00 | 1.4176 | 1.4187 | 1.4168 | 1.4182 | 0 |
| 2001-11-28T07:00:00+00:00 | 1.4182 | 1.4186 | 1.4161 | 1.4167 | 0 |
| 2001-11-28T08:00:00+00:00 | 1.4167 | 1.4178 | 1.4159 | 1.4163 | 0 |

**Last rows**

| datetime | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-07-31T16:00:00+00:00 | 1.34818 | 1.34849 | 1.34755 | 1.34787 | 13715 |
| 2026-07-31T17:00:00+00:00 | 1.34787 | 1.3502 | 1.34786 | 1.34975 | 20825 |
| 2026-07-31T18:00:00+00:00 | 1.34975 | 1.35021 | 1.34887 | 1.34966 | 13490 |
| 2026-07-31T19:00:00+00:00 | 1.34966 | 1.3501 | 1.34906 | 1.34906 | 7432 |
| 2026-07-31T20:00:00+00:00 | 1.34906 | 1.35081 | 1.34867 | 1.3489 | 14219 |

## Schema

| Column | Description |
| --- | --- |
| `datetime` | Bar open timestamp (UTC, ISO-8601). |
| `open` | Opening price of the candlestick bar. |
| `high` | Highest price during the bar. |
| `low` | Lowest price during the bar. |
| `close` | Closing price of the candlestick bar. |
| `volume` | Tick volume (number of price updates) during the bar. |

```text
datetime,open,high,low,close,volume
```

## Code examples

### pandas

```python
import pandas as pd

df = pd.read_csv('GBPUSD_1h.csv', parse_dates=['datetime'])
df.set_index('datetime', inplace=True)
print(df.describe())
print(df.resample('1h').agg({'open': 'first', 'high': 'max',
                              'low': 'min', 'close': 'last', 'volume': 'sum'}).head())
```

### backtrader

```python
import backtrader as bt
import pandas as pd

df = pd.read_csv('GBPUSD_1h.csv', parse_dates=['datetime'])
df.set_index('datetime', inplace=True)

class PandasData(bt.feeds.PandasData):
    params = (('datetime', None), ('open', 'open'), ('high', 'high'),
              ('low', 'low'), ('close', 'close'), ('volume', 'volume'))

cerebro = bt.Cerebro()
cerebro.adddata(PandasData(dataname=df))
# cerebro.addstrategy(YourStrategy)
# cerebro.run()
```

### vectorbt

```python
import pandas as pd
import vectorbt as vbt

df = pd.read_csv('GBPUSD_1h.csv', parse_dates=['datetime'])
close = df.set_index('datetime')['close']
fast, slow = vbt.MA.run(close, 10), vbt.MA.run(close, 50)
entries = fast.ma_crossed_above(slow)
exits = fast.ma_crossed_below(slow)
pf = vbt.Portfolio.from_signals(close, entries, exits, init_cash=10_000, freq='1min')
print(pf.stats())
```

## Download full data

The complete **GBPUSD** archive on **[getdata.finance](https://getdata.finance/datasets/gbpusd)** includes **10 OHLCV timeframes** (1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 1W) — **152,611** rows at `1m`, plus all other timeframes in the same ZIP.

**[-> Get the full GBPUSD dataset on getdata.finance](https://getdata.finance/datasets/gbpusd)**

---
*GetData · GBPUSD 1h OHLCV sample on GitHub · Full historical data on [getdata.finance](https://getdata.finance/datasets/gbpusd) · 2026-08-05 UTC*
