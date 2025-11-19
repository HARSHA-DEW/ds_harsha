# 📌 Trader Behaviour vs Bitcoin Market Sentiment  
### 📊 Data Science Analysis Project

---

## 📝 **Project Overview**
This project explores how **Bitcoin market sentiment (Fear, Neutral, Greed)** influences trader behaviour on a crypto derivatives exchange.  
By combining **historical trader data** with a **market sentiment index**, we analyze:

✔ Profitability  
✔ Trade volume & frequency  
✔ Leverage usage  
✔ Risk exposure  
✔ Hour-of-day trading trends  

---

## 📁 **Project Structure**

ds_harsha/
├── notebook_1.ipynb # Data cleaning + visualization analysis
├── csv_files/
│ ├── raw_traders.csv
│ ├── raw_sentiment.csv
│ ├── cleaned_trader_data.csv
│ ├── cleaned_sentiment.csv
│ ├── merged_data.csv
│ └── cleaning_log.txt
├── outputs/
│ ├── trade_count_by_sentiment.png
│ ├── pnl_vs_sentiment.png
│ ├── leverage_sentiment.png
│ ├── risk_sentiment.png
│ ├── hourly_volume_sentiment.png
│ └── correlation_matrix.png
└── ds_report.pdf # Final report 

---

## 🛠️ **Technologies Used**

| Tool / Library | Purpose |
|----------------|---------|
| Python | Core data analysis |
| Pandas, NumPy | Data cleaning & transformation |
| Matplotlib, Seaborn | Visualization |
| Google Colab | Notebook environment |
| CSV handling | Data storage |

---

## 🔍 **Key Insights**

| Behaviour | Insight |
|-----------|--------|
| 🟢 Trade Activity | Higher during **Greed** |
| 💰 Profitability | Better in **Greed**, lowest in Neutral |
| 📈 Leverage | Used more aggressively in **Greed** |
| ⚠ Risk | Highest during **Greed** |
| ⏰ Time-of-Day | Greedy trades cluster around **peak hours (10 AM–12 PM)** |
| 🔗 Correlation | Higher risk **does not guarantee more profit** |

**Summary:** Traders are more active and aggressive during Greed, but increased risk does not always generate higher profits.

---
## 🔗 Google Colab Notebook
https://colab.research.google.com/github/HARSHA-DEW/ds_harsha/blob/main/notebook_1.ipynb

## 💡 **Recommendations**

✔ Do NOT increase leverage blindly in Greed markets  
✔ Maintain consistent position sizing  
✔ Use sentiment as a **risk control indicator**, not for over-trading  
✔ Neutral markets require careful strategy adjustments  
✔ Monitor **risk score** more than raw volume  

---

## 👤 **Author**

**Harsha**  
_Data Science Enthusiast_  

📌 Focus areas: Data Analytics, Python, Machine Learning, Visualization

---

### ⭐ If you like this project, consider giving the repo a **Star** on GitHub!

