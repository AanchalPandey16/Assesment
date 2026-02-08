# Insight Summary – Marketplace Performance (30 Days)

## Overview

I analyzed 18,000 sales records and 14,000 ad records from January 2026 to understand platform performance and identify optimization opportunities. The analysis revealed significant inefficiencies in ad spending but also highlighted promising categories with strong potential.

**Summary Statistics:**
- Total Revenue: $54.5M
- Total Ad Spend: $160.0M
- Platform ROAS: 0.34 (spending $1 to earn $0.34)
- Date Range: January 1-31, 2026
- Missing Data: 35.7% of products lack category mapping

---

## Key Patterns Observed

### 1. Overall Platform Performance
The platform achieved a ROAS of 0.34, which means we're losing money on ads - for every dollar spent, only 34 cents comes back in revenue. However, the strong correlation (0.86) between ad spend and revenue shows that ads are working to drive sales, just not efficiently enough.

### 2. Category Performance

**Efficient Categories (ROAS > 1.0):**
- Baby Care: ROAS 1.34, Revenue $2.8M
- Nutrition: ROAS 1.28, Revenue $4.5M
- Devices: ROAS 1.08, Revenue $1.5M

These categories are profitable - they generate more revenue than ad spend.

**Inefficient Categories (ROAS < 0.5):**
- Makeup: ROAS 0.17, Revenue $9.2M
- Skincare: ROAS 0.19, Revenue $8.5M
- Haircare: ROAS 0.41, Revenue $4.1M

These generate high revenue but waste a lot of ad budget. Makeup and Skincare are the biggest concerns - they bring in the most sales but have terrible ad efficiency.

### 3. Product-Level Insights
Looking at individual products, I noticed that some top-selling products have very low ROAS (below 0.3), while some mid-tier products have excellent ROAS (above 2.0). This suggests that high-selling products might not need as much ad support because they already have demand.

### 4. Daily Volatility and Outliers
Revenue varies significantly day-to-day. I identified January 10th as a major outlier with $3.4M in revenue (88% above average). This could be from a promotion, campaign, or external event. Understanding what caused this spike could help replicate success.

### 5. Data Quality Issue
About 36% of the data is missing category information, representing 33% of total revenue. This is a significant gap that limits our ability to make fully informed decisions.

---

## Over-Performing vs Under-Performing Areas

| Performance Level | Categories/Products | Key Observation |
|-------------------|-------------------|-----------------|
| **Strong Performers** | Baby Care, Nutrition, Devices | Generating profit on ad spend (ROAS > 1.0) |
| **Poor Performers** | Makeup, Skincare | High revenue but massive ad waste (ROAS < 0.2) |
| **Opportunity** | Mid-revenue products with high ROAS | Efficient targeting, could be scaled up |
| **Risk** | Unmapped products (36% of data) | Cannot optimize what we can't categorize |

---

## Recommendations

### 1. Reallocate Ad Budget (High Priority)
**What to do:**
- Reduce ad spend on Makeup and Skincare by 30-40%
- Increase budget for Baby Care, Nutrition, and Devices by 25-30%

**Why:**
Makeup and Skincare are losing money on every ad dollar. Since they're already high-revenue categories, they likely have organic demand and don't need heavy ad support. The saved budget should go to categories that are actually profitable.

**Expected Impact:**
Could improve overall ROAS from 0.34 to 0.60-0.70, moving closer to breakeven.

### 2. Fix Missing Category Data (Critical)
**What to do:**
Work with the product team to map the 6,423 products (36% of data) that are missing category information.

**Why:**
We're making decisions based on only 64% of our revenue. The unmapped products could contain high performers we don't know about.

**Next Steps:**
Start with the highest revenue unmapped products first to get quick insights.

### 3. Optimize Product-Level Ad Spend (Medium Priority)
**What to do:**
- Stop or reduce ads for top-selling products with ROAS below 0.3
- Increase ads for mid-revenue products with ROAS above 2.0

**Why:**
Top sellers already have demand and don't need aggressive ads. Mid-tier efficient products could grow significantly with more budget.

### 4. Investigate Success Days (Medium Priority)
**What to do:**
Analyze what happened on January 10th (and other outlier days) to understand what drove the 88% revenue spike.

**Why:**
If we can identify the cause (specific campaign, promotion, external event), we can try to replicate it.

### 5. Set Up Daily Monitoring (Low Priority)
**What to do:**
Create a simple dashboard to track ROAS by category daily instead of waiting for monthly reports.

**Why:**
Catch problems early. If a category suddenly drops below 0.5 ROAS, we can investigate and adjust quickly instead of losing money for weeks.

---

## Conclusion

The platform has strong revenue ($54.5M in 30 days) but is spending inefficiently on ads. The main issue is over-investing in Makeup and Skincare, which are already popular but have poor ad returns. By shifting budget to efficient categories like Baby Care and Nutrition, and fixing the data quality gap, we can significantly improve profitability. The immediate priority should be reducing waste on low-ROAS categories and completing the product mapping to get full visibility.