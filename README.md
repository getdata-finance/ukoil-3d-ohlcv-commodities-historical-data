# UKOIL 3d OHLCV Commodities Historical Data — Free Sample

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE) [![Dataset rows](https://img.shields.io/badge/full_dataset-4_225_rows-blue)](https://getdata.finance/datasets/ukoil) [![Updated](https://img.shields.io/badge/weekly_update-every_Saturday_8am_UTC-green)](https://getdata.finance) [![Full data on getdata.finance](https://img.shields.io/badge/download-getdata.finance-orange)](https://getdata.finance/datasets/ukoil)

### -> [**Download the full UKOIL dataset on getdata.finance**](https://getdata.finance/datasets/ukoil)

**UKOIL 3d OHLCV commodities historical data** — ultra high-quality 3d OHLCV for **UKOIL**. Global commodity sessions — Asia, Europe and US coverage for futures-style market activity. Clean `datetime, open, high, low, close, volume` CSV for backtesting, algorithmic trading and quantitative research.

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

- **Ultra high-quality 3d OHLCV** for **UKOIL** (Commodities)
- **Global commodity sessions — Asia, Europe and US coverage for futures-style market activity**
- **Clean CSV schema** — `datetime, open, high, low, close, volume` (no gaps in formatting)
- **Free evaluation sample** on GitHub (`3d`) · **9 timeframes** on [getdata.finance](https://getdata.finance/datasets/ukoil) · **4,225** `1m` rows in the full archive
- Built for **backtesting**, **algorithmic trading** and **quantitative finance** workflows
- **Weekly refresh** — [getdata.finance](https://getdata.finance) every **Saturday, 8am UTC+0**; GitHub `3d` sample updated in sync

> **Sample on GitHub** · `UKOIL_3d.csv` (66 rows, `2026-05-01` -> `2026-07-31`). **Full archive on [getdata.finance](https://getdata.finance/datasets/ukoil)** — **4,225** `1m` rows (~0.75 MB), **9 timeframes** (1m · 3m · 5m · 15m · 30m · 1H · 12H · 3D · 1W), `1988-06-28` -> `2026-07-30`.

## Download sample

**[UKOIL_3d.csv](https://github.com/getdata-finance/ukoil-3d-ohlcv-commodities-historical-data/blob/main/UKOIL_3d.csv)** on GitHub ([raw CSV](https://raw.githubusercontent.com/getdata-finance/ukoil-3d-ohlcv-commodities-historical-data/main/UKOIL_3d.csv)) · [GitHub Releases](https://github.com/getdata-finance/ukoil-3d-ohlcv-commodities-historical-data/releases)

## GitHub Pages

Interactive chart & stats: **[https://getdata-finance.github.io/ukoil-3d-ohlcv-commodities-historical-data/](https://getdata-finance.github.io/ukoil-3d-ohlcv-commodities-historical-data/)**

Full archive & live chart on getdata.finance: **[https://getdata.finance/datasets/ukoil](https://getdata.finance/datasets/ukoil)**

## Sample vs full dataset

| | **Sample (this repo)** | **Full dataset ([getdata.finance](https://getdata.finance/datasets/ukoil))** |
|---|--:|---|
| Instrument | UKOIL · Commodities | UKOIL · Commodities |
| Timeframes | `3d` (sample) | **9** — 1m · 3m · 5m · 15m · 30m · 1H · 12H · 3D · 1W |
| 1m rows | 66 | **4,225** |
| Size | 0.01 MB | ~0.75 MB |
| Period | `2026-05-01` -> `2026-07-31` | `1988-06-28` -> `2026-07-30` |
| File | `UKOIL_3d.csv` | ZIP on [getdata.finance](https://getdata.finance/datasets/ukoil) |
| Coverage report | — | [UKOIL coverage](https://getdata.finance/coverage/ukoil) |
| Updates | Weekly (Saturday, 8am UTC+0) — GitHub sample | Weekly (Saturday, 8am UTC+0) — all timeframes |

## Timeframes on GetData

This GitHub repository ships a **`3d` evaluation sample** only. On **[getdata.finance](https://getdata.finance/datasets/ukoil)**, each full asset archive is delivered as a ZIP with **9 gap-free OHLCV timeframes** (one CSV per timeframe):

**1m** · **3m** · **5m** · **15m** · **30m** · **1H** · **12H** · **3D** · **1W**

GitHub = `3d` sample · [getdata.finance](https://getdata.finance/datasets/ukoil) = all **9** timeframes above for the same instrument.

## Weekly updates

- **[getdata.finance](https://getdata.finance)** — Full datasets are updated every Saturday, 8am UTC+0.
- **GitHub (this repo)** — GitHub samples are refreshed weekly (every Saturday, 8am UTC+0), in sync with getdata.finance.

When a new `3d` sample is published on GitHub, the README, chart preview and CSV reflect the latest week of data.

## Data preview

First and latest rows from the GitHub sample **`UKOIL_3d.csv`**:

**First rows**

| datetime | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-05-01T00:00:00+00:00 | 110.983 | 112.23 | 106.033 | 108.589 | 269435 |
| 2026-05-04T00:00:00+00:00 | 108.589 | 115.073 | 106.323 | 113.643 | 292606 |
| 2026-05-05T00:00:00+00:00 | 113.643 | 114.22 | 109.403 | 110.315 | 232454 |
| 2026-05-06T00:00:00+00:00 | 110.315 | 110.315 | 96.543 | 101.8 | 384921 |
| 2026-05-07T00:00:00+00:00 | 101.8 | 103.18 | 95.834 | 102.858 | 346014 |

**Last rows**

| datetime | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-07-27T00:00:00+00:00 | 97.925 | 97.925 | 87.223 | 87.494 | 144146 |
| 2026-07-28T00:00:00+00:00 | 87.494 | 87.865 | 82.313 | 83.573 | 225591 |
| 2026-07-29T00:00:00+00:00 | 83.573 | 90.965 | 83.573 | 90.398 | 215977 |
| 2026-07-30T00:00:00+00:00 | 90.398 | 93.105 | 88.613 | 89.345 | 193413 |
| 2026-07-31T00:00:00+00:00 | 89.345 | 89.345 | 84.414 | 85.925 | 45240 |

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

df = pd.read_csv('UKOIL_3d.csv', parse_dates=['datetime'])
df.set_index('datetime', inplace=True)
print(df.describe())
print(df.resample('1h').agg({'open': 'first', 'high': 'max',
                              'low': 'min', 'close': 'last', 'volume': 'sum'}).head())
```

### backtrader

```python
import backtrader as bt
import pandas as pd

df = pd.read_csv('UKOIL_3d.csv', parse_dates=['datetime'])
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

df = pd.read_csv('UKOIL_3d.csv', parse_dates=['datetime'])
close = df.set_index('datetime')['close']
fast, slow = vbt.MA.run(close, 10), vbt.MA.run(close, 50)
entries = fast.ma_crossed_above(slow)
exits = fast.ma_crossed_below(slow)
pf = vbt.Portfolio.from_signals(close, entries, exits, init_cash=10_000, freq='1min')
print(pf.stats())
```

## Download full data

The complete **UKOIL** archive on **[getdata.finance](https://getdata.finance/datasets/ukoil)** includes **9 OHLCV timeframes** (1m · 3m · 5m · 15m · 30m · 1H · 12H · 3D · 1W) — **4,225** rows at `1m`, plus all other timeframes in the same ZIP.

**[-> Get the full UKOIL dataset on getdata.finance](https://getdata.finance/datasets/ukoil)**

---
*GetData · UKOIL 3d OHLCV sample on GitHub · Full historical data on [getdata.finance](https://getdata.finance/datasets/ukoil) · 2026-08-05 UTC*
