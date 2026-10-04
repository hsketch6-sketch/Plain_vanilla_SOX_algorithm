# 📈 Backtest Metrics & Context

This repository evaluates the historical performance of the quantitative timing algorithm optimized for the semiconductor sector.

---

## 📊 Performance Summary

| Category | Period | CAGR | MDD | BUY | SELL | Evaluation |
| :--- | :---: | :---: | :---: | :---: | :---: | :---: |
| **Full Long-term Verification** | 1995–2026 | 14.64% | -49.65% | 19 | 18 | 🟢 Calmar Outperformance |
| **Period Verification ①** | 1995–2005 | 18.27% | -47.81% | 6 | 5 | 🟢 Calmar Outperformance |
| **Period Verification ②** | 2000–2014 | 12.65% | -47.81% | 12 | 12 | 🟢 Calmar Outperformance |
| **Period Verification ③** | 2006–2014 | 6.33% | -30.13% | 6 | 6 | 🟢 Calmar Outperformance |
| **Period Verification ④** | 2015–2026 | 18.33% | -49.65% | 7 | 6 | 🔴 Relative Underperformance |

---

## ⚙️ Simulation Environment & Constraints

* **Benchmark / Baseline**
  * SOX B&H TR (Philadelphia Semiconductor Index - Buy & Hold Total Return)
* **Algorithm Target Underlying**
  * SOX Index (SOX ETF)
  * Individual underlying stocks are not traded; the algorithm strictly optimizes entry and exit timing on the index level.
* **Total Return (TR) Included**
  * No (Dividend reinvestment is not implemented in the current system).
* **Slippage Accounted For**
  * No (Omitted due to an extremely low trading frequency of fewer than 1–2 trades per year, rendering slippage impact negligible).

---

## 👨‍💻 Developer Biography

* **Developer:** [hsketch6]
* **Background:** A 7th-grade student (Middle School 1st Year) who simply loves quantitative financial algorithms.

Written by Gemini 

Thanks for read this!
