# UCIA
Used Cars in India Analysis (1996–2019)
Objective of the Project:
This report examines the Indian used car market from 1996 to 2019, focusing on trends in price, fuel type, location, mileage, transmission, and ownership. The goal is to identify customer preferences and pricing patterns to support data-driven automotive resale strategies.
Problem Being Addressed:
With an evolving automotive landscape, stakeholders need to understand what factors influence used car pricing and buyer behavior. This analysis highlights key variables that determine resale value and market movement.
Key Datasets and Methodologies:
The report utilizes a Power BI dashboard summarizing used car listings and transactions. Aggregated visualizations depict trends by year, location, brand, mileage, and ownership type. Methods include pivot summaries, categorical filters, and comparative breakdowns.

3. Story of Data
Data Source:
Aggregated from used car sales platforms and listing records from 1996–2019 in India.
Data Structure:
•	Rows: Each record represents a car listing or sale.
•	Columns: Include variables like Car Name, Fuel Type, Transmission, Owner Type, Price, Mileage, Seats, and Location.
Important Features:
•	Price: Determines vehicle resale value.
•	Fuel Type: Shows engine preference trends.
•	Transmission: Differentiates between manual and automatic driving habits.
•	Location: Provides insight into regional pricing behavior.
Data Limitations or Biases:
•	No breakdown by vehicle condition or seller type.
•	Outliers in early years (1996–2005) show minimal data activity.
•	Pricing may be influenced by untracked promotional offers or vehicle history.

4. Data Splitting and Preprocessing
Data Cleaning:
No null or unstructured values are evident from visuals. KPIs and charts rely on clean numerical and categorical fields.
Handling Missing Values:
Irregular early-year entries were likely suppressed or aggregated.
Data Transformations:
Mileage and price were grouped into bins. Fuel and transmission types were categorized for count and sum aggregations.
Data Splitting:
•	Dependent Variables: Price, Total Count
•	Independent Variables: Year, Brand, Fuel Type, Transmission, Mileage, Location
Industry Context:
Relevant to used car dealers, automotive marketers, online vehicle platforms, and resale pricing algorithm developers.
Stakeholders:
•	Online used car marketplaces
•	Dealerships and valuation experts
•	Auto manufacturers (for market intelligence)
•	Car financing and insurance companies

5. Pre-Analysis
Key Trends Identified:
•	Price growth peaked between 2013 and 2017, hitting 8.68K total in 2016.
•	Petrol and Diesel dominate the used car fuel types (932 and 1055 units respectively).
•	Manual transmissions are still more common, but automatics generate more value.
Potential Correlations:
•	Price seems to increase with decreasing mileage (e.g., 13.0 kmpl and 17.9 kmpl bins).
•	Locations like Coimbatore and Bangalore show higher average pricing.
Initial Insights:
•	Cars with automatic transmissions fetch higher total value even with fewer units.
•	Majority of listings are from first-hand owners, possibly indicating trust and better resale outcomes.

6. In-Analysis
Unconfirmed Insights:
•	Though manual cars dominate in volume, automatics generate more total value (34K vs 23K), suggesting premium pricing.
•	Coimbatore, not Delhi or Bangalore, has the highest average resale price—may indicate a strong local resale market or luxury vehicle dominance.
Recommendations:
•	Target higher-value resale markets like Coimbatore and Bangalore.
•	Encourage automatic listings, especially in urban areas where demand and price are higher.
Analysis Techniques Used:
•	Stacked bar charts
•	Pie and donut visualizations
•	KPI indicators
•	Multi-filtered dashboards (by year, kilometers, car name)
7. Post-Analysis and Insights
Key Findings:
•	Total Listings: 2,017 cars
•	Average Price: ₹9.48L
•	Most popular fuel types: Diesel and Petrol
•	Most valuable brand: Mercedes-Benz (~507 units in value)
•	Most common transmission: Manual (1,370 cars), but Automatics yield higher total price
•	Top price by location: Coimbatore (₹15.08L average)
Comparison with Initial Findings:
Initial expectations about manual dominance were validated in volume, but contradicted in value. Urban preference for automatics became clear.

8. Data Visualizations & Charts
Visual Types Used:
•	Line Graph: Total price over years
•	Bar Charts: Fuel type, location pricing, mileage, owner type
•	Pie Chart: Transmission distribution
•	KPI Tiles: Averages and totals for pricing, mileage, seats, and car count
Explanation:
•	Time-series chart shows exponential market growth post-2010.
•	Pie chart quickly identifies transmission preference.
•	Mileage and price charts expose the direct impact of efficiency on value.

9. Recommendations and Observations
Actionable Insights:
•	Promote listings from first-time owners (dominant and most trusted).
•	Focus acquisition on diesel/petrol cars with automatic transmission for premium margins.
•	Target sellers in Coimbatore and Bangalore for higher yield listings.
Optimizations:
•	Enhance UI filters to support transmission, fuel, and city-based searches.
•	Educate sellers on pricing premiums for automatic vehicles.
Unexpected Outcomes:
•	Coimbatore's high resale price was unexpected compared to traditional urban hubs.
•	Electric cars are almost nonexistent (only 2), showing limited adoption pre-2020.

10. Conclusion
Key Learnings:
•	India’s used car market grew substantially between 2010–2017.
•	Urban areas, especially in South India, yield the highest resale values.
•	Automatics, though fewer, command better pricing.
Limitations:
•	Lack of vehicle condition metrics.
•	Absence of post-2019 data limits modern trend projection.
Future Research:
•	Include financing method, service records, and accident history.
•	Analyze dealer vs individual listings separately.
•	Extend dataset to post-2020 to capture EV impact and COVID-era effects.

11. References & Appendices
References:
•	Power BI File: Used Car in India Analysis.pbix
•	Dashboard Export: Used Cars.png
Appendices:
•	Mileage and Transmission visual cross-tabs
•	Brand-wise pricing breakdown
•	Location filter effects on price averages

