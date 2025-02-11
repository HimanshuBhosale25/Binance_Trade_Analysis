**Binance Trade Data Analysis**
===============================

📌 **Project Overview**
-----------------------

This project analyzes **historical trade data from Binance accounts** over a 90-day period to derive meaningful financial insights. The goal is to **rank accounts based on risk-adjusted performance**, identifying the top 20 accounts that demonstrate both **profitability and stability**.

📊 **Key Features**
-------------------

✔️ **Financial Metrics Calculation:** ROI, PnL, Sharpe Ratio, MDD, Win Rate, etc.\
✔️ **Risk-Aware Ranking System:** Prioritizes stable and consistent traders over high-risk ones.\
✔️ **Feature Engineering:** Extracts insights from trade data and assigns weighted scores.\
✔️ **Top 20 Accounts List:** Identifies the best-performing accounts based on calculated scores.

🏗 **Project Structure**
------------------------
``` sh
📂 Binance_Trade_Analysis/
│── 📜 primetrade_analysis.ipynb   # Jupyter Notebook with full analysis
│── 📜 Binance_Trade_Analysis_Report.pdf   # Final report detailing findings
│── 📜 metrics_results.csv   # CSV file with calculated metrics
│── 📜 README.md   # Project documentation (this file)
```
⚙️ **Methodology**
------------------

1️⃣ **Data Exploration & Cleaning** -- Loaded and processed the dataset, handled missing values.\
2️⃣ **Feature Engineering** -- Calculated key performance metrics like ROI, MDD, and Win Rate.\
3️⃣ **Ranking Algorithm** -- Developed a custom ranking system based on risk-adjusted metrics.\
4️⃣ **Scoring System** -- Assigned weights to different metrics to balance profitability and risk.\
5️⃣ **Evaluation & Insights** -- Identified the **top 20 best-performing accounts** based on the ranking.

📌 **Findings & Challenges**
----------------------------

🔹 The biggest challenge was balancing **high profitability** with **risk mitigation**.\
🔹 Some accounts had **high profits but large drawdowns**, making them unstable.\
🔹 The final ranking prioritized **Win Rate & Sharpe Ratio** to ensure **consistent performance**.\
🔹 Testing different metric weightings helped **fine-tune the scoring system**.

📂 **Deliverables**
-------------------

✅ **Jupyter Notebook** -- Full analysis and code implementation.\
✅ **CSV File** -- Contains calculated metrics for all accounts.\
✅ **Top 20 Accounts List** -- Best-performing accounts based on the ranking.\
✅ **Report** -- Summary of methodology, findings, and assumptions.

🚀 **How to Use**
-----------------

1️⃣ Clone the repository:
``` sh
git clone https://github.com/HimanshuBhosale25/Binance_Trade_Analysis.git
```

2️⃣ Open the Jupyter Notebook (`primetrade_analysis.ipynb`) and run the analysis.\
3️⃣ Check the `metrics_results.csv` file for calculated metrics.\
4️⃣ Read the report (`Binance_Trade_Analysis_Report.pdf`) for detailed insights.

🏆 **Conclusion**
-----------------

This project successfully provides a **structured and risk-aware ranking system** for Binance accounts, ensuring that top-performing traders are both **profitable and consistent**.