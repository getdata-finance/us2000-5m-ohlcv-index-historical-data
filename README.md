# US2000 5m OHLCV Index Historical Data — Free Sample

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE) [![Dataset rows](https://img.shields.io/badge/full_dataset-553_995_rows-blue)](https://getdata.finance/datasets/us2000) [![Updated](https://img.shields.io/badge/weekly_update-every_Saturday_8am_UTC-green)](https://getdata.finance) [![Full data on getdata.finance](https://img.shields.io/badge/download-getdata.finance-orange)](https://getdata.finance/datasets/us2000)

### -> [**Download the full US2000 dataset on getdata.finance**](https://getdata.finance/datasets/us2000)

**US2000 5m OHLCV index historical data** — ultra high-quality 5m OHLCV for **Russell 2000**. Clean `datetime, open, high, low, close, volume` CSV for backtesting, algorithmic trading and quantitative research.

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

- **Ultra high-quality 5m OHLCV** for **Russell 2000** (Index)
- **Clean CSV schema** — `datetime, open, high, low, close, volume` (no gaps in formatting)
- **Free evaluation sample** on GitHub (`5m`) · **11 timeframes** on [getdata.finance](https://getdata.finance/datasets/us2000) · **553,995** `5m` rows in the full archive
- Built for **backtesting**, **algorithmic trading** and **quantitative finance** workflows
- **Weekly refresh** — [getdata.finance](https://getdata.finance) every **Saturday, 8am UTC+0**; GitHub `5m` sample updated in sync

> **Sample on GitHub** · `US2000_5m.csv` (11,089 rows, `2026-07-07` -> `2026-09-02`, 1.02 MB). **Full archive on [getdata.finance](https://getdata.finance/datasets/us2000)** — **553,995** `5m` rows (full `1m`: 2,762,553), **11 timeframes**, `2018-10-26` -> `2026-09-02`.

## Download sample

**[US2000_5m.csv](https://github.com/getdata-finance/us2000-5m-ohlcv-index-historical-data/blob/main/US2000_5m.csv)** on GitHub ([raw CSV](https://raw.githubusercontent.com/getdata-finance/us2000-5m-ohlcv-index-historical-data/main/US2000_5m.csv)) · [GitHub Releases](https://github.com/getdata-finance/us2000-5m-ohlcv-index-historical-data/releases)

## GitHub Pages

Interactive chart & stats: **[https://getdata-finance.github.io/us2000-5m-ohlcv-index-historical-data/](https://getdata-finance.github.io/us2000-5m-ohlcv-index-historical-data/)**

Full archive & live chart on getdata.finance: **[https://getdata.finance/datasets/us2000](https://getdata.finance/datasets/us2000)**

## Sample vs full dataset

| | **Sample (this repo)** | **Full dataset ([getdata.finance](https://getdata.finance/datasets/us2000))** |
|---|--:|---|
| Instrument | Russell 2000 · Index | Russell 2000 · Index |
| Timeframes | `5m` (sample) | **11** — 1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W |
| 5m rows | 11,089 | **553,995** |
| Size | 1.02 MB | full ZIP on [getdata.finance](https://getdata.finance/datasets/us2000) |
| Period | `2026-07-07` -> `2026-09-02` | `2018-10-26` -> `2026-09-02` |
| File | `US2000_5m.csv` | ZIP on [getdata.finance](https://getdata.finance/datasets/us2000) |
| Coverage report | — | [US2000 coverage](https://getdata.finance/coverage/us2000) |
| Updates | Weekly (Saturday, 8am UTC+0) — GitHub sample | Weekly (Saturday, 8am UTC+0) — all timeframes |

## Timeframes on GetData

This GitHub repository ships a **`5m` evaluation sample** only. On **[getdata.finance](https://getdata.finance/datasets/us2000)**, each full asset archive is delivered as a ZIP with **11 gap-free OHLCV timeframes** (one CSV per timeframe):

**1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W**

GitHub = `5m` sample · [getdata.finance](https://getdata.finance/datasets/us2000) = all **11** timeframes above for the same instrument.

## Weekly updates

- **[getdata.finance](https://getdata.finance)** — Full datasets are updated every Saturday, 8am UTC+0.
- **GitHub (this repo)** — GitHub samples are refreshed weekly (every Saturday, 8am UTC+0), in sync with getdata.finance.

When a new `5m` sample is published on GitHub, the README, chart preview and CSV reflect the latest week of data.

## Data preview

First and latest rows from the GitHub sample **`US2000_5m.csv`**:

**First rows**

| datetime | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-07-07T19:00:00+00:00 | 2985.32 | 2986.09 | 2980.72 | 2982.38 | 3813 |
| 2026-07-07T19:05:00+00:00 | 2982.38 | 2985.08 | 2979.92 | 2980.44 | 3426 |
| 2026-07-07T19:10:00+00:00 | 2980.44 | 2981.54 | 2978.69 | 2979.69 | 2871 |
| 2026-07-07T19:15:00+00:00 | 2979.69 | 2980.17 | 2975.73 | 2979.47 | 3360 |
| 2026-07-07T19:20:00+00:00 | 2979.47 | 2981.68 | 2977.74 | 2981.53 | 3458 |

**Last rows**

| datetime | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-09-02T01:40:00+00:00 | 2916.81 | 2917.81 | 2916.69 | 2917.2 | 445 |
| 2026-09-02T01:45:00+00:00 | 2917.2 | 2917.45 | 2916.59 | 2916.89 | 465 |
| 2026-09-02T01:50:00+00:00 | 2916.89 | 2917.21 | 2915.84 | 2917.14 | 617 |
| 2026-09-02T01:55:00+00:00 | 2917.14 | 2918.01 | 2916.84 | 2917.91 | 607 |
| 2026-09-02T02:00:00+00:00 | 2917.91 | 2917.96 | 2917.86 | 2917.96 | 13 |

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

df = pd.read_csv('US2000_5m.csv', parse_dates=['datetime'])
df.set_index('datetime', inplace=True)
print(df.describe())
```

### backtrader

```python
import backtrader as bt
import pandas as pd

df = pd.read_csv('US2000_5m.csv', parse_dates=['datetime'])
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

df = pd.read_csv('US2000_5m.csv', parse_dates=['datetime'])
close = df.set_index('datetime')['close']
fast, slow = vbt.MA.run(close, 10), vbt.MA.run(close, 50)
entries = fast.ma_crossed_above(slow)
exits = fast.ma_crossed_below(slow)
pf = vbt.Portfolio.from_signals(close, entries, exits, init_cash=10_000, freq='5min')
print(pf.stats())
```

## Download full data

The complete **US2000** archive on **[getdata.finance](https://getdata.finance/datasets/us2000)** includes **11 OHLCV timeframes** (1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W) — **553,995** rows at `5m`, plus all other timeframes in the same ZIP.

**[-> Get the full US2000 dataset on getdata.finance](https://getdata.finance/datasets/us2000)**

---
*GetData · US2000 5m OHLCV sample on GitHub · Full historical data on [getdata.finance](https://getdata.finance/datasets/us2000)*
