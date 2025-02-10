# Web-Traffic-Analysis-Dashboard

This Power BI dashboard provides an in-depth analysis of web traffic data for 2024, including key metrics such as total page views, bounce rates, session durations, and conversion rates. The goal of this project is to offer actionable insights that can help improve web performance and user engagement.

## Project Background
With an ever-growing online presence, it's crucial for businesses to understand how their websites are performing. The Web Traffic and Performance Dashboard helps monitor and optimize website traffic by analyzing key performance indicators (KPIs). By tracking total page views, bounce rates, session durations, and other important metrics, businesses can identify areas for improvement and take actionable steps to enhance user experience.

This dashboard was built using Power BI, pulling data from various sources to provide insights into web traffic behavior and performance. By examining user interactions through different browsers, traffic sources, and page views over time, the goal is to identify patterns that could inform business strategies.

### Important Terminology
1. Page Views: The total number of pages viewed on the website, including repeated views of a single page.
2. Bounce Rate: The percentage of visitors who navigate away from the site after viewing only one page.
3. Session Duration: The average amount of time a user spends on the website during a single session.
4. Conversion Rate: The percentage of sessions that lead to a desired action, such as a purchase, sign-up, or form submission.
5. Traffic Sources: The origin of the website visitors, categorized as paid search, organic search, direct traffic, social media, or referrals.

## Key Metrics

** Total Page Views:
The dashboard tracks total page views for 2024, amounting to 83,74,046, which is just shy of the 76,77,166 target.

** Average Bounce Rate:
With an average bounce rate of 34.35%, there’s room for improvement in retaining users beyond the landing page.

** Average Session Duration:
On average, users spend 1 minute 12 seconds on the website, indicating a need for strategies to engage visitors longer.

** Converted Sessions:
The conversion rate stands at 68.15%, with a notable portion of sessions (31.85%) not leading to a conversion.

### Breakdown by Browser
The Opera browser holds the largest share of page views at 2,77,470.
Other browsers like Edge show slightly lesser session duration at 55 seconds.
### Traffic Source Analysis
Paid Search drives the majority of traffic, followed by Organic Search, Social Media, Referral, and Direct Traffic.
### Monthly Trends and Weekday Analysis
A line graph compares daily page views against set targets.
A bar chart visualizes traffic throughout the week, with relatively stable performance on weekdays.

![Web Traffic Dashboard](https://github.com/atharvagolwalkar/Web-Traffic-Analysis-Dashboard/blob/main/Screenshot%202025-02-10%20195643.png)
![Page Views Analysis](https://github.com/atharvagolwalkar/Web-Traffic-Analysis-Dashboard/blob/main/Screenshot%202025-02-10%20195704.png)

## Recommendations
Based on the insights gathered from the web traffic analysis, the following recommendations can help improve website performance:

Optimize Landing Pages: With a bounce rate of 66.93%, optimizing landing pages (speed, content relevance, layout) could lower the bounce rate and retain more visitors.

Enhance User Engagement: The average session duration of 56 seconds suggests a need to create more engaging content, such as interactive features, videos, or blogs, to keep users on the site longer.

Improve Conversion Funnel: With 31.77% of sessions not converting, enhancing the conversion funnel by simplifying the user journey or offering incentives could increase conversions.

Diversify Traffic Sources: Currently, the website relies heavily on Paid Search and Organic Search. Expanding outreach through Social Media campaigns or optimizing referral partnerships could bring in more diverse traffic.

A/B Testing: Running A/B tests on different landing pages, especially focusing on browsers with lower session durations or conversion rates (like Safari and Edge), can help identify potential improvements.

## Technical Project Information

### Tools and Technologies Used:
1. Power BI: Used for data visualization and building the dashboard.
2. Data Transformation: Data was cleaned and transformed using Power Query to prepare it for visualization in Power BI.
3. Data Model:
The data model consists of several tables, including Traffic Source, Browser Data, and Time-Series information. These tables were joined to create relationships that allowed for dynamic filtering and drill-downs in the Power BI report.
4. Visualizations:
   
    **KPI Cards: Display total page views, bounce rates, and session durations.

    **Bar Charts: Compare total page views by traffic source and performance by browser.

    **Line Graphs: Show trends over time, with a focus on daily page views against targets.

    **Tables: Provide a detailed breakdown of key metrics like session duration and bounce rate by browser.

### Future Improvements:
1. Integrating predictive analytics to forecast web traffic based on historical data.
2. Expanding the dashboard to track user behavior on specific web pages (heatmaps, exit points).
3. Adding real-time data analysis to monitor performance metrics as they happen.
