![Logo](https://images.unsplash.com/photo-1587825140708-dfaf72ae4b04?fm=jpg&q=60&w=3000&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxzZWFyY2h8M3x8c2VtaW5hcnN8ZW58MHx8MHx8fDA%3D)

# Project Background
In this project, I set out to explore advanced Power BI visualisation techniques, including dynamic KPI cards with conditional formatting and custom waffle charts, to derive insights from a Kaggle-based Superstore dataset (2012–2014) [Link](https://www.weforum.org/publications/the-future-of-jobs-report-2025/). The analysis is centered around ad engagement, customer demographics, and purchase behaviours, with the goal of informing more targeted marketing strategies and improving customer experience. The project also emphasises Power BI’s ability to turn complex datasets into interactive and insightful dashboards.

Insights and recommendations are provided in the following areas:

- **Web Purchase Breakdown:** Insights on website visits and purchase behaviour by visit frequency

- **Customer Demographic:** Profiling customers by education, marital status, income, and age

- **Total Spend Per Month:** Product purchase trends by web visit frequency

- **Average Monthly Spend Per Customer:** Spend trends by last transaction date and demographic group

PowerBI Dashboard [Link](https://www.google.com)

# Data Structure
The dataset contains 28 columns. Four columns — Customer Join Date, Complaints, Year of Birth, and Customer ID—were excluded due to low analytical value. This dataset did not require cleaning prior to loading in PowerBI unlike some of the other datasets I have used for visualisation. A sample of the first few columns and rows is shown below and can be downloaded here [Link](https://wwww.github/amirulshafiq98/Superstore)

![Data Table](https://github.com/user-attachments/assets/4dbd2cd8-7a40-4cd5-b850-93e92b989b68)

# Executive Summary
### Overview:
Despite launching a new ad campaign and website in the past month, only 15% of members viewed the ad. Online purchases, however, accounted for 33% of total sales, supported by 7,685 website visits. The highest conversion rates came from users with 6–8 visits per month, with peak purchases at 6 visits. Members who visited the site 1–3 times contributed to nearly half of total monthly spending ($24,653 out of $52,143). 

Top-selling products were wine ($28,314) and meat ($15,563). The customer base primarily consisted of Bachelor’s degree holders (50%), aged 31–50 (55%), and married (65%), earning $40,000–$80,000 annually. While the average order value (AOV) was $23.32, it was significantly skewed downward by members earning < $40,000 (AOV = $2.92)

Shopping behaviour showed:
- Ages 19–50 preferred shopping at the end of the month
- Ages 51+ shopped more frequently with no clear pattern
- Discount coupon usage was highest among 31–50 (4:1 ratio of discounts used to customers)

The following sections will dive deeper into sales performance, top-selling products, and customer behavior to identify actionable opportunities for continued growth. Below is an overview of the dashboard in PowerBI that can be downloaded [here](https://www.google.com)

![Updated BI](https://github.com/user-attachments/assets/eedc6885-2a9b-4a13-b77d-fa39267258f8)

### Web Purchase Breakdown:
- Conversion peaked at 6–8 web visits, making this the optimal retargeting window
- Purchases dropped 3.5x after 9+ visits
- Despite being newly launched, the website drove 33% of all sales
- Customers with 6, 7, and 8 website visits showed the highest conversion to purchases, indicating an optimal engagement window for retargeting efforts
- Website adoption, while in its infancy, contributed to 33% of all sales in its launch month, suggesting strong potential for digital growth with the majority of sales still coming via catalog (21%) and in-store purchases (46%)
- Only 2% of members did not make a purchase via the website

![Sales Trends](https://via.placeholder.com/468x300?text=App+Screenshot+Here)

### Customer Demographic:
- Most customers were Bachelor’s graduates (50%), aged 31–50 (55%), married (65%), earning $40k–$80k
- Only 14.89% of all members saw the ad
- 1/4 of members without kids saw the ad—a 78% increase over the general rate
- Members without kids had a higher average income ($64k) than those with kids ($43k)
 
![Sales Trends](https://via.placeholder.com/468x300?text=App+Screenshot+Here)

### Total Spend Per Month:
- 1–3 site visits accounted for ~50% of total spend
- Wine and meat were the biggest sellers at the superstore generating $28,314 and $15,563 respectively
- Products sold in order: Wine > Meat > Fish > Sweets > Fruits
- Discount usage:
    - Ages 19–30: infrequent
    - Ages 31–50: 4:1 discount-to-customer ratio
    - Ages 51+: 2:1 discount-to-customer ratio

![Sales Trends](https://via.placeholder.com/468x300?text=App+Screenshot+Here)

### Average Monthly Spend Per Customer:
- Ages 19–50 shopped mainly at month-end
- Ages 51+ shopped more frequently, but less predictably
- Those earning $40k–$80k spent the most within a range of $119.29–$679.38/month
- Those earning < $40k never spent more than $85/month
- Members aged between 19-30 (Max: $284.33, Avg: $51.77) spent less on average compared to those who were 31+ (Max: $571.79, Avg: $233.73)

 ![Sales Trends](https://via.placeholder.com/468x300?text=App+Screenshot+Here)

# Recommendations
- **Optimise Website Experience:** Incentivise users who visit 6–8 times/month with loyalty rewards and promotions to increase conversion
- **Targeted Ad Campaigns:** Focus on high-income, child-free members for premium offerings—this group had the highest ad engagement and spending
- **Age-Based Incentives:** Prioritise age group 31–50 with discounts and retention programs—they form the largest customer segment
- **Product Bundling:** Package high-selling items like wine and meat, especially for users who visit 1–3 times/month, to drive upsells
- **Affordable Offerings:** Introduce entry-level products or discounts for customers earning < $40k to boost conversion among high-footfall, low-spend groups

# Limitations
- **Short Time Frame:** Data only covers a single month, limiting trend and seasonality analysis
- **Missing Campaign Metadata:** No info on ad channels or timing, making it hard to attribute ad effectiveness
- **No Timestamped Transactions:** Lack of transaction dates prevents analysis of sales patterns by day or week
- **Sampling Bias:** Ad viewership insights may be skewed by self-selection or non-random survey participation
