# 📊 Macro Market Regime Analysis Framework

![Python](https://img.shields.io/badge/python-3.8+-blue.svg)
![License](https://img.shields.io/badge/license-MIT-green.svg)
![Status](https://img.shields.io/badge/status-active-success.svg)
![Data Source](https://img.shields.io/badge/data-yahoo%20finance-orange.svg)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange.svg)
![Period](https://img.shields.io/badge/period-2000--2024-blue.svg)

## 📋 Project Overview

**Macro Market Regime Analysis Framework** is an open-source, Python-based financial market analysis tool designed for educational and research purposes. The system provides comprehensive analysis of market regimes across 25 years of historical data (2000-2024), examining performance patterns across 5 major asset classes during 10 distinct market environments.

The tool analyses **5 core asset classes** including US equities, global equities, bonds, gold, and the US dollar. Users can examine any trading year from 2000-2024, making it valuable for historical market research, regime pattern recognition, and understanding how different assets perform under varying market conditions.

## 🎯 Key Features

### 1. **Comprehensive Market Regime Analysis**
* **10 Market Regimes** from 2000-2024 including Dot-com Bubble (2000), Financial Crisis (2007-2009), COVID Crash (2020), and Inflation Shock (2022)
* **Historical Performance** analysis of each regime with detailed metrics
* **Regime Comparisons** across different market environments
* **Optimal Allocation** recommendations based on historical patterns

### 2. **Multi-Asset Performance Metrics**
* **5 Core Asset Classes**: US Stocks (SPY), Global Stocks (ACWI), Bonds (AGG), Gold (GLD), US Dollar (UUP)
* **Comprehensive Metrics**: Annualised returns, volatility, Sharpe ratio, Sortino ratio, maximum drawdown
* **Risk-Adjusted Returns** analysis across all regimes
* **Correlation Analysis** between asset classes in different environments

### 3. **Advanced Analytics Suite**
* **Interactive Dashboards** with Plotly visualisations
* **Performance Heatmaps** showing returns by asset and regime
* **Risk-Return Scatter Plots** for visual performance comparison
* **Correlation Matrices** showing changing relationships during stress
* **Optimal Allocation Pie Charts** based on regime characteristics

### 4. **Technical Implementation**
* **Robust Data Handling** with fallback synthetic data generation
* **Automatic Regime Detection** and classification
* **Professional Visualisations** with consistent colour schemes
* **Modular Architecture** for easy customisation and extension
* **Error-Resilient Design** with comprehensive data validation

## 🔍 What This Project Does

This project analyses how different asset classes perform under various market regimes. It answers critical questions like:
* Which assets perform best during inflation shocks?
* How do bonds behave during equity market crashes?
* What's the optimal allocation during normal growth periods?
* How do correlations between assets change during crises?

## 💡 Why It Does It

Understanding market regimes is crucial for:
* **Risk Management**: Different regimes have different risk characteristics
* **Asset Allocation**: Optimal allocations vary by market environment
* **Performance Expectations**: Setting realistic return expectations based on current market conditions
* **Historical Perspective**: Learning from past market behaviour to inform future decisions
* **Educational Value**: Demonstrating regime-dependent performance patterns

## 💰 Financial Importance

### For Investment Professionals
* **Tactical Asset Allocation**: Adjust portfolios based on identified market regimes
* **Risk Management**: Set appropriate risk limits for current market conditions
* **Performance Attribution**: Understand which market environments favour specific strategies
* **Client Communication**: Explain market conditions and portfolio positioning

### For Researchers & Academics
* **Historical Analysis**: Study asset behaviour across different economic environments
* **Regime Detection**: Develop and test regime identification methodologies
* **Model Validation**: Test portfolio strategies across multiple market environments
* **Educational Tool**: Teach market dynamics and asset class characteristics

### For Individual Investors
* **Context Awareness**: Understand current market environment
* **Expectation Setting**: Realistic return expectations based on regime
* **Portfolio Construction**: Build resilient portfolios for different environments
* **Behavioural Finance**: Avoid emotional decisions by understanding historical patterns

## ⚙️ Technical Implementation

### Data Pipeline

* **Data Sources**: (Yahoo Finance)
* **Data Download**: (yfinance API)
* **Processing**: (pandas DataFrames)
* **Analysis**: (numpy Analytics) 
* **Visualisation**: (Plotly Dashboards)

### Core Technologies
- **Python 3.8+**: Primary programming language
- **yfinance**: Market data download from Yahoo Finance
- **pandas & numpy**: Data manipulation and numerical analysis
- **Plotly**: Interactive visualisations and dashboards
- **scipy**: Statistical analysis and calculations

### Key Functions
1. **Data Download**: Robust data retrieval with fallback mechanisms
2. **Regime Processing**: Extract and analyse data for specific years
3. **Metrics Calculation**: Comprehensive performance and risk metrics
4. **Visualisation Generation**: Professional, interactive charts
5. **Dashboard Creation**: Integrated multi-chart analysis views

## 📊 Analysis Components

### 1. **Regime Analysis Dashboard**
* **Cumulative returns** during the regime
* **Risk-return scatter plot**
* **Correlation matrix**
* **Optimal allocation pie chart**

### 2. **Cross-Regime Comparisons**
* **Annualised returns heatmap**
* **Volatility comparison chart**
* **Sharpe ratio analysis**
* **Risk-return profile scatter**

### 3. **Performance Metrics**
* **Total and annualised returns**
* **Volatility and maximum drawdown**
* **Sharpe and Sortino ratios**
* **Calmar ratio** and **positive days percentage**

### 4. **Allocation Recommendations**
* **Historical optimal allocations** by regime
* **Risk-adjusted allocation suggestions**
* **Dynamic allocation** based on regime characteristics

## 📈 Key Insights

### **Regime-Dependent Performance**
* **Gold** excels during crises (2008, 2020, 2022)
* **Bonds** provide stability during equity stress
* **US Dollar** strengthens during risk-off periods
* **Equities** outperform during recovery phases

### **Risk Characteristics**
* **Volatility** varies significantly by regime
* **Correlations** change during stress periods
* **Maximum drawdowns** are regime-dependent
* **Risk-adjusted returns** differ by environment

### **Practical Applications**
* **Regime Recognition**: Identify current market environment
* **Allocation Adjustment**: Modify portfolios based on regime
* **Risk Management**: Adjust risk exposure appropriately
* **Performance Expectations**: Set realistic return targets

## ⚠️ Limitations & Considerations

### **Data Limitations**
* **Historical Data**: Some assets have limited early history
* **ETF Inception Dates**: Affect analysis of early years
* **Data Quality**: Free Yahoo Finance data has inherent limitations
* **Survivorship Bias**: Only currently traded assets included

### **Analytical Limitations**
* **Past Performance**: Does not guarantee future results
* **Regime Identification**: Historical classification is retrospective
* **Market Evolution**: Future regimes may differ from historical patterns
* **Black Swan Events**: Extreme events are not fully captured

### **Technical Limitations**
* **Data Availability**: Dependent on Yahoo Finance API stability
* **Processing Power**: Large datasets require adequate resources
* **Internet Connectivity**: Real-time data download requires internet access
* **Platform Dependencies**: Some features may vary by Jupyter environment

## 📊 Project Status

This is a **completed portfolio project** that I'm sharing publicly to demonstrate my skills.

## 🌐 Live Dashboard

**Note:** This project includes a web dashboard interface that GitHub cannot display properly.

👉 **Experience the full interactive version:** [hamza-choudhury.github.io](https://hamza-choudhury.github.io)

The live site showcases all interactive features, charts, and controls that make this project unique.

## ☕ Support & Appreciation

If you find this project valuable for your research, education, or professional work, consider supporting its development:

### **One-time Support**
* **PayPal**: [https://paypal.me/HChoudhury0](https://paypal.me/HChoudhury0)
* **Buy Me A Coffee**: [https://buymeacoffee.com/hchoudhury](https://buymeacoffee.com/hchoudhury)

### **Recurring Support**
* **PayPal**: Set up monthly contributions through the link above

### **Other Ways to Support**
* **Star the repository** on GitHub
* **Share with colleagues** who might find it useful
* **Provide feedback** for improvements
* **Contribute code** via pull requests

## ⚠️ Important Disclaimer

### **EDUCATIONAL AND RESEARCH PURPOSES ONLY**

This analysis is provided **STRICTLY** for educational and research purposes. It should **NOT** be construed as:

* **Investment advice** or financial guidance
* **Recommendation** to buy or sell any securities
* **Prediction** of future market performance
* **Substitute** for professional financial advice

### **No Warranty**
The software is provided **"as is"**, without warranty of any kind, express or implied, including but not limited to the warranties of merchantability, fitness for a particular purpose, and noninfringement.

### **Professional Verification Required**
Always verify data with **professional sources** and consult **qualified financial professionals** before making any investment decisions.

### **Data Accuracy Notice**
* **Data** may contain inaccuracies or omissions
* **Free data sources** have inherent limitations
* **Some early year data** is estimated or forward-filled
* **Users should verify** critical data with professional sources

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a **Pull Request**. For major changes, please open an **issue** first to discuss what you would like to change.

### **Areas for Contribution**
1. **Additional Asset Classes**: Expand beyond the 5 core assets
2. **New Regime Definitions**: Add additional market environments
3. **Enhanced Metrics**: Implement additional performance measures
4. **Improved Visualisations**: Add new chart types or interactive features
5. **Documentation**: Improve clarity, examples, or explanations

## 🔗 Related Projects

* **Market Liquidity Intelligence System**: Companion project for liquidity analysis
* **Portfolio Optimisation Toolkit**: Advanced portfolio construction tools
* **Risk Management Framework**: Comprehensive risk analysis system

## 📚 References & Further Reading

### **Academic References**
* **Regime Switching Models**: Hamilton (1989) - Markov switching models
* **Market Regimes**: Ang & Timmermann (2012) - Regime changes and asset allocation
* **Strategic Asset Allocation**: Campbell & Viceira (2002) - Long-term portfolio decisions

### **Practical Guides**
* **Market Cycle Analysis**: Understanding different market phases
* **Asset Allocation**: Modern portfolio theory and practice
* **Risk Management**: Principles of financial risk management

### **Data Sources**
* **Yahoo Finance**: Primary data source for market prices
* **Federal Reserve**: Economic data and indicators
* **Bloomberg/Refinitiv**: Professional market data (alternative)

---

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

**MIT License Summary:**
* **Permission** is granted to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the software
* The software is provided **"AS IS"** without warranty of any kind
* The author is **not liable** for any claims, damages, or other liabilities

---
