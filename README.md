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

•	I identified telephone appointments having a higher attendance % compared to face-to-face appointments and suggested that the NHS should increase telephone appointment volumes.

![lineplot_att_mode_monthly](https://github.com/user-attachments/assets/fd2132c0-4ecf-4a55-8189-c6b811bb3156)


•	I identified that there is a statistically significant positive correlation between higher wait times and missed appointment rate (correlation coefficient = 0.89 & P-value = 0.0075). I suggested keeping time between booking and appointment short as these appointments are more likely to be attended. 

![correlation_wait_dna](https://github.com/user-attachments/assets/88077a42-d67f-47d4-aeac-6a999e6f32d1)

![boxplot_wait_mode](https://github.com/user-attachments/assets/34933972-af08-48f6-8bd1-b20b8753ac96)


•	I identified that Tuesday is the busiest day of the week, followed by Monday. I also identified that Monday and Tuesdays were the most common days when utilisation exceeded capacity, and therfore recommended to increase staff capacity earlier in the week to keep up with demand.

![barplot_appt_dow](https://github.com/user-attachments/assets/2ea8a6bf-206e-4b0b-b994-e4cf8375b19e)

![lineplot_appt_dow](https://github.com/user-attachments/assets/b94361db-59c2-46dd-9507-e3c614f8dc66)

![barplot_util_above_capacity_dow](https://github.com/user-attachments/assets/de12b5b5-8185-418c-9251-cf4a23d2fe3d)


•	I identified Other practice staff having higher missed apppointment rates and average wait times than GPs, but they conduct proportionally more face-to-face appointments, so suggested expanding telephone appointments for Other practice staff to help them reduce missed appointments. By monitoring staff specific missed appointment rates, the NHS could find inefficiecies in their operations and improve total attendance.

![stacked_barplot_appt_hcp_mode](https://github.com/user-attachments/assets/f0f76a91-5351-4363-a3a5-e5bc88bfb1c2)

![barplot_hcp_dna](https://github.com/user-attachments/assets/ca665d7b-6184-4714-a980-5a7fdaa375df)

![barplot_avg_wait_hcp](https://github.com/user-attachments/assets/143af13c-f20c-4eac-abe4-a4e370b2e91e)


•	I noted that the 4% of missed appointments costs the NHS approximately £927 million from January 2020 to June 2022, underscoring the financial impact of data quality and patient attendance. In 2019 a report on the cost of missing appointments calculated the following:
“Each appointment costs an average of £30, putting the total cost to the NHS at more than £216 million pounds on top of the disruption for staff and fellow patients that would pay for:
The annual salary of 2,325 full time GPs
224, 640 cataract operations
58,320 hip replacement operations
216,000 drug treatment courses for Alzheimer’s
The annual salary of 8, 424 full time community nurses”. (NHS, 2019)
If we apply that £30 missed appointment metric to our data, then 30,911,233 not attended appointments over the 18 months period that the dataset covers costs the NHS £ 927,336,990


**Professional Development and Impact:**

This project highlighted my proficiency in leveraging advanced analytics, research, and data visualisation techniques to drive significant potential improvements for the NHS. The initiative not only showcased my technical acumen but also highlighted my ability to translate data insights into actionable strategies that enhance service delivery and operational efficiency. 

