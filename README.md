# Digital-Marketing-Performance-Analysis
## Project Overview 

This dataset is a synthetically generated, benchmark-based digital marketing performance dataset designed for educational dashboards, analytics practice, and portfolio projects, with a specific focus on the MENA (Middle East & North Africa) region. It simulates realistic multi-platform advertising activity across the full marketing funnel
| | |
|---|---|
| **Dataset** | Digital Marketing Performance (Kaggle) |
| **Period** | 2023 – 2025 |
| **Region** | MENA (13 countries) |
| **Records** | 30,000+ |
| **Tool Used** | Power BI |

## Business Problem 
Advertising spend remained stable at ~$4.2M/year, yet ROAS declined from **1.18x (2024)** to **1.08x (2025)** — the lowest in three years. CTR and CVR also dropped simultaneously.

## Business Objective
- Identify the key drivers of marketing performance
- Evaluate the efficiency of current budget allocation
- Recommend optimization opportunities to improve marketing ROAS, and enhance overall conversion performance

## Data Model
<img width="957" height="641" alt="image" src="https://github.com/user-attachments/assets/30118c50-9454-4d8d-9355-906c16130305" />

## Dashboard Structure
| Page | Question |
|---|---|
| Home | Project overview & problem statement |
| Overview | How are we performing overall? |
| Platform | Which platforms are consuming budget inefficiently? |
| Campaign | Which creative drives the best results? |
| Geo | Which markets are driving the largest budget leakage? |
| Ad Timing | Are budgets deployed at the right time? |
| Summary | Conclusion & action plan |
## Analysis Framework
 
The report is structured around 4 analytical dimensions, each addressing a specific aspect of budget misallocation:
 
### 1. Platform
- 5 out of 6 platforms operate below breakeven (ROAS < 1.0x)
- Google Search is the only profitable platform (ROAS 3.78x, CVR 1.88%) yet its budget share *declined* in 2025
- LinkedIn consumes 20.1% of spend at ROAS 0.11x — the lowest performer, likely due to B2B-oriented audience being targeted with B2C creatives
- Funnel allocation is nearly identical across all platforms (40-30-30), failing to leverage each channel's core strength

**Key Insight: The platform with the strongest conversion performance is receiving a declining share of the budget, while some underperforming platforms continue to receive significant investment. At the same time, spending is being allocated to the wrong stages of the marketing funnel across platforms**
  
### 2. Campaign
- Reach and Video Views account for 42% of campaign spend yet deliver near-zero CVR (0.04%) and no direct revenue
- Leads campaigns — the highest-converting objective (CVR 4.48%) — receive only 13% of spend
- Product Launch delivers the strongest efficiency (ROAS 1.61x, CPA $30.98) but is the second-least-funded theme
- Feed placement receives the largest budget ($3.2M) but ROAS of only 0.30x vs PMax at 4.11x

**Key Insight: A large portion of the budget is concentrated on brand awareness activities, while campaigns that generate stronger conversions are not receiving proportional investment**
  
### 3. Geography
- Tier 1 receives 66.5% of spend but ROAS is only marginally higher than Tier 3 (4.7x more budget, near-equal returns)
- Tier 2 operates below breakeven (ROAS 0.99x) while receiving 19.4% of spend — contributing to $195K in direct annual losses (Egypt, Qatar, Bahrain)
- Oman (ROAS 1.36x, CPA $34) and Kuwait (ROAS 1.28x, CPA $37) are the most efficient markets yet receive less than 5% of spend each

**Key Insight: Budget allocation across markets is primarily driven by market hierarchy rather than actual performance, causing several high-potential markets to be overlooked**

### 4. Ad Timing
- Summer (ROAS 0.67x, below breakeven) receives 20.3% of spend despite Fall delivering 1.53x ROAS
- Weekends (Sat 0.95x, Sun 0.89x) receive nearly identical daily spend as weekdays despite below-breakeven performance
- Peak hours 19–21h generate 13.5% higher CTR but account for only 12.3% of spend — 87.7% of budget runs during lower-engagement hours

**Key Insight: The company does not fully understand customer behavior across its markets, leading to missed conversion opportunities during periods of increased demand and wasted budget during ‘dead’ hours**

## Conclusion
Declining ROAS is not a budget problem. It is a structural misallocation across funnel, platform, market, and timing. The company does not have a performance-driven budget allocation strategy

## Recommendations
- Cut the budget allocated to LinkedIn or review a more effective advertising strategy for the platform. At the same time, shift the reduced spend share from LinkedIn to Google Search
- Shift a portion of the budget from upper-funnel (Awareness) campaigns to lower-funnel (Conversion) activities to improve ROAS
- Expand investment in promising markets: Conduct a one-quarter test by increasing budget in high-potential Tier 3 markets, maintaining Tier 1 investment, and reducing exposure to Tier 2 markets
- Apply a dayparting strategy by increasing budget allocation during the 18:00–21:00 peak hours while reducing advertising spend on dead hours

## About
 
This is a personal practice project built to develop skills in data analysis, business storytelling, and Power BI. Feedback and suggestions are warmly welcome.
 
📧 Connect with me on LinkedIn: *https://www.linkedin.com/in/tuyet-nhi-tran/*

🔗 Live Dashboard: *https://app.powerbi.com/view?r=eyJrIjoiN2FlYjc2ZGItYjQwOC00NjM5LWE4MjMtM2E3NGNmZTJkZjMxIiwidCI6ImFmMWYzNzUzLTM5MjUtNGU2Zi05NDliLTk3YzAwNzMyMDgwMyIsImMiOjEwfQ%3D%3D*
