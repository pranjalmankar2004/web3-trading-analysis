Data Science Assignment - Web3 Trading Team
Candidate: Pranjal Mankar
Assignment: Trader Behavior vs Market Sentiment Analysis
📋 Project Overview
This project analyzes the relationship between trader behavior on Hyperliquid exchange and Bitcoin market sentiment (Fear & Greed Index). The analysis explores how market emotions influence trading profitability, volume patterns, win rates, and overall trading performance.
🔗 Google Colab Notebook
Primary Analysis: View Notebook
Note: Notebook is set to "Anyone with the link can view" as per requirements
📁 Repository Structure
ds_pranjal_mankar/
├── notebook_1.ipynb          
├── csv_files/                 
├── outputs/                   
├── ds_report.pdf             
└── README.md                 
📊 Datasets Used
1.	Bitcoin Market Sentiment Dataset
•	Source: Fear & Greed Index
•	Columns: Date, Classification (Fear/Greed categories)
2.	Historical Trader Data from Hyperliquid
•	Columns: account, symbol, execution price, size, side, time, start position, event, closedPnL, leverage, etc.
🎯 Key Findings
•	Most Profitable Period: Extreme Greed ($67.89 average PnL)
•	Least Profitable Period: Neutral ($34.31 average PnL)
•	Highest Win Rate: Extreme Greed (52% success rate)
•	Lowest Win Rate: Extreme Fear (37% success rate)
•	Statistical Significance: p-value = 0.0000 (highly significant)
🛠️ Technologies & Libraries Used
•	Python 3.x
•	pandas - Data manipulation and analysis
•	numpy - Numerical computations
•	matplotlib - Data visualization
•	seaborn - Statistical visualizations
•	scipy.stats - Statistical testing (Kruskal-Wallis test)
•	Google Colab - Development environment
📈 Analysis Methodology
1.	Data Cleaning & Preprocessing
•	Timestamp normalization and date alignment
•	Numeric conversion for PnL and volume columns
•	Missing value handling
2.	Exploratory Data Analysis
•	Sentiment distribution analysis
•	Trading volume patterns by sentiment
•	Profit/Loss distribution across market emotions
•	Win rate calculations
3.	Statistical Testing
•	Kruskal-Wallis test for comparing multiple groups
•	Statistical significance validation
4.	Visualization & Insights
•	Four comprehensive charts showing key relationships
•	Performance summary generation
•	Trading strategy recommendations
🚀 How to Run the Analysis
1.	Open the Google Colab notebook
2.	Upload the dataset files to Colab environment:
•	fear_greed_index.csv
•	historical_data.csv
3.	Run all cells sequentially
4.	Generated outputs will be saved automatically
📝 Key Insights & Recommendations
Trading Strategies Discovered:
•	Contrarian Approach: Buy during high fear periods when markets overreact
•	Momentum Trading: Increase positions during moderate greed periods
•	Dynamic Risk Management: Adjust position sizes based on sentiment intensity
•	Sentiment Monitoring: Use emotion shifts as early reversal indicators
Risk Management:
•	Reduce exposure during extreme sentiment periods (both fear and greed)
•	Apply stricter stop-losses during volatile sentiment phases
•	Monitor sentiment transitions for optimal entry/exit timing
📊 Generated Outputs
CSV Files:
•	merged_dataset.csv: Complete analysis dataset with sentiment alignment
•	performance_summary.csv: Statistical summaries grouped by sentiment
Visualizations:
•	Sentiment Distribution: Market emotion frequency analysis
•	PnL by Sentiment: Profit/loss patterns across different market moods
•	Volume Analysis: Trade size variations by sentiment category
•	Win Rate Analysis: Success probability across sentiment states
🎯 Business Impact
This analysis provides actionable insights for:
•	Algorithmic Trading Systems: Sentiment-based strategy implementation
•	Risk Management: Dynamic position sizing based on market emotions
•	Market Timing: Optimal entry/exit point identification
•	Performance Optimization: Strategy adjustment based on psychological factors
________________________________________
This project demonstrates expertise in data analysis, statistical testing, financial market understanding, and practical strategy development for cryptocurrency trading environments.

