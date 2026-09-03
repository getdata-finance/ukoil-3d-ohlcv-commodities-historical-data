# UKOIL 3d OHLCV Commodities Historical Data — Free Sample

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE) [![Dataset rows](https://img.shields.io/badge/full_dataset-4_237_rows-blue)](https://getdata.finance/datasets/ukoil) [![Updated](https://img.shields.io/badge/weekly_update-every_Saturday_8am_UTC-green)](https://getdata.finance) [![Full data on getdata.finance](https://img.shields.io/badge/download-getdata.finance-orange)](https://getdata.finance/datasets/ukoil)

### -> [**Download the full UKOIL dataset on getdata.finance**](https://getdata.finance/datasets/ukoil)

**UKOIL 3d OHLCV commodities historical data** — ultra high-quality 3d OHLCV for **Brent Crude Oil**. Clean `datetime, open, high, low, close, volume` CSV for backtesting, algorithmic trading and quantitative research.

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

- **Ultra high-quality 3d OHLCV** for **Brent Crude Oil** (Commodities)
- **Clean CSV schema** — `datetime, open, high, low, close, volume` (no gaps in formatting)
- **Free evaluation sample** on GitHub (`3d`) · **11 timeframes** on [getdata.finance](https://getdata.finance/datasets/ukoil) · **4,237** `3d` rows in the full archive
- Built for **backtesting**, **algorithmic trading** and **quantitative finance** workflows
- **Weekly refresh** — [getdata.finance](https://getdata.finance) every **Saturday, 8am UTC+0**; GitHub `3d` sample updated in sync

> **Sample on GitHub** · `UKOIL_3d.csv` (22 rows, `2026-06-30` -> `2026-09-01`, 2.05 KB). **Full archive on [getdata.finance](https://getdata.finance/datasets/ukoil)** — **4,237** `3d` rows (full `1m`: 5,237,943), **11 timeframes**, `1988-06-28` -> `2026-09-01`.

## Download sample

**[UKOIL_3d.csv](https://github.com/getdata-finance/ukoil-3d-ohlcv-commodities-historical-data/blob/main/UKOIL_3d.csv)** on GitHub ([raw CSV](https://raw.githubusercontent.com/getdata-finance/ukoil-3d-ohlcv-commodities-historical-data/main/UKOIL_3d.csv)) · [GitHub Releases](https://github.com/getdata-finance/ukoil-3d-ohlcv-commodities-historical-data/releases)

## GitHub Pages

Interactive chart & stats: **[https://getdata-finance.github.io/ukoil-3d-ohlcv-commodities-historical-data/](https://getdata-finance.github.io/ukoil-3d-ohlcv-commodities-historical-data/)**

Full archive & live chart on getdata.finance: **[https://getdata.finance/datasets/ukoil](https://getdata.finance/datasets/ukoil)**

## Sample vs full dataset

| | **Sample (this repo)** | **Full dataset ([getdata.finance](https://getdata.finance/datasets/ukoil))** |
|---|--:|---|
| Instrument | Brent Crude Oil · Commodities | Brent Crude Oil · Commodities |
| Timeframes | `3d` (sample) | **11** — 1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W |
| 3d rows | 22 | **4,237** |
| Size | 2.05 KB | full ZIP on [getdata.finance](https://getdata.finance/datasets/ukoil) |
| Period | `2026-06-30` -> `2026-09-01` | `1988-06-28` -> `2026-09-01` |
| File | `UKOIL_3d.csv` | ZIP on [getdata.finance](https://getdata.finance/datasets/ukoil) |
| Coverage report | — | [UKOIL coverage](https://getdata.finance/coverage/ukoil) |
| Updates | Weekly (Saturday, 8am UTC+0) — GitHub sample | Weekly (Saturday, 8am UTC+0) — all timeframes |

## Timeframes on GetData

This GitHub repository ships a **`3d` evaluation sample** only. On **[getdata.finance](https://getdata.finance/datasets/ukoil)**, each full asset archive is delivered as a ZIP with **11 gap-free OHLCV timeframes** (one CSV per timeframe):

**1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W**

GitHub = `3d` sample · [getdata.finance](https://getdata.finance/datasets/ukoil) = all **11** timeframes above for the same instrument.

## Weekly updates

- **[getdata.finance](https://getdata.finance)** — Full datasets are updated every Saturday, 8am UTC+0.
- **GitHub (this repo)** — GitHub samples are refreshed weekly (every Saturday, 8am UTC+0), in sync with getdata.finance.

When a new `3d` sample is published on GitHub, the README, chart preview and CSV reflect the latest week of data.

## Data preview

First and latest rows from the GitHub sample **`UKOIL_3d.csv`**:

**First rows**

| datetime | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-06-30T00:00:00+00:00 | 70.974 | 71.71 | 69.933 | 71.385 | 232908 |
| 2026-07-03T00:00:00+00:00 | 71.385 | 72.275 | 71.103 | 71.743 | 80143 |
| 2026-07-06T00:00:00+00:00 | 71.743 | 80.375 | 70.813 | 79.113 | 500751 |
| 2026-07-09T00:00:00+00:00 | 79.113 | 79.113 | 75.084 | 75.768 | 543842 |
| 2026-07-12T00:00:00+00:00 | 75.768 | 87.35 | 75.768 | 85.145 | 475982 |

**Last rows**

| datetime | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-08-20T00:00:00+00:00 | 90.686 | 93.922 | 90.601 | 93.171 | 342415 |
| 2026-08-23T00:00:00+00:00 | 93.171 | 93.171 | 88.151 | 88.395 | 261966 |
| 2026-08-26T00:00:00+00:00 | 88.395 | 90.756 | 86.84 | 89.229 | 289647 |
| 2026-08-29T00:00:00+00:00 | 89.229 | 92.528 | 89.229 | 91.744 | 173046 |
| 2026-09-01T00:00:00+00:00 | 91.744 | 98.007 | 91.727 | 97.007 | 252509 |

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
pf = vbt.Portfolio.from_signals(close, entries, exits, init_cash=10_000, freq='3d')
print(pf.stats())
```

## Download full data

The complete **UKOIL** archive on **[getdata.finance](https://getdata.finance/datasets/ukoil)** includes **11 OHLCV timeframes** (1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W) — **4,237** rows at `3d`, plus all other timeframes in the same ZIP.

**[-> Get the full UKOIL dataset on getdata.finance](https://getdata.finance/datasets/ukoil)**

---
*GetData · UKOIL 3d OHLCV sample on GitHub · Full historical data on [getdata.finance](https://getdata.finance/datasets/ukoil)*
