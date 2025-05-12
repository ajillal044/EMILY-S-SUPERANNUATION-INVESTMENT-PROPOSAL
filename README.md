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
![Image](https://github.com/user-attachments/assets/b38b19f8-d3ab-4c34-bead-3be4b04684b8)
![Image](https://github.com/user-attachments/assets/4d0ea9ca-9372-40d1-aad7-d6b70eebf722)
The low growth rate of the stable fund may not align with Emily’s long-term need for higher returns to meet her retirement goals. While a slightly higher allocation to SkyHigh could enhance her returns while maintaining acceptable risk, the balanced fund aligns well with her short-term goals.
Table 1: Invested Funds
Fig 1: Current Fund Allocation
## Assessment of Contribution
Currently, she contributes 3% of the salary, matched by her employer. This results in an annual contribution of NZD 4601.43. Assuming an average salary growth of 3.5% with 0.7 as standard deviation, and her contributions scale proportionately:
* The current contributions may not suffice to achieve her retirement lifestyle envisioned since other factors like inflation, increase in taxes, healthcare cost can affect the spending and saving rates.
* To match her goals, increasing the contribution from the 3% threshold is advisable, since the employer would also match her contribution up to 10%.
Based on the volatility of each fund, we can calculate the risk score for Emily's investment portfolio. The calculation is attached in the appendix (refer Appendix A.1) for the same:
  * Stable Bonds Fund has a volatility of 4%, so the weight for risk score is 1.
  * Balanced Hybrid Fund has a volatility of 8.5%, so the weight for risk score is 2.12.
  * SkyHigh Equity Growth Fund has a volatility of 20.5%, so the weight for risk score is 5.12.
Using these figures, we calculate the overall portfolio risk score:
  * The current Risk Score for Emily’s superannuation investments is 44.
  * This risk score of 44 places Emily’s portfolio in the medium to high-risk category, reflecting a significant exposure to market volatility, especially due to the 20% steady allocation in the high-risk SkyHigh Fund.
To maintain her current lifestyle, including travel and leisure activities, Emily will need an average of NZD 130,000 per year post-retirement life. To reach this goal, she should gradually increase her superannuation contributions in a way that balances growth and stability. This will help her build a solid retirement fund while minimizing risks over time.
## Recommendations for Adjustments
Emily is currently contributing 3% of her salary to her superannuation fund. Based on this contribution and her current investment choices, we estimate that her superannuation balance when she reaches 65 will likely fall between $1.21 million and $1.29 million, considering the past performance of her chosen funds.
However, this amount will not be enough to support Emily’s desired retirement lifestyle, which includes maintaining her current standard of living and her travel and leisure activities. As per our calculation, she should have an average of NZD 130000 per year post-retirement, which means she needs to increase her current contribution and investment strategy.
1. Reallocation of Equity: Adjust allocation in Stable, Balanced, and SkyHigh to balance risk and maximize growth , optimization technique was used to obtain maximum return with respect to risk constraints (refer Appendix A.2).
2. Increase Contributions: Raise contributions from 3-10% of her salary to build a larger retirement corpus.
3. Rebalance Periodically: Review the portfolio every 5 years to adjust risk as retirement approaches.
   ![Image](https://github.com/user-attachments/assets/9c71be95-9654-4ab3-96f3-6d255a0c671d)
   ![Image](https://github.com/user-attachments/assets/709ba2c8-adb4-45fb-b77e-49ff0e00fb31)
## PROJECTION METHODOLOGY
To project the future value of Emily's superannuation fund, considering the variability in salary increases and fund performance, we use a Monte Carlo simulation approach. This method captures the impact of uncertainties and generates a range of potential outcomes.
Salary Growth: Grows annually based on a random normal distribution with a mean growth rate of 3.5% (±0.7%).
Contributions: Emily contributes 3% of her gross salary, with a matching contribution from her employer (up to 3%) and annual government contributions of NZD 521.43.
Investment Allocation: The annual growth of each fund is modelled using random sampling from their respective distributions, reflecting market uncertainty.
Fund Balances: The balance of each fund grows based on its rate of return, and contributions are added proportionally.
Inflation: According to the statistics, the NZ inflation rate is between 2-3% and now it is at 2.2%. All the future expenses were calculated using the inflation, since the expenses are bound to increase with the change.
Monte Carlo Approach: Multiple simulations were performed to estimate the range of possible outcomes for Superannuation fund by calculating the expected value of fund at retirement and confidence interval, providing a range for the likely final balance.
To achieve Emily’s financial goals, we recommend a slab-wise increase in superannuation contributions and adjustments to her fund allocation.
1. Contribution Increase Strategy
  * Gradual contribution increases from 3% to 10% over the next 25 years, incrementing by 1-2% every 5 years.
  * With employer matching, contributions effectively double, enhancing savings while ensuring returns, significantly.
  * Utilizes approximately 22% of unused salary balance, while reducing taxable income.
2. Portfolio Reallocation for Stability: Fund allocation adjustments as contributions increase:
   * Slab 1 (4% Contribution): Stable (20%), Balanced (60%), SkyHigh (20%) — Risk Score: 49 (medium-high risk).
   * Slab 2 (6% Contribution): Stable (20%), Balanced (70%), SkyHigh (10%) — Risk Score: 43 (medium risk).
   * Slab 3 (8% Contribution): Stable (40%), Balanced (50%), SkyHigh (10%) — Risk Score: 38 (low-medium risk).
   * Slab 4 (10% Contribution): Stable (60%), Balanced (40%), SkyHigh (0%) — Risk Score: 28 (low risk).

Overall Risk Score became 39 (Medium-low)
![Image](https://github.com/user-attachments/assets/a8c1006a-e952-4137-beb0-237f93cb8fba)

Increased superannuation contributions can lead to tax savings, enhancing the net retirement savings.
3. Projected Outcome:
* By aligning contributions and allocations with her salary growth and risk tolerance, Emily’s superannuation fund can grow to NZD 2.35 Million by retirement.
* This corpus will adequately cover her retirement goals, factoring in inflation (2–3%) and life expectancy projections.
* She can withdraw the required amount annually for her post-retirement life expenses, thereby continuously getting returns of the balance amount.
* Based on our analysis, Emily will need approximately NZD 98,000 annually at the beginning of her retirement, with expenses expected to rise in line with inflation. Considering projected investment returns, she can withdraw up to a maximum of NZD 180,000 per year (refer Appendix C.4), with the surplus serving as a contingency fund for unforeseen circumstances.
## Dependencies

* Excel (for Monte Carlo simulation)

## How to Contribute

Contributions are welcome. Please fork the repository and create a pull request with a clear explanation of your changes.


