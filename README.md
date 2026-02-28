Supply Chain Logistics & Shipping Analysis

A comprehensive logistics and shipping performance analysis built using Tableau. This project
evaluates shipment efficiency, disruption patterns, transport performance, and operational risk
indicators across global routes.

Project Overview
Dataset: Global shipping transactions (5,000+ records)
Tool: Tableau Public
Analysis Focus: Shipment performance, disruption rate, route efficiency, transport mode
performance, and weather impact analysis

This dashboard is designed to monitor logistics reliability, detect operational bottlenecks, and
support data-driven decision-making in supply chain operations.

Key Questions & Insights 
What is the overall shipment performance?
KPIs Analyzed:
• Total Shipments
• Disruption Rate (%)
• Average Transit Time
• On-Time Delivery Rate
• Total Transaction Count

Insight:
While overall shipment volume remains stable, the presence of disruptions indicates
operational risk exposure. Monitoring disruption % is critical for service-level reliability.

Which routes have the highest transaction volume?
Analysis: Shipment Count by Origin–Destination Route
Insight:
Certain port-to-port routes dominate transaction volume. High-traffic routes represent both
strategic strengths and operational risk concentration areas.
Recommendation:
Introduce route-specific performance monitoring for high-volume corridors.

 What is the disruption rate across transport modes?
Analysis: Disruption Rate by Transport Mode (Sea, Air, Rail, Road)
Insight:
Sea and road transport show higher disruption variability compared to air. This reflects exposure
to weather, congestion, and geopolitical risk.
Recommendation:
Diversify mode selection for high-priority shipments and introduce risk scoring per mode.

How does weather condition impact disruptions?
Analysis: Shipment Performance by Weather Condition
Insight:
Extreme weather conditions significantly increase disruption probability and transit delays.
Recommendation:
Integrate weather forecasting into logistics planning and adjust buffer times accordingly.

Which product categories face higher disruption exposure?
Analysis: Disruption Count by Product Category
Insight:
Certain categories (likely perishable or high-value goods) experience higher disruption
sensitivity.
Recommendation:
Prioritize resilient transport modes for sensitive goods and negotiate SLAs with stronger penalty
clauses.

How does transit time vary across routes?
Analysis: Average Transit Time by Route
Insight:
Some routes show consistently longer lead times, indicating congestion or inefficient routing.
Recommendation:
Evaluate alternative routing strategies or renegotiate carrier agreements.

Monthly Shipment & Disruption Trend
 
Insight:
Seasonal spikes in disruption rates indicate potential climate or demand-driven pressure
periods.
Recommendation:
Develop peak-season contingency planning and capacity buffers.
Overall Insights Summary
• Disruption risk is unevenly distributed across transport modes and routes.
• High-volume routes carry concentrated operational risk.
• Weather conditions significantly impact reliability.
• Some transport modes demonstrate better stability but may involve higher cost.
• Transit time variability suggests optimization opportunity.

Strategic Recommendations
1. Implement Route Risk Scoring
Assign risk levels to high-volume origin–destination pairs.
2. Improve Mode Diversification Strategy
Avoid overreliance on disruption-prone modes.
3. Introduce Predictive Disruption Monitoring
Use historical disruption patterns to anticipate future risk.
4. Strengthen Carrier Performance KPIs
Monitor on-time delivery %, average delay, and disruption frequency per carrier.
5. Establish Seasonal Contingency Plans
Increase buffer stock and safety lead time during high-risk periods.
6. Develop Executive-Level Logistics KPI Dashboard
Include disruption %, transit variance, and SLA compliance for leadership visibility.
 Technical Implementation

Calculated Fields:
• Disruption Rate = (SUM(Disruption Flag) / COUNT(Shipment ID)) × 100
• Average Transit Time = AVG(Delivery Date – Shipment Date)
• On-Time Delivery % = On-Time Shipments / Total Shipments
• Route = [Origin Port] + " → " + [Destination Port]

Data Aggregation:
• Route-level transaction grouping
• Transport mode performance comparison
• Monthly trend analysis using date hierarchy

Visualization Techniques:
• KPI Summary Cards
• Route transaction bar charts
• Disruption % comparison charts
• Monthly trend line charts
• Interactive filters (Month, Quarter, Route, Product Category, Transport Mode, Weather
Condition)

 Files Included
• SUPPLY CHAIN LOGISTICS & SHIPPING ANALYSIS.twbx – Tableau packaged workbook
• global_supply_chain_risk_2026.csv.csv – Simulated logistics dataset
• readme.md – Project documentation

 Business Impact
This dashboard enables logistics managers and supply chain leaders to:
• Detect disruption hotspots
• Optimize route planning
• Reduce delivery delays
• Improve SLA compliance
• Strengthen operational resilience
It supports proactive decision-making instead of reactive firefighting in supply chain operations.

 Connect with Me
Website: https://rotimiayomide99.github.io/rotimiayomide.github.io/
Linkedin: www.linkedin.com/in/ayomide-rotimi-1ba9261bb
Email: Rotimiayomide99@yahoo.com
GitHub: https://github.com/Rotimiayomide99
