# Row Health Performance Analysis
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
- [Appendix](#appendix)
    
 

# Executive Summary
The campaigns are driving exceptional awareness with a 9.39% CTR and extremely low $0.07 CPC, but the funnel leaks heavily at signup (only 0.18% signup rate). Top-performing campaigns like Health For All and Benefit Updates should receive more budget, while underperforming hashtag campaigns need a creative refresh. To improve ROI, fix landing page friction, simplify signup flows, and use claims data to balance preventive vs. high-risk member acquisition.

# ERD

<img width="734" height="482" alt="image" src="https://github.com/user-attachments/assets/b22ef913-0b48-4aba-b6c9-95326aa72fd1" />



# North Star Metrics
• **Signup Rate**: The percentage of people who see a campaign and subsequently sign up for a  Row Health plan.

• **Cost per Signup**: The average amount spent in order to acquire a new signup from each campaign.

• **Click through Rate (CTR)**: The percentage of people who viewed a campaign and click on the associated link.

• **Cost per Click (CPC)**: The average amount spent for each click on a campaign link.

• **Impressions**: The total number of times a campaign is displayed on someone's screen, regardless of whether they click or sign up.

# Deep-dive Insights
## Marketing Performance

### Insights
- CTR is exceptionally strong (9.39%) This is very strong for health‑related campaigns. Industry averages often sit between 2–4%.
  
- CPC is extremely low ($0.07) indicating efficient spend and strong ad relevance.

- Campaigns like **Health For All**, **Benefit Updates**, and **Summer Wellness Tips** appear to deliver:  
  - High impressions  
  - High CTR  
  - Low CPC  


- Hashtag campaigns (`#Coverage Matters`, `#Healthy Living`, `#Insure Your Health`) show:  
  - Lower CTR  
  - Higher CPC  
  - Lower impressions
    
### Recommendations

	• Increase budget allocation to the top 3 performing campaigns.
	• Refresh or pause underperforming hashtag campaigns — test new creatives or audiences.
	• Optimize landing pages since strong CTR but weak signup rate indicates post‑click friction.
	• Segment audiences by campaign theme (education vs. plan comparison vs. preventive care).
	• Introduce seasonal campaigns (e.g., flu season, open enrollment) to boost engagement.

## Signup Performance

### Insights

- Signup Rate is low (0.18%) despite high CTR. This is the biggest funnel leak.
  
- Cost per Signup ($3.68) is reasonable but it could be improved if signup rate increases.
  
- Signup trends (2019–2023):
	- Signup count is increasing, showing growing interest.
	- Signup mix is shifting, meaning some campaigns are becoming more effective over time.

    
### Recommendations
	• Fix the landing page experience Low signup rate suggests:
		○ Too many form fields
		○ Slow page load
		○ Poor mobile experience
		○ Weak value proposition
	• Implement retargeting for users who clicked but didn’t complete signup.
	• Simplify the signup flow
		○ Reduce friction
		○ Add progress bar
		○ Offer “email‑only quick start”
	• Test incentives Examples: free wellness guide, plan comparison tool, premium calculator.
	• Identify top signup‑driving campaigns and shift budget accordingly.


## Claim Performance

### Insights
- Some campaigns generate high claim counts but low average claim amounts — likely preventive or wellness‑focused.

- Others generate low claim counts but high average claim amounts — likely chronic or high‑risk segments.

- Claim trends (2019–2023):
	  - Total claim amounts are rising, which may reflect:
			- Higher enrollment
			- Higher utilization
			- More expensive care categories
      
- Claims mix shows shifts in which campaigns drive the most claims, indicating evolving member behavior.


### Recommendations 
	• Map campaign → member → claim behavior Identify which campaigns attract:
		○ High‑cost claimants
		○ Low‑cost preventive users
		○ Chronic care users
	• Promote preventive‑care campaigns to reduce long‑term claim costs.
	• Introduce care‑management nudges for high‑claim segments:
		○ Telehealth
		○ Medication adherence
		○ Preventive screenings
	• Monitor claim lag to ensure accurate attribution.

# Dashboard

<img width="1022" height="764" alt="image" src="https://github.com/user-attachments/assets/5a2451b0-3eaf-4cf1-bc17-da22b7f8eca8" />

# Presentation

# Appendix

