# British Airways Review Dashboard (Interactive Tableau Dashboard)
Analyzed British Airways customer reviews to identify key drivers of satisfaction while highlighting aircraft quality, cabin class, and service factors as major influences on customer experience.

## Questions (KPIs)
- What is the overall average customer rating for British Airways?
- How do ratings vary across different aircraft types?
- Which countries give the highest and lowest customer ratings?
- How does cabin class impact customer satisfaction?
- Which service categories (seat comfort, food, staff service, etc.) drive overall rating?
- What is the trend of customer satisfaction over time?

## Process
- Data Cleaning: Removed null values, standardized rating scales (1–10), and formatted review dates for time-series analysis.
- Data Transformation: Broke down review metrics into categories (seat comfort, food, staff service, entertainment).
- Feature Engineering: Created calculated fields such as recommendation rate (%) and overall rating averages.
- Tableau Prep: Aggregated ratings by country, aircraft, and time using grouping and calculated measures.
- Visualization: Built an interactive Tableau dashboard with filters for aircraft type, country, and traveler type.

## Project Insight
- Overall Customer Rating: British Airways has an average rating of approximately 4.2 / 10, indicating generally low customer satisfaction.
- Recommendation Rate: Only about 33% of customers recommend the airline.
- Country Based Rating: Higher ratings from: UK, USA → ~4.5–5.0; Lower ratings from: India, some EU countries → ~3.5–4.0
- Cabin Class Impact: Business Class: ~5.5–6.5; Economy Class: ~3.5–4.5
- Service Category Drivers: Highest rated: Staff service (~5.0); Lowest rated: Food & seat comfort (~3.5–4.0)
- Trend Over Time: Ratings show a slight downward trend over recent years, indicating declining customer satisfaction.

# Final Conclusion
British Airways faces a significant customer satisfaction issue, with an average rating of just 4.2/10 and a low 33% recommendation rate. The biggest drivers of dissatisfaction are seat comfort and food quality, while staff service remains relatively stronger. Performance varies by aircraft and cabin class, with premium and newer aircraft delivering better experiences.

## To improve, efforts should focus on: 
- Upgrading older aircraft interiors
- Improving economy-class experience
- Enhancing food and comfort offerings
