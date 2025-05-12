# Emily's Retirement Financial Simulation

## Project Overview

This project is a comprehensive financial simulation designed to help Emily, a 30-year-old data analyst, effectively plan for her retirement. It provides a detailed analysis of Emily’s current superannuation strategy, projects her future retirement savings, and suggests tailored recommendations to ensure financial stability and sustainability post-retirement.

## Key Features

* Monte Carlo simulation for projecting superannuation growth (conducted in Excel).
* Customized superannuation contribution strategy.
* Risk assessment of current and proposed investment portfolios.
* Analysis of three investment funds: Stable Bonds Fund, Balanced Hybrid Fund, and SkyHigh Equity Growth Fund.
* Recommendations for fund reallocation and contribution adjustments.

## Project Structure

* **Executive Summary**: An overview of Emily's financial situation and the primary recommendations for her retirement strategy.
* **Introduction**: Explanation of the importance of retirement planning and a background on Emily's current financial status.
* **Superannuation Strategy Review**: Detailed analysis of Emily's existing fund allocation and contribution strategy.
* **Projection Methodology**: Explanation of the Monte Carlo simulation method (Excel) used for fund growth projection.
* **Analysis Framework**: Methodology for data collection, simulation, and risk assessment.
* **Conclusion**: Final recommendations for optimizing Emily’s retirement plan.

## SUPERANNUATION STRATEGY REVIEW
Evaluation of Current Superannuation Investment Allocation
The current allocation strategy of the superannuation fund divides her contribution into three funds: 40% in Stable bonds fund, 40% into Balanced fund and 20% into SkyHigh.
[table]
[fig]
The low growth rate of the stable fund may not align with Emily’s long-term need for higher returns to meet her retirement goals. While a slightly higher allocation to SkyHigh could enhance her returns while maintaining acceptable risk, the balanced fund aligns well with her short-term goals.
Table 1: Invested Funds
Fig 1: Current Fund Allocation
Assessment of Contribution
Currently, she contributes 3% of the salary, matched by her employer. This results in an annual contribution of NZD 4601.43. Assuming an average salary growth of 3.5% with 0.7 as standard deviation, and her contributions scale proportionately:
● The current contributions may not suffice to achieve her retirement lifestyle envisioned since other factors like inflation, increase in taxes, healthcare cost can affect the spending and saving rates.
● To match her goals, increasing the contribution from the 3% threshold is advisable, since the employer would also match her contribution up to 10%.
Based on the volatility of each fund, we can calculate the risk score for Emily's investment portfolio. The calculation is attached in the appendix (refer Appendix A.1) for the same:
● Stable Bonds Fund has a volatility of 4%, so the weight for risk score is 1.
● Balanced Hybrid Fund has a volatility of 8.5%, so the weight for risk score is 2.12.
● SkyHigh Equity Growth Fund has a volatility of 20.5%, so the weight for risk score is 5.12.
Using these figures, we calculate the overall portfolio risk score:
● The current Risk Score for Emily’s superannuation investments is 44.
● This risk score of 44 places Emily’s portfolio in the medium to high-risk category, reflecting a significant exposure to market volatility, especially due to the 20% steady allocation in the high-risk SkyHigh Fund.
To maintain her current lifestyle, including travel and leisure activities, Emily will need an average of NZD 130,000 per year post-retirement life. To reach this goal, she should gradually increase her superannuation contributions in a way that balances growth and stability. This will help her build a solid retirement fund while minimizing risks over time.
Recommendations for Adjustments
Emily is currently contributing 3% of her salary to her superannuation fund. Based on this contribution and her current investment choices, we estimate that her superannuation balance when she reaches 65 will likely fall between $1.21 million and $1.29 million, considering the past performance of her chosen funds.
However, this amount will not be enough to support Emily’s desired retirement lifestyle, which includes maintaining her current standard of living and her travel and leisure activities. As per our calculation, she should have an average of NZD 130000 per year post-retirement, which means she needs to increase her current contribution and investment strategy.
1. Reallocation of Equity: Adjust allocation in Stable, Balanced, and SkyHigh to balance risk and maximize growth , optimization technique was used to obtain maximum return with respect to risk constraints (refer Appendix A.2).
2. Increase Contributions: Raise contributions from 3-10% of her salary to build a larger retirement corpus.
3. Rebalance Periodically: Review the portfolio every 5 years to adjust risk as retirement approaches.
## Dependencies

* Excel (for Monte Carlo simulation)

## How to Contribute

Contributions are welcome. Please fork the repository and create a pull request with a clear explanation of your changes.


