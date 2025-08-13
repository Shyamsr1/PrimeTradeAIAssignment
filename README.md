# PrimeTrade AI Assignment

## Overview
This repository contains the **PrimeTrade AI Assignment** Jupyter Notebook, which performs trading data analysis, sentiment correlation, and visualization tasks. The analysis leverages the Fear–Greed Index, trading performance metrics, and statistical methods to uncover relationships between market sentiment and profitability.

## Contents
- **`PrimetradeaiAssignment.ipynb`** — Main analysis notebook.
- **Data Files:**
  - `fear_greed_index.csv` — Sentiment scores and classifications.
  - `historical_data.csv` — Trade history with PnL, volume, fees.
- **requirements.txt**
- **README.md**

## Key Features
- Data preprocessing & cleaning.
- Sentiment and PnL correlation analysis.
- Group statistics by sentiment classification.
- Statistical hypothesis testing (T-test, Kruskal–Wallis).
- Rich data visualizations (heatmaps, time-series, bar plots).

## Dataset Columns & Descriptions

The dataset contains multiple columns with detailed descriptions, which are provided inside the
[`PrimetradeaiAssignment.ipynb`](PrimetradeaiAssignment.ipynb) file.  
Please refer to that notebook for a complete breakdown of each column and its purpose.


## How to Run
1. Clone the repository:
```bash
git clone https://github.com/Shyamsr1/PrimeTradeAIAssignment.git
cd PrimeTradeAIAssignment
```
2. Install dependencies:
```bash
pip install -r requirements.txt
```
3. Place the CSV files into the `data/` directory.
4. Open and run the notebook:
```bash
jupyter notebook PrimetradeaiAssignment.ipynb
```

## License
MIT License — feel free to use and adapt.
