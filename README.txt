Bryan Zhao, Darren Nguyen, Zayaan Atif

Predictive Model for Vanguard Information Technology Index Fund (VGT) using commodity price data as features.

Data Sources: 
yfinance
Reddit: 'r/news', 'r/worldnews', 'r/breakingnews', 'r/globalnews', 'r/wallstreetbets', 'r/stockmarket', 'r/stocks', 'r/trading', 'r/daytrading', 'r/economics',  and 'r/economy'.

Features: 
GLD: SPDR Gold Shares (Spot Price)
SLV: iShares Silver Trust (Spot Price)
PPLT: abrdn Physical Platinum Shares (Spot Price)
CPER: United States Copper Index Fund (Futures)
USO: United States Oil Fund (Futures)
UNG: United States Natural Gas Fund (Futures)
WEAT: Teucrium Wheat Fund (Futures)
SOYB: Teucrium Soybean Fund (Futures)
CORN: Teucrium Corn Fund (Futures)

Models:
Logistic Regression (LR)
K-Nearest Neighbors (KNN)
Extreme Gradient Boosted Classifier (XGB)
Artificial Neural Network (ANN)
Sentiment Analyzer “tabularisai/multilingual-sentiment-analysis”

The best-performing model was the Extreme Gradient Boosted Classification. It had a precision score of 65.8% and an F-Beta score of 68.5%.

The most important features for VGT are precious metals such as copper, silver, and gold. 
