# Bitcoin Market Sentiment & Trader Performance Analysis

## 📊 Project Overview

This project explores the relationship between Bitcoin market sentiment and trader performance using data from Hyperliquid, a decentralized perpetual exchange. The analysis reveals counter-intuitive patterns about how traders perform during different market sentiment periods.

## 🎯 Objectives

- Analyze the correlation between market sentiment (Fear/Greed Index) and trader performance
- Identify hidden patterns in trading behavior across sentiment periods
- Provide actionable insights for smarter trading strategies
- Benchmark individual trader performance metrics

## 📈 Key Findings

### 🔍 Counter-Intuitive Discovery
**Traders perform significantly better during Fear periods than Greed periods:**
- **Fear periods**: $209,372.66 average PnL (93.8% win rate)
- **Greed periods**: $99,675.52 average PnL (84.4% win rate)
- **Extreme Greed**: Only $35,393.10 average PnL (40% win rate)

### 📊 Performance Metrics
- **Total traders analyzed**: 32
- **Profitable traders**: 31 (96.9%)
- **Total combined PnL**: $10,225,249.60
- **Average PnL per trader**: $319,539.05
- **Overall win rate**: 86.2%

## 🗂️ Data Sources

### 1. Bitcoin Market Sentiment Dataset
- **Source**: Fear & Greed Index
- **Columns**: Date, Classification (Fear/Greed/Neutral/Extreme Greed)

### 2. Historical Trader Data from Hyperliquid
- **Columns**: account, symbol, execution price, size, side, time, start position, event, closedPnL, leverage

## 🔬 Analysis Components

### 1. Sentiment-Based Performance Analysis
- **77 trading sessions** analyzed across sentiment periods
- Performance metrics segmented by Fear, Greed, Neutral, and Extreme Greed
- Trading activity patterns and volume analysis

### 2. Individual Trader Profiling
- **Top 10 performers** detailed breakdown
- Risk profile categorization (Conservative vs High Leverage)
- Activity level segmentation (High vs Low Activity)

### 3. Behavioral Pattern Recognition
- Trading frequency correlation with sentiment
- Win rate variations across market conditions
- Position sizing and leverage usage patterns

## 📋 Key Metrics Analyzed

### Performance Indicators
- **Profit & Loss (PnL)**: Total and daily averages
- **Win Rate**: Percentage of profitable trades
- **Sharpe Ratio**: Risk-adjusted returns
- **Trading Volume**: Number of trades per period

### Risk Metrics
- **Leverage Usage**: Position sizing relative to account
- **Drawdown Analysis**: Maximum loss periods
- **Volatility Measures**: Performance consistency

## 🏆 Top Performers

| Rank | Trader Address | Total PnL | Daily Avg | Win Rate | Trading Days |

## 🎯 Strategic Insights

### 1. Sentiment-Based Trading Strategy
- **Increase position sizes during Fear periods** - historically show 2x better performance
- **Reduce exposure during Extreme Greed** - lowest win rates and returns
- **Monitor sentiment transitions** for optimal entry/exit points

### 2. Risk Management Recommendations
- Conservative leverage strategies show consistent profitability
- High-activity trading correlates with better returns
- Diversification across sentiment periods reduces overall risk

### 3. Market Timing Insights
- Fear periods present optimal trading opportunities
- Greed periods require more cautious approach
- Neutral periods show mixed results (50% win rate)

## 🛠️ Technical Implementation

### Data Processing Pipeline
1. **Data Integration**: Merge sentiment data with trading records by date
2. **Feature Engineering**: Calculate daily PnL, win rates, and risk metrics
3. **Sentiment Classification**: Map dates to Fear/Greed categories
4. **Performance Aggregation**: Group metrics by trader and sentiment period

### Analysis Framework
- **Statistical Analysis**: Correlation and significance testing
- **Performance Benchmarking**: Comparative analysis across periods
- **Risk Assessment**: Leverage and volatility measurements
- **Behavioral Analysis**: Pattern recognition in trading habits

## 📊 Visualization Outputs

The analysis includes comprehensive visualizations covering:
- PnL distribution across sentiment periods
- Win rate comparisons by market condition
- Trading activity heatmaps
- Individual trader performance rankings
- Risk-return scatter plots


## 📝 Conclusion

This analysis reveals that market sentiment is a powerful predictor of trading performance, with Fear periods consistently outperforming Greed periods. The findings challenge conventional wisdom and provide a data-driven foundation for sentiment-based trading strategies.

The research demonstrates that successful trading often involves contrarian thinking - performing best when market sentiment is most pessimistic. This insight, combined with proper risk management and position sizing, can significantly improve trading outcomes.

---

