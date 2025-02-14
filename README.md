# MLB Undervalued Player Analysis
This project analyzes **MLB hitting data (2022 season)** to uncover undervalued hitters using advanced metrics like **OPS, wOBA, and regression modeling**.

## Key Insights
- Players with **high OPS but low RBI** are often overlooked.
- **Walk rate (BB%)** is an **underrated skill** that leads to higher offensive production.
- **Regression modeling** helps identify hitters exceeding expectations.

## Tools Used
- **Python** (pandas, NumPy, statsmodels)
- **Machine Learning** (Linear Regression for OPS predictions)
- **Data Visualization** (matplotlib, seaborn)

## Files
- `underrated.ipynb` - Jupyter Notebook with full analysis
- `2022_batting_stats.csv` - Raw dataset
- `images/` - Key plots used in the report

## Results
📌 **Top 10 Undervalued Players**  
Danny Jansen: OPS = 0.855 (League Avg: 0.711), RBI = 44 (League Avg: 49)
Vinnie Pasquantino*: OPS = 0.832 (League Avg: 0.711), RBI = 26 (League Avg: 49)
Jake Fraley*: OPS = 0.812 (League Avg: 0.711), RBI = 28 (League Avg: 49)
Adley Rutschman#: OPS = 0.806 (League Avg: 0.711), RBI = 42 (League Avg: 49)
Lars Nootbaar*: OPS = 0.788 (League Avg: 0.711), RBI = 40 (League Avg: 49)
Andrew Benintendi*: OPS = 0.785 (League Avg: 0.711), RBI = 39 (League Avg: 49)
Michael Brantley*: OPS = 0.785 (League Avg: 0.711), RBI = 26 (League Avg: 49)
Brendan Donovan*: OPS = 0.773 (League Avg: 0.711), RBI = 45 (League Avg: 49)

## 📊 Visualizations
<img width="832" alt="Screenshot 2025-02-14 at 12 23 07 PM" src="https://github.com/user-attachments/assets/41b57157-bdbf-46d6-8d98-877f1fa7cae9" />
<img width="850" alt="Screenshot 2025-02-14 at 12 23 29 PM" src="https://github.com/user-attachments/assets/20ad9943-4fa3-41a4-8268-3fc0b3af6be2" />
<img width="840" alt="Screenshot 2025-02-14 at 12 23 40 PM" src="https://github.com/user-attachments/assets/d2f4ef4d-7ea5-4197-8394-d117cd670afb" />


## How to Run
1. Clone the repository:  
   ```bash
      git clone https://github.com/noaahkim/MLB-Undervalued-Player-Analysis.git
      cd MLB-Undervalued-Player-Analysis
