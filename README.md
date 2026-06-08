# Marketing_Campaign_AB_Test

# Business Context and Goal
To generate additional revenue, an AD campaign was run in order to drive more conversions, and to identify whether or not the lift in conversions from ad group was because of only ads 

# Problem Statement 
**Did showing ads actually make people buy?**


## Table of Contents 
- [North Star Metrics](#north-star-metrics)
- [Executive Summary](#executive-summary-did-showing-ads-actually-make-people-buy)
- [Inisghts](#insights)
- [Recommendations](#recommendations)



## North Star Metrics

- conversion_rate :- pct of users convertng after seeing an AD

### Outcome of North Star Metrics
- For conversion_rate,
  - A downward trend decreases the revenue 🔻
  - An upward trend increases the revenue ⬆️
 
# Executive Summary: Did showing ads actually make people buy?

This analysis evaluated the effectiveness of a digital advertising campaign using an **A/B test** conducted on approximately **588,000 users**. Users were exposed either to an **advertisement (treatment group) or a public service announcement (control group)**, with the objective of measuring the impact on conversion rates.

The results indicate that the advertising campaign was successful. **The ad group achieved a conversion rate of 2.55%, compared to 1.79% for the PSA group, representing a 43% relative lift in conversions**. A **chi-square test confirmed that this difference is statistically significant (p < 0.001), indicating that the observed uplift is highly unlikely to have occurred by chance**.

Further analysis revealed a strong **positive relationship between ad exposure frequency and conversion performance**. Users exposed to higher volumes of advertisements consistently demonstrated higher conversion rates, reaching approximately 17% among users who viewed 100 or more ads. This suggests that **increased exposure is associated with stronger conversion outcomes**.

Time-based analysis identified clear performance patterns. **Monday generated the highest conversion rate among weekdays**, while the **strongest-performing hours were concentrated in the afternoon (14:00–16:00) and early evening (20:00–21:00)**. These periods represent potential opportunities for more efficient advertising spend allocation and campaign scheduling.


### Conclusion 

Several limitations should be considered when interpreting the findings. The experiment groups were heavily imbalanced, with approximately 96% of users assigned to the ad group and only 4% to the PSA group. While the statistical testing accounts for this imbalance, it may still affect the robustness of direct group comparisons.

Additionally, the dataset does not provide information about the user assignment methodology. As a result, it is not possible to verify whether exposure was fully randomized. **Therefore, the observed relationship between ad frequency and conversion may reflect that the users to which ads were exposed already had a high intent rather than the direct effect of increased ad exposure**.



## Insights

- ### Insight 1 :- The groups are not equal. Exactly 96% of users are in the ad group and only 4% saw the PSA. This is not a balanced experiment
<img width="552" height="516" alt="Screenshot 2026-06-08 at 8 49 47 AM" src="https://github.com/user-attachments/assets/87ccaf41-923a-4ded-90ec-cf7962871202" />

- ### Insight 2 :- The ad group converts at 2.55% and the PSA group at 1.79% 
<img width="820" height="490" alt="Screenshot 2026-06-08 at 8 57 20 AM" src="https://github.com/user-attachments/assets/ddcdd5e8-e25a-4c72-b83d-907880a15282" />

- ### Inisight 3 :- Monday is the strongest at 3.32%, with Saturday the weakest at 2.13%. The spread across the week is 1.19 percentage points — noticeable but not dramatic
<img width="920" height="488" alt="Screenshot 2026-06-08 at 9 00 08 AM" src="https://github.com/user-attachments/assets/bca52382-0e9a-4333-b0d2-82acc3c20fe4" />

- ### Insight 4 :- The top hours are 16:00 (3.09%) and 20:00 (3.03%), followed closely by 15:00 and 21:00. Mid-to-late afternoon and early evening consistently outperform other time windows.
<img width="989" height="590" alt="Screenshot 2026-06-08 at 9 11 55 AM" src="https://github.com/user-attachments/assets/a0a2bcd1-4cc8-4b06-ae2a-c4a1790df0ce" />

- ### Inisght 5 :- That's a relative lift of 43% — users who were shown AD converted more.
- ### Insight 6 :- Statistical Significance - the probability of seeing a difference this large by chance is essentially zero
chi-square of 54.01 and a p-value of 2e-13







# Recommendations

- Continue investing in the advertising campaign, as it delivers a statistically significant uplift in conversions.
- Prioritize campaign delivery during high-performing periods, particularly Mondays and the 14:00–16:00 and 20:00–21:00 time windows.
- Explore frequency optimization strategies to determine the ideal level of ad exposure before diminishing returns occur.
- Conduct additional experiments with balanced treatment and control groups to strengthen causal conclusions and improve result reliability.
  
