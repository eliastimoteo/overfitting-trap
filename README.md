# The Overfitting Trap: Why 95% of Backtested Crypto Strategies Fail

An interactive Python course where you experience strategy overfitting firsthand — then learn how to protect yourself.

## What This Is

You will:
1. Run a parameter sweep on real crypto derivatives data (400 combinations)
2. Find an "amazing" winning strategy with great returns
3. Test it on data it has never seen
4. Watch it fail

This is not theory. You run real code on real data and see the results yourself.

## Why This Matters

Most crypto trading courses sell you backtested results that look incredible. This module shows you exactly why those results are meaningless — and what to do instead.

This is based on a real 6-month research project involving 146 scripts, 11 crypto markets, and 5 timeframes. The failure you'll see in these notebooks is the same failure that happened in production research.

## Requirements

- Python 3.10+
- Jupyter Notebook or VS Code with Jupyter extension
- CoinGlass API key (Standard tier — [get one here](https://www.coinglass.com/?ref_code=KHDJVY))
- Libraries: `pandas`, `numpy`

```bash
pip install pandas numpy jupyter
```

## How to Use

1. Clone this repo
2. Open `01_parameter_sweep.ipynb` in Jupyter or VS Code
3. Run each cell top to bottom
4. Read the explanations between cells
5. Continue to `02_the_holdout_test.ipynb`

The whole module takes about 30 minutes.

## What You'll Learn

- What selection bias is and why it's invisible
- Why walk-forward validation alone doesn't prevent overfitting
- How to properly use a holdout test
- The 5 rules for honest strategy evaluation
- Why 400 parameter combinations guarantee a fake winner

## Sample Data Included

The repo includes a sample dataset so you can run the notebooks immediately without your own API key. If you want to use live data, add your CoinGlass API key.

## Want More?

This is Module 4 from **"Honest Crypto Quant"** — a complete interactive course covering:

- Building a data pipeline with CoinGlass + Binance
- Feature engineering for crypto derivatives
- Walk-forward validation done right
- **The Overfitting Trap (this module)**
- What doesn't work: classic strategies, macro timing, ML on small samples
- What actually works: funding carry, structural edges
- Building a live funding carry scanner with dashboard and alerts

**Full course available at:** [https://cryptoquantlab.gumroad.com/l/ksoypc](https://cryptoquantlab.gumroad.com/l/ksoypc)

## About

Built from a real crypto quant research project. No fake results, no cherry-picked backtests, no hype. Just honest findings from 6 months of systematic research.

## License

MIT — use it, share it, learn from it.
