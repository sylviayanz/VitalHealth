# Vital Health Marketing Insights - Project Overview

## The goal of this project is to investigate the performance of marketing campaigns at Vital Health in order to surface recommendations on marketing budget allocation across future campaign categories.

Founded in 2016, Vital Health is a medical insurance company serving over thousands of customers throughout the United States. In 2019, they launched a new set of marketing campaign categories spanning topics like wellness tips, the affordability of their plans, and preventative care. Their customers can sign up for 4 different plans - bronze, silver, gold, and platinum - each with different premiums and claim coverage rates.

Now that they’ve hired a new data team and are strategizing their marketing budget for the year, the company would like to build more understanding of the effectiveness of these campaign categories and how they relate to signups and subsequent patient claims. The budget is allocated to drive two primary objectives: 1) to increase the number of customer signups, and 2) to raise awareness of Row Health’s brand across the country.


# Dataset Structure

The dataset consisted of three tables, including information about **campaigns, signups** and **user demographics**, as well as **claims** filed by customers and related claim information.

![image](https://github.com/user-attachments/assets/2926bf12-68b8-4088-8081-34a7cec1b214)


# Insights Summary
## North Star Metrics

In order to evaluate campaign performance, we focused on the following key metrics:

-    **Impressions:**  The number of people who saw a marketing campaign.
-   **Cost per Click (CPC):**  the amount an advertiser pays each time a user clicks on their advertisement
-   **Signup Rate:**  The percentage of people who see a campaign and subsequently sign up for a Vital Health plan.
-   **Cost per Signup:**  The average dollars spent in order to acquire a signup from each campaign.
-   **Click through Rate (CTR):**  The percentage of people who see a campaign and click on the associated link.

##  Marketing Insights


-   Despite achieving the highest number of impressions (1.3M), the  **Tailored Health Plans** campaign  category has the third lowest click-through rate (7%), which indicates a potential disconnect between the campaign content and the target audience's interests.

-   The **#HealthyLiving and Tailored Health Plans campaigns** have nearly identical total impressions (1.36M vs. 1.31M) but show notable performance differences. #HealthyLiving achieves a higher CTR (10% vs. 7%) and the same CPC. This suggests that the #HealthyLiving content resonates more effectively with audiences despite targeting a similar volume of potential customers.

-   Across categories,  **Health for All and Benefit Updates** performed around 3-4x better than the average CTR at 36% and 22%, respectively.

-   The  **Golden Years Security** campaign has the lowest CTR at 1.7%, resulting in a disproportionately low number of clicks relative to its cost and an abnormally high CPC of $0.48. In contrast, the remaining campaigns are more efficiently budgeted, with CPCs ranging between $0.03 and $0.05.

-   **Family Coverage Plan** had high impressions but no clicks - this needs to be investigated and could be due to missing data or issues with the campaign.

##  Signup Insights

-   **In April 2020, all campaign categories exhibited a significant increase in signups attributed to elevated demand for healthcare products during the pandemic.** While this initially enhanced performance metrics, most segments demonstrated a downward trajectory from mid-2022 onwards, with 2023 signups dropping below pre-pandemic benchmarks. However, the #CoverageMatters and #HealthyLiving segments displayed notable resilience, collectively comprising approximately 57% of mid-2023 signups.

-   **The Health For All campaign category demonstrated superior performance metrics**, generating 3.5k signups with a signup rate of 3%, approximately 15x above the aggregate benchmark. Analysis indicates this elevated performance correlates directly with the Health Awareness campaign subset, which exhibited the highest signups efficiency across all campaign categories (3.72%).

-   **Golden Years Security has the lowest signup count (23) and the lowest signup rate (0.01%)** despite having the extremely highest cost per signup ($124).

-   Despite its strong click-through rate, **the Benefit Updates campaign category had the second lowest signups (45) and signup rate (0.02%)**, along with the second highest cost per signup at $45.

-   Notably, the #HealthyLiving category had the highest number of signups but a relatively low signup rate of 0.3%.

-   Within the two campaign categories with the highest cost per signup, info-based campaign types (like offers and policy info) drove high costs per signup. Also, some COVID-based campaigns also had abnormally high CACs at $1.2-$1.3K.

## Claims Insights

-   Claim metrics demonstrated an upward correlation with the pandemic's onset, increasing alongside signup rates, and have maintained stability across the majority of campaign segments, with the exception of the **Compare Health Coverage** campaign.
-   The **Compare Health Coverage campaign exhibited a consistent positive trajectory throughout 2021-2022**, reaching peak performance at $173K in July 2022, followed by a substantial decrease in subsequent periods, attributed to a corresponding reduction in claim frequency. 

-   The Compare Health Coverage campaign customers generated the highest average claim value ($410) and maximum total claims. Within this segment, the **Customer Testimonial campaign type drove the highest aggregate claim volume ($2.9M) and per-claim average ($499)**.


# Recommendations

Recommendations focus on two strategies: removing ineffective campaign categories and reallocating budget towards categories with better performance across north star metrics.

-   **Health for All**: Reallocate budget from Golden Years Security, which has high cost per acquisition, to Health for All campaigns. The second category outperforms across all key metrics, especially high CTR(36%), and signup rate(2.9%).
-   **Health Awareness**: Within Health for All campaigns, focus on health awareness-type marketing, and less on product promotion-type campaigns, which had low signup rate and CTR.
- **Benefit Updates & Affordable Plans**: Even though these campaigns have high CTR, they exhibit low signup counts (below 100) and high cost per signup, indicating a need for conversion funnel optimization.
-   **COVID Campaigns**: Investigate the cause of abnormally high cost per signup for COVID-based campaigns, which had 2 signups that costed over $1K, compared to an average signup cost of $2.2. Consider removing these campaigns altogether.
-   **Family Coverage Plan:**  Investigate the lack of clicks despite high impressions, as there are likely issues with the campaign or missing data.


# Dashboard

The dashboard can be found in Tableau Public  [here](https://public.tableau.com/views/VitalHealthCampaignDashboard/Dashboard2). This dashboard enables users to filter by plan, campaign type, and state, and focuses on trends and values in marketing metrics, signup metrics, and claim metrics.

![VitalHealth Dashboard](https://github.com/user-attachments/assets/a0f59345-267e-4e6e-9f44-eb562645f63f)


# Presentation Sample
The presentation created for the marketing team walks through the insights and recommendations above and can be found [here](https://public.tableau.com/app/profile/sylvia.tsai/viz/VitalHealthCampaignDashboard/Dashboard2). Some extracts are presented below for easy viewing.


<img src="https://github.com/user-attachments/assets/c071f9b2-e7c7-4b31-b4cb-caed10f34b84" width="100%">
<img src="https://github.com/user-attachments/assets/bc4ce6ed-01c5-4f69-8125-648c96f4fdc9" width="100%">
<img src="https://github.com/user-attachments/assets/9dc82b6b-1124-4fc8-8003-2182ef7254c6" width="100%">
