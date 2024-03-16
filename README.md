# bootcamp-correlation-analysis

## Background & Goal
The primary objective of this exercise is to discover actionable insights that can improve user adoption rates. By analyzing user engagement and identifying the key factors that drive users to interact with the product more frequently and consistently, we aim to forecast future user adoption.

## Findings
Our analysis of 12,000 users from the `takehome_users.csv` and their engagement from `takehome_user_engagement.csv` has revealed significant findings:

#### 1. User Account Activity Trends
![user_account_age_distribution](https://github.com/clement-hironimus/bootcamp-correlation-analysis/assets/62453600/419bc8b1-5676-4515-9c43-6c8dfaf97ccf)

- Seasonal Patterns in Signups: Semi-annual peaks in user signups suggest the influence of external factors or internal campaigns. Actionable Insight: Investigate the causes behind these peaks to understand what drives user signups and leverage these insights in planning future marketing efforts.
- Increasing Account Creation Rate: The recent uptick in account creation points to a growing interest in the product. Actionable Insight: Capitalize on this momentum with targeted engagement strategies for new users to bolster early adoption.

&nbsp;
#### 2. Engagement Metrics Correlation with Adoption
![spearman_correlation_matrix](https://github.com/clement-hironimus/bootcamp-correlation-analysis/assets/62453600/bd6402ca-b81d-4734-a417-e1a0f3f0e7f4)

- Weekly Engagement: A strong correlation between weekly visit count and user adoption status underscores the importance of regular engagement. Actionable Insight: Incentivize frequent logins with engaging content, features, or rewards that encourage habitual use.
- Recency of Engagement: Negative correlation with days since last visit reaffirms the importance of consistent engagement. Actionable Insight: Implement monitoring systems to identify and re-engage users who are at risk of becoming inactive, using personalized outreach or special offers.

&nbsp;
#### 3. Categorical Variables and User Adoption
![cramer_v_matrix](https://github.com/clement-hironimus/bootcamp-correlation-analysis/assets/62453600/ea08b041-b984-4758-8207-cf2ee4ffc5c0)

- Mailing List and Marketing Drip: The lack of a strong correlation between these marketing strategies and adoption indicates a need for reassessment. Actionable Insight: Revamp marketing communications to better engage users, perhaps by using more personalized and behavior-driven content.
- Organizational Influence: The moderate association between organization IDs and user adoption suggests that certain organizational environments are more conducive to adoption. Actionable Insight: Collaborate with organizations that have high adoption rates to identify best practices and potentially develop tailored features or services for these environments.
- Creation Source: Different creation sources seem to impact adoption rates, although not dominantly. Actionable Insight: Analyze the user experience for each creation source to optimize the onboarding process and identify the most effective channels for user acquisition.

&nbsp;
#### 4. Other Considerations and Further Research

- While creation source and marketing efforts do not show a strong direct impact on user adoption, they contribute to a broader ecosystem of user engagement. Actionable Insight: Further explore other behavioral factors, such as feature usage and responsiveness to onboarding processes, to gain a more holistic understanding of the drivers of adoption.
- User Behavior Post-Signup: The initial interactions of users with the platform can set the tone for ongoing engagement. Actionable Insight: Focus on delivering a compelling user experience right from the start and consider strategies that convert initial interest into sustained engagement.
