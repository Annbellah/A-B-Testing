## Business Understanding
Marketing companies often want to know if their ads will work. To figure this out, they show different versions of the ads to different people at the same time. This is called A/B testing. They want to see which version gets the best results.

To answer two big questions:

Will the ads work?
How much did the ads help?

They usually show most people the ads, but some people see a public service announcement or nothing at all where the ads would normally be. This helps them compare the ads to something else.

In my project, I’m applying a similar approach to evaluate the effectiveness of marketing campaigns. The main objectives are:

Assessing Campaign Success: Determine whether the campaign has a significant impact.
Quantifying Ad Effectiveness: Measure how much of the campaign's success can be directly attributed to the ads themselves.

By using A/B testing, I aim to provide insights into which campaign elements drive the most engagement and how effectively the ads contribute to the overall success of the campaign.

## EDA

#### Univariate Analysis

 We have two test groups. People who saw ads and people who saw the public service announcement. Majority of the people are who saw the ads.
- 97.5% of the people bought the product while 2.5% bought the product.
- Friday is the day most people watched the ads and Tuesday is the least viewed day.
- Most ads were viewed around 1pm and least were viewed around 4pm.

#### Bivariate Analysis

- Monday had the most converted ads while friday had the most ads that were not converted.
- Most of the ad test group converted but keeping in mind of the class imbalance cause most of the people were exposed to ads compared to psa group
- Most of the ads were not converted

## Statistical Testing

#### Observations from the Chi-squared Test
The p-value obtained is exceedingly small, far below the typical threshold of 0.05. This indicates a high level of statistical significance. The chi-square statistic is notably high, which further supports the conclusion that the observed differences are not due to chance.

Given the very low p-value, we can confidently reject the null hypothesis. This indicates a significant relationship between the type of test group (ad vs. PSA) and the conversion outcome. In other words, the type of advertisement significantly affects the likelihood of conversion.

The analysis reveals that the type of advertisement (either 'ad' or 'PSA') has a substantial impact on conversion rates. Further examination is needed to determine which test group—'ad' or 'PSA'—results in higher conversion rates and to understand the underlying factors contributing to this difference.

#### Observations from the Mann-Whitney U test

Based on the results of the Mann-Whitney U test,the p-value is 4.69e-11, which is much smaller than the common significance level of 0.05. Given the extremely low p-value, we reject the null hypothesis. This indicates that there is a statistically significant difference between the distributions of total ads seen by the ad group and the psa group.

The significant p-value reveals that the advertisement has a substantial effect on the number of ads seen compared to the public service announcement. This means that people who saw advertisements saw a different amount of ads compared to those who only saw a public service announcement. This difference shows that advertisements are effective in changing how many ads people notice.

## Conclusions
The analysis shows that advertisements are significantly more effective in engaging people and influencing their behavior compared to PSAs. People exposed to advertisements saw a different amount of ads, and this exposure led to notable differences in conversion rates.

## Recommendations 
- Invest in Effective Ads: Since advertisements have a substantial impact, allocate more resources to developing and deploying effective ad campaigns. Focus on creative and engaging ad content to maximize conversion rates.
- Review and Revise PSAs: Analyze the content and delivery of PSAs to make them more impactful. While PSAs are less effective than ads, improving their quality could still positively influence conversion rates.
- Track Performance Metrics: Continuously monitor key metrics related to ad exposure and conversion rates. Use this data to adjust and improve advertising strategies as needed.