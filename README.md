# XPTUSD 1m OHLCV Metals Historical Data — Free Sample

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE) [![Dataset rows](https://img.shields.io/badge/full_dataset-4_736_622_rows-blue)](https://ork.ad/) [![Updated](https://img.shields.io/badge/weekly_update-every_Sunday-green)]() [![Full data on ork.ad](https://img.shields.io/badge/download-ork.ad-orange)](https://ork.ad/)

### → [**Download the full XPTUSD dataset on ork.ad**](https://ork.ad/)

**XPTUSD 1m OHLCV Precious metals historical data** — ultra high-quality one-minute OHLCV for **Platinum / US Dollar**. Near-continuous precious-metals liquidity across global sessions. Clean `time, open, high, low, close, volume` CSV for backtesting, algorithmic trading and quantitative research.

## Table of contents

- [Why this dataset?](#why-this-dataset)
- [Download sample CSV](#download-sample)
- [GitHub Pages preview](#github-pages)
- [Sample vs full dataset](#sample-vs-full-dataset)
- [Timeframes on ork.ad](#timeframes-on-orkad)
- [Weekly updates](#weekly-updates)
- [Data preview](#data-preview)
- [Schema](#schema)
- [Code examples](#code-examples)
- [Download full data on ork.ad](#download-full-data)

## Why this dataset?

- **Ultra high-quality 1-minute OHLCV** for **Platinum / US Dollar** (Precious metals)
- **Near-continuous precious-metals liquidity across global sessions**
- **Clean CSV schema** — `time, open, high, low, close, volume` (no gaps in formatting)
- **Free evaluation sample** on GitHub (`1m` only) · **13 timeframes** on [ork.ad](https://ork.ad/) · **4,736,622** `1m` rows in the full archive
- Built for **backtesting**, **algorithmic trading** and **quantitative finance** workflows
- **Weekly refresh** — [ork.ad](https://ork.ad/) every **Sunday**; GitHub `1m` sample updated in sync

> **Sample on GitHub** · `XPTUSD_1m.csv` (173,955 rows, `2025-12-02` → `2026-06-02`). **Full archive on [ork.ad](https://ork.ad/)** — **4,736,622** `1m` rows (~269.97 MB), **13 timeframes** (``1m`, `3m`, `5m`, `15m`, `30m`, `1H`, `2H`, `4H`, `8H`, `12H`, `16H`, `1D`, `1W``), `2008-11-09` → `2026-06-02`.

## Download sample

**[XPTUSD_1m.csv](https://github.com/ork-ad/xptusd-1m-ohlcv-metals-historical-data/blob/main/XPTUSD_1m.csv)** on GitHub ([raw CSV](https://raw.githubusercontent.com/ork-ad/xptusd-1m-ohlcv-metals-historical-data/main/XPTUSD_1m.csv)) · [GitHub Releases](https://github.com/ork-ad/xptusd-1m-ohlcv-metals-historical-data/releases) when the release workflow is active.

## GitHub Pages

Interactive chart & stats: **[https://ork-ad.github.io/xptusd-1m-ohlcv-metals-historical-data/](https://ork-ad.github.io/xptusd-1m-ohlcv-metals-historical-data/)**

## Sample vs full dataset

| | **Sample (this repo)** | **Full dataset ([ork.ad](https://ork.ad/))** |
|---|--:|---|
| Instrument | Platinum / US Dollar · Precious metals | Platinum / US Dollar · Precious metals |
| Timeframes | `1m` only (sample) | **13** — `1m`, `3m`, `5m`, `15m`, `30m`, `1H`, `2H`, `4H`, `8H`, `12H`, `16H`, `1D`, `1W` |
| 1m rows | 173,955 | **4,736,622** |
| Size | 9.91 MB | ~269.97 MB |
| Period | `2025-12-02` → `2026-06-02` | `2008-11-09` → `2026-06-02` |
| File | `XPTUSD_1m.csv` | ZIP on [ork.ad](https://ork.ad/) |
| Updates | Weekly (Sunday) — GitHub sample | Weekly (Sunday) — all timeframes |

## Timeframes on ork.ad

This GitHub repository ships a **1-minute (`1m`) evaluation sample** only. On **[ork.ad](https://ork.ad/)**, each full asset archive is delivered as a ZIP with **13 gap-free OHLCV timeframes** (one CSV per timeframe):

**1m** · **3m** · **5m** · **15m** · **30m** · **1H** · **2H** · **4H** · **8H** · **12H** · **16H** · **1D** · **1W**

GitHub = `1m` sample · [ork.ad](https://ork.ad/) = all **13** timeframes above for the same instrument.

## Weekly updates

- **[ork.ad](https://ork.ad/)** — Full datasets on ork.ad are updated every Sunday.
- **GitHub (this repo)** — GitHub 1m samples are refreshed weekly (every Sunday), in sync with ork.ad.

When a new `1m` sample is published on GitHub, the README, chart preview and CSV reflect the latest week of data.

## Data preview

First and latest rows from the GitHub sample **`XPTUSD_1m.csv`**:

**First rows**

| time | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2025-12-02T10:20:00Z | 1618.036 | 1618.136 | 1614.414 | 1614.563 | 96 |
| 2025-12-02T10:21:00Z | 1614.513 | 1616.002 | 1614.314 | 1616.002 | 99 |
| 2025-12-02T10:22:00Z | 1615.903 | 1617.69 | 1615.903 | 1617.59 | 49 |
| 2025-12-02T10:23:00Z | 1617.54 | 1617.64 | 1616.499 | 1617.342 | 64 |
| 2025-12-02T10:24:00Z | 1617.392 | 1619.129 | 1617.243 | 1618.683 | 61 |

**Last rows**

| time | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| time | open | high | low | close | volume |
| 2026-06-02T10:16:00Z | 1948.872 | 1948.872 | 1946.838 | 1947.136 | 42 |
| 2026-06-02T10:17:00Z | 1947.186 | 1947.98 | 1947.186 | 1947.484 | 63 |
| 2026-06-02T10:18:00Z | 1947.682 | 1947.98 | 1947.434 | 1947.632 | 17 |
| 2026-06-02T10:19:00Z | 1947.582 | 1948.427 | 1947.484 | 1948.427 | 25 |

## Schema

```text
time,open,high,low,close,volume
```

## Code examples

### pandas

```python
import pandas as pd

df = pd.read_csv('XPTUSD_1m.csv', parse_dates=['time'])
df.set_index('time', inplace=True)
print(df.describe())
print(df.resample('1h').agg({'open': 'first', 'high': 'max',
                              'low': 'min', 'close': 'last', 'volume': 'sum'}).head())
```

### backtrader

```python
import backtrader as bt
import pandas as pd

df = pd.read_csv('XPTUSD_1m.csv', parse_dates=['time'])
df.set_index('time', inplace=True)

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

df = pd.read_csv('XPTUSD_1m.csv', parse_dates=['time'])
close = df.set_index('time')['close']
fast, slow = vbt.MA.run(close, 10), vbt.MA.run(close, 50)
entries = fast.ma_crossed_above(slow)
exits = fast.ma_crossed_below(slow)
pf = vbt.Portfolio.from_signals(close, entries, exits, init_cash=10_000, freq='1min')
print(pf.stats())
```

## Download full data

The complete **XPTUSD** archive on **[ork.ad](https://ork.ad/)** includes **13 OHLCV timeframes** (`1m`, `3m`, `5m`, `15m`, `30m`, `1H`, `2H`, `4H`, `8H`, `12H`, `16H`, `1D`, `1W`) — **4,736,622** rows at `1m`, plus all higher timeframes in the same ZIP.

**[→ Get the full XPTUSD dataset on ork.ad](https://ork.ad/)**

---
*GetData · XPTUSD 1m OHLCV sample on GitHub · Full historical data on [ork.ad](https://ork.ad/) · 2026-07-02 UTC*