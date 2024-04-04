#### Module 14 Challenge: Machine Learning Trading Bot
##### Anvitha Chaluvadi

<p align="center">
<img src = Images/machine-learning.gif width =40% height 30%=/>
</p>

### Background
For this Challenge, you’ll assume the role of a financial advisor at one of the top five financial advisory firms in the world. Your firm constantly competes with the other major firms to manage and automatically trade assets in a highly dynamic environment. In recent years, your firm has heavily profited by using computer algorithms that can buy and sell faster than human traders.

The speed of these transactions gave your firm a competitive advantage early on. But, people still need to specifically program these systems, which limits their ability to adapt to new data. You’re thus planning to improve the existing algorithmic trading systems and maintain the firm’s competitive advantage in the market. To do so, you’ll enhance the existing trading signals with machine learning algorithms that can adapt to new data.

### What You're Creating

You’ll combine your new algorithmic trading skills with your existing skills in financial Python programming and machine learning to create an algorithmic trading bot that learns and adapts to new data and evolving markets.

In a Jupyter notebook, you’ll do the following:

Implement an algorithmic trading strategy that uses machine learning to automate the trade decisions.

Adjust the input parameters to optimize the trading algorithm.

Train a new machine learning model and compare its performance to that of a baseline model.

## Evaluation Report

After thoroughly analyzing and comparing our trading models, I've gathered valuable insights into their performance and potential for future trading strategies. My evaluation process involved a detailed examination of each model's ability to predict market movements and execute profitable trades over time. Here's a summary of my findings and recommendations.

### Insights from the Initial Models

My exploration of various trading models revealed key differences in their performance:

* Certain models excelled at identifying optimal moments for executing buy or sell orders, demonstrating strong predictive capability.
* Others distinguished themselves by effectively differentiating between profitable and unprofitable trades, indicating their potential utility in trading scenarios.

### Journey Through the Models

I experimented with three distinct models, starting with a basic approach, progressing to a Support Vector Machine (SVM) strategy, and concluding with a Logistic Regression model. My goal was to leverage historical price data to automate trading decisions, focusing on the interaction between two moving averages as my primary signal. I simplified my assumptions by considering the ability to trade at the prices from the previous day, acknowledging the limitations of this approach in real-world trading.

* The **Baseline Strategy Returns** model, which relied on simple moving average analysis, showed limited effectiveness. It struggled to provide accurate predictions about future market movements.

<p align="center">
<img src = Images/baseline.png width =60% height 30%=/>
</p>

* The **Support Vector Machine Returns** model demonstrated superior performance, particularly in volatile markets. It proved adept at identifying actionable patterns for buying or selling.

<p align="center">
<img src = Images/SVM-returns.png width =60% height 30%=/>
</p>

* The **Logistic Regression Returns** model underperformed in comparison. Its reliance on moving averages appeared to diminish its predictive accuracy over time.

<p align="center">
<img src = Images/LR-returns.png width =60% height 30%=/>
</p>

### Recommendations for Future Trading

Based on my comprehensive review, I recommend the **Support Vector Machine Returns** model as the most promising option for trading. It outperformed the **Logistic Regression Returns** model and displayed significant potential for generating profits while managing risk effectively.

The **Support Vector Machine Returns** model showcased an ability to enhance returns over time and navigate market volatility successfully. Therefore, I advise considering this model for real-world trading applications, and monitoring its performance as market conditions evolve.