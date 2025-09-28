# 📊 Sentiment-Driven Trading Behavior Analysis  
**Web3 Trading Team – Internship Assignment**  
**Author:** Suraj  
**Date:** September 2025

---

## 📌 Assignment Overview  
This project explores how market sentiment—captured by the Fear & Greed Index—affects trader behavior and performance. By merging sentiment data with historical trade records, we uncover patterns in profitability, trade volume, fees, and positioning across different emotional climates.

---

## 📁 Folder Structure


---

## 🧪 How to Run

1. Open `notebook_1.ipynb` in Google Colab or Jupyter Notebook.
2. Ensure the `csv_files/` folder is accessible in your environment.
3. Run cells sequentially to:
   - Load and clean data
   - Merge sentiment with trade records
   - Generate grouped insights and visualizations
   - Build correlation matrix

---

## 📊 Key Features Analyzed

- `Closed PnL` – Profitability
- `Fee` – Cost of trading
- `Size USD` – Trade volume
- `Side` – BUY vs SELL behavior
- `Execution Price`
- `Sentiment Classification` – Extreme Fear → Extreme Greed

---

## 📈 Visuals Included

- `pnl_vs_sentiment.png` – Average profit by sentiment
- `volume_vs_sentiment.png` – Trade volume by sentiment
- `fee_vs_sentiment.png` – Fee behavior by sentiment
- `buy_sell_distribution.png` – Buy vs Sell ratios
- `correlation_matrix.png` – Feature relationships

---

## ⚙️ Dependencies

```bash
pandas
matplotlib
seaborn
datetime
