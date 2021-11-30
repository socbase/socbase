## Get data from cnbc.com

Step 1: install library python
```pip install cnbcfinance```
Step 2: Get history or get quote realtime
# Get history data
```from cnbcfinance import get_history_df```
```data = get_history_df('AAPL', '30m')```
# Get quote
```from cnbcfinance import get_history_df```
```data = get_quota('AAPL')```
