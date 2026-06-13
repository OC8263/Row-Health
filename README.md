# Row Health Campaign Category Analysis
# Company Background

Row Health is a U.S.-based medical insurance company founded in 2016, now serving thousands of customers nationwide. In 2019, the company expanded its marketing efforts by launching a series of campaign categories covering key topics such as wellness tips, plan affordability, and preventative care. Customers can choose from four tiered plans (bronze, silver, gold, and platinum), each designed with varying premium levels and claim coverage rates to suit different needs.
With a newly established data team in place, Row Health is now focused on shaping a smarter marketing strategy for the year ahead. Central to this effort is a deeper understanding of how each campaign category drives customer signups and influences subsequent patient claims. The marketing budget is guided by two core objectives: growing the overall customer base through increased signups, and strengthening Row Health's brand presence across the United States.

<summary><strong>Table of Contents</strong></summary>

- [Executive Summary](#executive-summary)
- [ERD](#erd)
- [North Star Metrics](#north-star-metrics)
- [Deep-dive Insights](#deep-dive-insights)
- [Marketing Performance](#marketing-performance)
- [Signup Performance](#signup-performance)
- [Claim Performance](#claim-performance)
- [Presentation](#presentation)
- [Dashboard](#dashboard)

    
 

# Executive Summary
The campaigns are driving strong brand awareness, reflected in a **9.39% CTR** and an impressively low **$0.07 CPC**. However, the funnel breaks down significantly at the signup stage, with only a **0.18% signup rate**, indicating friction between ad engagement and conversion. Top-performing campaigns such as **Health For All and Benefit Updates** warrant increased budget allocation, while hashtag-based campaigns are underperforming and require a creative refresh. To improve overall ROI, efforts should focus on reducing landing page friction, streamlining the signup flow, and leveraging claims data to strike the right balance between preventive and high-risk member acquisition.

# ERD

<img width="734" height="482" alt="image" src="https://github.com/user-attachments/assets/b22ef913-0b48-4aba-b6c9-95326aa72fd1" />



# North Star Metrics
• **Signup Rate**: The percentage of people who viewed a campaign and subsequently sign up for a Row Health plan.

• **Cost per Signup**: The average amount spent to acquire a new signup from each campaign.

• **Click through Rate (CTR)**: The percentage of people who viewed a campaign and click on the associated link.

• **Cost per Click (CPC)**: The average amount spent for each click on a campaign link.

• **Impressions**: The total number of times a campaign was displayed to a user, regardless of whether they clicked or signed up.

# Deep-dive Insights
## Marketing Performance

### Insights
- CTR is exceptionally strong at **9.39%**, well above the industry average of **2–4%**, while CPC remains notably low at **$0.07**, reflecting highly efficient and well-targeted campaign spend.
  
- Top-performing campaigns — **Health For All (36.1% CTR), Benefit Updates (22.2%)**, and **Summer Wellness Tips (17.0%)**, consistently outperform across impressions, CTR, and CPC.

- Hashtag campaigns significantly underperform across all metrics, and **Golden Years Security** stands out with the highest CPC at **$0.48**, far above the campaign average.
    
### Recommendations

	• Increase budget allocation toward Health For All, Benefit Updates, and Summer Wellness Tips, and pause or refresh underperforming hashtag campaigns with new creatives and targeting.
	• Optimize landing pages as the gap between strong CTR and weak signup rate points to post‑click friction.
	• Introduce seasonal campaigns tied to key moments such as flu season and open enrollment to boost engagement.

## Signup Performance

### Insights

- The **0.18% signup rate** represents the most critical funnel gap, despite strong click engagement indicating significant friction between ad exposure and conversion.
  
- **#Healthy Living (3,727), Health For All (3,545)**, and **#Coverage Matters (3,536)** are the top three signup-driving campaigns, together accounting for the majority of 16,289 total signups.

- Cost per Signup varies widely across campaigns from as low as **$0.65** (#Coverage Matters) to as high as **$176.73** (Golden Years Security), highlighting major differences in conversion efficiency.
    
### Recommendations
	• Improve the landing page experience; the low signup rate likely stems from too many form fields, slow page load times, poor mobile optimization, or a weak value proposition.
	• Simplify the signup flow by reducing friction, adding a progress indicator, and offering a quick-start option such as email-only registration.
	• Implement retargeting for users who clicked but did not complete signup, and test conversion incentives such as a free wellness guide or plan comparison tool.

## Claim Performance

### Insights

- Total claims across all campaigns amount to **$13,335,785** from **49,866 claims**, with a grand average claim amount of **$267**.
  
- **Health For All, #Coverage Matters**, and **#Healthy Living** generate the highest claim volumes, while **Compare Health Coverage** has the highest average claim at **$410**, suggesting it attracts higher-cost members
  
- Total claim amounts have risen steadily from 2019 to 2023, with a shifting claims mix indicating evolving member behavior across campaign types.



### Recommendations 
	• Map the full campaign → member → claim journey to identify which campaigns attract high-cost versus low-cost preventive members.
	• Prioritize preventive care campaigns and introduce proactive health reminders for high-claim segments, including telehealth and preventive screening prompts.
	• Monitor claim lag to ensure accurate attribution between campaigns and resulting claims.

# Dashboard
- [Tableau](https://public.tableau.com/app/profile/christine3803/viz/RowHealthDashboard/Dashboard)
<img width="1022" height="764" alt="image" src="https://github.com/user-attachments/assets/5a2451b0-3eaf-4cf1-bc17-da22b7f8eca8" />

# Presentation



