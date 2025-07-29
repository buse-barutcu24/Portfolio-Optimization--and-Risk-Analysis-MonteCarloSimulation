# Portfolio-Optimization--and-Risk-Analysis-MonteCarloSimulation
Portfolio optimization and risk analysis project using financial data, knowledge and python.

Summary: In this project, I worked on portfolio optimization, risk measurement, and performance evaluation for an investment universe of 20 stocks selected from both emerging (Turkey) and developed (US) markets. I aimed to identify the optimal portfolio that provides high risk-adjusted returns and to analyze, understand, and evaluate this portfolio from various perspectives. 
-So why did I choose these stocks for my study? My project includes major US companies like Apple, Microsoft, and Pepsi, as well as Turkish companies like Mavi, Şişecam, and Tüpraş. Furthermore, the markets in which these companies operate vary. My goal is to provide market diversity while also conducting both global and local analyses. This structure also provided systematic risk reduction. I automatically pulled all stock data from yfinance. I also must say that I used data from the past year to reflect current market conditions in my analysis.

In portfolio optimization, I calculated the annual expected return, volatility, and Sharpe ratio for each of 10,000 randomly weighted portfolios. A Monte Carlo simulation generated numerous probability-based scenarios, and from these scenarios, the optimal portfolio with the maximum Sharpe ratio was selected.

As seen in my project, the annual expected return of our selected optimal portfolio is 18.29%, annual volatility (risk): 17.15%, and a sharpe ratio of 0.78. The optimal portfolio optimizes return based on risk. While a Sharpe ratio below 1 is limited, it offers a positive return and a controlled risk structure. Our minimum risk portfolio also incorporates its own ratios into our project. Despite its low return, it is a suitable alternative for investors seeking lower risk.

Then, using Backtest, I tested how the portfolio strategy I created performed against historical data. As shown in the project, the Final Cumulative Return was 16.05%. The S&P 500 return during the same period was approximately 16.95%. This study showed that while the 15.98% return is independently significant and positive, the portfolio, even though theoretically optimized, lags slightly behind the market index.

After that, I looked for the Risk Measurements: Value at Risk (95%): -1.52%, which means This means that there's a probability that the portfolio can lose a maximum of 1.52% in a single day. A controlled risk ratio of less than 2% indicates that it is protected against sudden market fluctuations. Conditional VaR (CVaR): -2.38%. So In the worst-case scenario, an average loss of 2.38% is projected. In this case, the CVaR negative is higher than the VaR. This suggests that in extremely bad situations, losses can be greater than the VaR, but they are still measurable. This indicates that our portfolio does not suffer severe losses even during times of crisis. Max Drawdown: -14.55%. While this value isn't particularly high, it's certainly enough to be worrying for long-term investors. However, considering that stock market indices have seen declines of up to -30%, we can say this portfolio is recoverable and not that much of a big deal. Furthermore, the positive cumulative yield offsets the decline. So no doubt to say that the portfolio avoids large losses and carries an acceptable level of risk.

I then examined the Risk Contribution This analysis once again highlighted the need to pay attention not only to weighting but also to volatility and correlation.

What can be inferred from the Rolling Sharpe Ratio is that, according to the 60-day moving average analysis, the portfolio has become quite efficient in recent periods, although it has experienced fluctuations over time.
You can gain deaper insights and broader observations by reviewing my project in detail.

-What I learned from this study:
Working with data, I saw a simulation of how each metric (VaR, CVaR, drawdown, Sharpe...) would actually observe a different dimension of risk.
I observed and improved my skills in extracting, analyzing, and visualizing financial data using Python. And I rediscovered my passion for this.
Here, I observed once again that structures that achieve a balance of risk and reward, rather than those that simply maximize return or minimize risk, are more sustainable in the long run.
I realized the importance of a multifaceted approach, leading to broader observations, rather than simply focusing on a single metric.
And finally, I had the opportunity to experience the satisfaction of applying concepts like portfolio theory, risk management, variance-covariance matrices, and risk contribution in practice, just as I enjoyed hearing about them from my professor in school.

-Buse BARUTÇU
