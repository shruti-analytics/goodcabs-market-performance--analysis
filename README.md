# Goodcabs-market-performance-analysis

# Project Background
Goodcabs is one of India’s fastest-growing cab service brands in tier-2 cities, operating across ten emerging urban markets. Unlike conventional ride-hailing companies, Goodcabs is built on a driver-first philosophy—empowering local drivers to earn sustainably in their hometowns while ensuring reliable, high-quality service for passengers.

As the company enters its third year, the Chief of Operations has set ambitious performance targets for 2024, aiming to expand trip volumes, strengthen rider satisfaction, and increase long-term customer loyalty. To support these goals, the leadership team requires a clear, data-driven understanding of how the business is performing across different cities, passenger segments, and trip types.This project provides an end-to-end analysis of Goodcabs’ operational and customer metrics—enabling the leadership to evaluate current performance, uncover growth opportunities, and make informed decisions for scaling sustainably.

 The analysis delivers deep insights across three major pillars:
 - Trip Performance: Evaluates total trip volume, target achievement, peak vs. off-peak demand patterns, and city-wise trends.
 - Passenger Insights:Examines the balance between new and repeat passengers, satisfaction ratings, retention patterns, and city-level loyalty behavior.
 - Revenue Analysis:Breaks down monthly revenue shifts, city-wise revenue contribution, fare patterns, and pricing effectiveness.

An interactive PowerBI dashboard can be downloaded [here.](https://github.com/shruti-analytics/goodcabs-market-performance--analysis/blob/main/Goodcabs%20.pbix)

The SQL queries used for the analysis can be found [here.](https://github.com/shruti-analytics/goodcabs-market-performance--analysis/blob/main/goodcabs.sql)

# Executive Summary

### Overview of Findings

<img width="1285" height="500" alt="Screenshot 2025-12-11 173807" src="https://github.com/user-attachments/assets/73fd245f-caab-434d-ab01-75bf0872ff71" />

The comapny recorded 426K trips and ₹108M revenue in the last six months, with strong early-year momentum—both trips and revenue peaked in February–March before dipping noticeably by June, signaling a clear need to address mid-year demand slowdown. Passenger dynamics reveal a steady decline in new passenger acquisition from 36K in January to just 22K in June.City-wise performance shows large revenue concentration in Jaipur, Kochi, and Chandigarh, while several cities contribute minimally, highlighting uneven market penetration and the opportunity for targeted city-level strategy refinement.

### Deeper Dig Through


### Trip Performance:


<img width="1052" height="550" alt="Screenshot 2025-12-11 174919" src="https://github.com/user-attachments/assets/97939b1e-d98c-4dd2-98f1-823482b3571e" />


- Trips rose from January to a peak in May, driven almost entirely by weekday commuters, but June shows a sharp decline in both weekday and weekend demand. This suggests that Goodcabs’ growth is heavily dependent on routine work-travel patterns, and seasonal or external factors (exams, heat, holidays, etc.) may be affecting monthly volumes.

- **Clear over-performance in Jaipur, Kochi, and Mysore.** These three cities surpass their trip targets, showing strong market fit, high adoption, and efficient operations. Jaipur is the top performer overall, while Kochi and Mysore deliver consistently above-target utilization despite smaller absolute volumes.

- Retention rising, new acquisition falling. New passengers drop steadily from 36K → 23K across the six-month period, while repeated passengers increase and take majority share (crossing 60%+ by April–June). This points to strong user satisfaction and loyalty, but weakening top-of-funnel growth that needs attention.

- Operational conversion gaps in some high-demand cities. A few cities (e.g., Kochi, Surat) show substantial raw demand but occasionally fall short of targets, indicating operational constraints (driver availability, matching, or pricing) that are preventing full conversion of demand into completed trips.


### Passenger Insights:


<img width="1277" height="547" alt="Screenshot 2025-12-11 185529" src="https://github.com/user-attachments/assets/10e62166-b331-4111-9a80-ca04c2dcdcb1" />


- **Loyalty is strengthening steadily, but total passenger volume is shrinking.** Repeat passengers rise from 8.3K → 12.2K (Jan–May), showing stronger loyalty and improved retention, while new passengers drop consistently from 36K → 22K, signaling weakening acquisition.

-**Loyalty is highly uneven across cities, revealing strong and weak customer experience clusters.** Surat (42.6%), Lucknow (37.1%), and Indore (32.7%) have the highest repeat-passenger rates, indicating strong local engagement. However, Mysore (11.2%) and Jaipur (17.4%) struggle to retain customers, despite being top trip contributors — pointing to service consistency or city-specific experience issues.

- **Customer satisfaction is stable, but driver ratings are slipping — a warning signal for future retention.** Passenger ratings remain consistently strong around 7.6–7.9, showing stable customer satisfaction. However, driver ratings fall from 7.89 → 7.75, with a noticeable drop in June, suggesting operational pressure, inconsistent service quality, or insufficient driver support — which could threaten long-term loyalty.


### Revenue Analysis:


<img width="1284" height="550" alt="Screenshot 2025-12-11 185700" src="https://github.com/user-attachments/assets/6380015c-7a14-458e-9539-6c1addab7b31" />


-Revenue shows a clear seasonal pattern, with strong demand in Jan–Mar but a sharp 14.4% decline from May to June, indicating reduced summer mobility or rising competitive pressure.

-Nearly half of total revenue comes from just two cities—Jaipur and Kochi—creating a high concentration risk, while Chandigarh emerges as an underrated high-value market with strong long-distance demand.

-Weekday trips dominate overall volume, but weekend revenue surpasses weekday earnings, indicating that weekend trips are longer, higher-fare, or more premium in nature.

-Repeat passengers generate slightly more revenue than new riders, reinforcing loyalty strength but also showing that growth in weaker cities will depend on improving new-user acquisition.


### Recommendations:

-Introduce weekend surge pricing, premium ride categories, or bundled offers (e.g., “Weekend Saver Pass”) since weekend trips generate higher revenue per ride.Promote events, leisure partnerships, and targeted ads on Fridays and Saturdays to leverage naturally higher ticket sizes.

-Since weekday trips are volume-heavy but lower revenue, optimize route clustering, driver allocation, and dynamic pricing to improve per-trip profitability.Introduce micro-incentives for drivers during office hours to reduce cancellations and increase throughput during peak commute windows.

- Diversify growth by launching localized promotions in mid-tier cities like Chandigarh, Lucknow, and Indore where demand is strong but revenue capture is lower.

- Expand loyalty tiers with rewards, cashback, and “frequent rider benefits” to maintain improving retention trends.Deploy targeted campaigns for cities with low repeat rates (e.g., Mysore, Jaipur) to develop stable recurring user bases.

- Partner with colleges, tech parks, malls, and local businesses to onboard new users where new-rider growth is dropping.Provide first-ride discounts, referral rewards, and hyperlocal digital campaigns to revive new user funnels.

- Monitor cities where driver ratings fall faster and deploy quality control interventions (ride audits, feedback loops).

- Implement distance-based premiums or minimum fare adjustments in cities like Coimbatore, Mysore, and Surat to uplift revenue.
