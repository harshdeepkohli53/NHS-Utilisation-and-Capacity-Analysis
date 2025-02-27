# NHS assignment - Diagnostic Analysis using Python (Final Grade: pending)

Project Summary: The second six week LSE project involved working with real-world data to address a problem faced by the National Health Service (NHS). The project was aimed at addressing the issues of adequate capacity and utilisation within the system by considering appointment data to help reduce missed appointments. The analysis required me to utilise Python to explore the available data, create visualisations to identify trends, and extract meaningful insights to inform decision-making.

The report considered the two primary business questions as proposed by the NHS:

**1. Has there been adequate staff and capacity in the networks?**

**2. What was the actual utilisation of resources?**


**Analytical Approach Highlights:**

**Data validation**: As stated in the metadata, the data had already been cleaned, but also stated that the data was not originally designed for analysis due to lack of national standard for data entry causing extensive widespread data quality issues.  In spite of this, I demonstrated proficiency in consolidating data sets. When possible, ensuring accuracy and reliability analysis outcomes. Using a user defined function I was able to efficiently identify null values, duplicates and data types. Only 3.6% of the dataset contained duplicates which I felt was too low and without any context about how the data was collected and if they were genuine duplicates, I decided not to delete any data.

**Data wrangling**: Data was manipulated in Python using libraries such as Pandas and Numpy to reshape and filter the data to my intended requirement. Using functions such as groupby, map, loc, pivot allowed me to acheive this. Data was sense checked by creating data frames to view outputs before any visualisations were created, ensuring outputs were accurate.

**Effective visualisations**: Designed descriptive, easy to understand graphs using libraries such as Matplotlib and Seaborn for customistable graphs, including boxplots to understand distributions, lineplots for time series analysis and barplots for analysis on categorical variables.

**External research**: I conducted thorough research, integrating findings from a wide range of sources including references from several reliable sources. This ensured a well-rounded analysis, grounded in evidence and diverse perspectives.

**Strategic Recommendations**: Delivered actionable insights directly focussed on the questions posed by the NHS. I demonstrated the ability to translate complex data into actionable insights justified by strong research, focusing on strategic recommendations based on data analysis. Highlighted the need for efficient resource allocation, including increasing telephone appointment volumes, keeping time between booking and appointment short and monitoring staff specific missed appointment rates.


**Presentation** - https://youtu.be/0K1g4YoGr4A?si=fKqbgLiBeu6X4gkK


**Key Insights and Recommendations:**

•	Incentivize more telephone appointments. In general, we can see that attendance for telephone appointments is greater. A limitation is that we don’t know what groups of patients prefer telephone appointments, but we could consider offering telephone appointments for groups more likely to miss face-to-face appointments (e.g. younger patients or those with mobility issues). Measure success by comparing attendance rates prior to expanding telephone appointment volumes and after expanding.
•	Keep time between booking and appointment short as these appointments are more likely to be attended. 
•	Increase staff capacity earlier in the week as demand is highest on Mondays & Tuesdays.
•	Monitor staff specific DNA rates. Other practice staff have higher DNA rates and average wait times than GPs, but they conduct proportionally more face-to-face appointments, so consider expanding telephone appointments for them help reduce missed appointments.
•	Finally twitter data proved to be less useful, but potential insights can be unlocked through cleaned, ethical analysis using relevant hashtags.


**Professional Development and Impact:**

This project highlighted my proficiency in leveraging advanced analytics, research, and data visualisation techniques to drive significant potential improvements for the NHS. The initiative not only showcased my technical acumen but also highlighted my ability to translate data insights into actionable strategies that enhance service delivery and operational efficiency. 

