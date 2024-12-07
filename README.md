# A-Comparative-Analysis-of-the-S-P-500-and-CSI-300-Using-Various-Risk-Metrics
This project analyzes the S&amp;P 500 and CSI 300 indices using Value-at-Risk (VaR) and Conditional Value-at-Risk (CVaR) methodologies to assess risk at 95% and 99% confidence levels. By employing multiple models and a traffic light system to classify risk, it provides insights into portfolio management strategies and highlights vulnerabilities in volatile markets.

## Project Overview:

In the realm of financial risk management, assessing and comparing the returns of major indices such as the S&P 500 and CSI 300 is paramount. These indices serve as barometers for the performance of the U.S. and Chinese stock markets, respectively, making an understanding of their behavior crucial for investors and institutions alike. This research project delves into a comparative analysis of the returns of these two indices using various risk measures, including Value-at-Risk (VaR) and Conditional Value-at-Risk (CVaR) methodologies.

Our research is driven by the goal of enhancing risk management strategies through a comprehensive understanding of risk-return dynamics. We employ various risk measures, including Value-at-Risk (VaR) and Conditional Value-at-Risk (CVaR), to identify potential losses within specified confidence levels and time horizons. By extending our analysis to include CVaR, which quantifies expected losses beyond VaR thresholds, we gain deeper insights into portfolio risk. Additionally, our backtesting approach using the Traffic Light Test ensures the reliability of our findings and helps refine risk management strategies, particularly in volatile market conditions.

## Key Objectives:

Compare Risk Metrics: Evaluate the S&P 500 and CSI 300 indices using historical, normal, and exponentially weighted moving average (EWMA) approaches for VaR and CVaR.
Traffic Light System: Employ a traffic light (TL) representation to classify risk levels (Green: Low, Yellow: Moderate, Red: High).
Confidence Levels: Analyze results at both 95% and 99% confidence levels to uncover vulnerabilities and provide actionable insights.
Methodology

## Data Collection:

The data for this study were collected from Investing.com and Yahoo Finance websites, covering a time span of 14 years from January 1, 2010, to January 1,
2024. Two major indices, namely the S&P 500 and CSI 300, were selected for analysis.

The methodology involved the implementation of a rolling window approach to compute the Value-at-Risk (VaR) and Conditional Value-at-Risk (CVaR) every four years. Three different approaches were utilized for the calculation of VaR and CVaR: Historical, Normal, and Equally Weighted Moving Averages Approach.

These approaches were employed to estimate potential losses and tail risks associated with the S&P 500 and CSI 300 indices over the specified time horizon.
The analysis aimed to provide valuable insights for risk management and portfolio allocation decisions.

## Risk Models:

VaR: Measures the potential loss in value over a defined period for a given confidence level.
CVaR: Quantifies expected losses beyond the VaR threshold, providing a deeper insight into tail risk.
Three modeling approaches:
Historical Approach
Normal Distribution Approach
EWMA (Exponentially Weighted Moving Average) Approach

## Analysis:

Our study investigate the comparative risk profiles of the S&P 500 and CSI 300 indices, employing VaR and CVaR methodologies with rolling windows and diverse modeling techniques. At the 95% confidence level, both indices exhibit commendable risk management performance across all methodologies, characterized by minimal failures and green Traffic Light (TL) statuses. This suggests a consistent ability to anticipate and manage potential losses within the specified confidence interval.

However,as we delve deeper into the 99% confidence level, intriguing distinctions emerge. The S&P 500 demonstrates a notable increase in failures, particularly evident with the Normal VaR model, leading to a red TL status. This signals a deviation from expected risk levels and underscores potential vulnerabilities in risk management strategies. In contrast, the CSI 300 presents a contrasting picture, with a lower incidence of failures across models, albeit with some caution warranted, especially with the Normal VaR model. Notably, the Historical VaR model for the CSI 300 maintains a green TL status, indicating satisfactory risk management performance even at this heightened confidence level.

The Traffic Light system, integrated into our analysis, provides an intuitive framework to classify and visualize risk levels. By categorizing results into Green (low risk), Yellow (moderate risk), and Red (high risk), it highlights areas requiring attention and reinforces key findings. This approach enables stakeholders to make more informed investment decisions, tailoring strategies to mitigate risks effectively.

## Conclusion:

These findings highlight the nuanced risk dynamics inherent in global financial markets and underscore the critical role of dynamic risk assessment methodologies. Understanding these differences between the S&P 500 and CSI 300 enables investors and risk managers to tailor their strategies effectively, ensuring resilience and adaptability in the face of volatile market conditions. By incorporating such insights, stakeholders can navigate uncertainties with greater confidence, thereby fostering more robust and informed investment decisions.

Our study offers valuable insights into the risk profiles of the S&P 500 and CSI 300 indices, providing a foundation for informed decision-making in portfolio management and risk mitigation. Moving forward, further research and refinement of risk assessment methodologies will be essential in enhancing our understanding and management of financial market risks.


## References:

Cogneau, P. “Backtesting Value-at-Risk: how good is the model?  Intelligent Risk, PRMIA, July, 2015.

Rockafellar, R. T. and S. Uryasev. "Conditional Value-at-Risk for General Loss Distributions." Journal of Banking and Finance. Vol. 26, 2002, pp. 1443–1471.
