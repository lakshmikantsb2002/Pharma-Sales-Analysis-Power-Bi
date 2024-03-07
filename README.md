# Pharma-Sales-Report
Pharma Sales Data Analysis Report using Power BI
I have done this Pharma sales data analysis project using Power BI while i was doing Data Analytics Internship at DharwadHubballiTutor Company.

Pharmaceutical Sales Analysis
In this ‘Data Analysis’ project, we’ll analyze a global Pharmaceutical Manufacturing Company's raw sales data and draw meaningful insights.
 Tools used: Power BI Desktop


Features
PowerBI Desktop[For creating a report]

PowerQuery Editor [For data-transformation/data-modeling]

PowerBI Service [For making the report accessible on the web without PowerBI login]
Multipage fully Interactive Report [For drawing insights and analysis]

1.INTRODUCTION:
Datamatrix-ml Pharmaceuticals is one of the leading Pharmaceutical Manufacturing companies with a global presence.
Their Markets are divided into different regions across the world. One of those regions manages the German and Poland Markets.
Company does not sell directly to customers. Instead, they work with a couple of Distributors in all their regions.
They have an agreement with each distributor to share their Sales Data. This is to enable them to gain insights up to the retail level. This data is made available 
 to them in CSV format.

2.METHODOLOGY:

To conduct this analysis, a comprehensive dataset comprising daily, quarterly, and yearly sales data was collected from Kaggle and imported into Power BI. Power 
 Query was employed to clean and transform the data, ensuring its accuracy and consistency.


Data in Excel
i. Data Import and Preparation: The dataset, comprising daily, quarterly, and yearly sales data, was imported into Power BI.

Power Query was utilized to perform data cleaning and preparation tasks.
Columns were split as needed to extract relevant information, such as separating date and time.
Conditional columns were created to categorize data based on specific criteria, such as medication categories.

Data in PowerQuery
ii. Column Manipulation and Calculation:

Additional columns were added to facilitate analysis, such as calculating total sales or deriving specific insights.
Aggregation functions, such as sum or count, were used to calculate metrics like total sales per week or quarterly sales.
Conditional calculations were performed to evaluate performance based on medication categories or timeframes.
Calculations of New measures with DAX.
Table.TransformColumnTypes('Divided Column'(("Hour",type duration))
Conditional Column in PowerQuery

3. ANALYSIS & INSIGHTS

I. Daily & Hourly Sales Analysis:

Sales-specific trends:: By visualizing sales by weekdays, I observed a consistent pattern where Saturday consistently demonstrated the highest sales, while Thursdays had the lowest sales.

Bar Chart: By visualizing sales by time(hour), the hourly sales of the pattern remain consistent during the weekdays, with the highest sales at 7:00p.m and lowest at 6:00 a.m. However, during the weekend there is a change in sales pattern with highest sales at 12:00p.m and lowest sales at 10:00 p.m.

Product-specific insights: The Stacked column chart and line chart indicate that product N02BE consistently outperformed other categories in terms of daily sales and hourly sales. In contrast, the N05C product had the lowest sales across all weekdays and weekends.

4.CONCLUSION & RECOMMENDATION: The analysis of pharmaceutical product sales using Power BI has provided valuable insights into market dynamics and performance. My findings suggest that N02BE demonstrates strong sales performance across all timeframes, while N05C struggles to gain significant traction.
Based on these insights, I recommend the following actions for pharmaceutical companies:

Focus on leveraging the popularity of N02BE by investing in its promotion and further enhancing its market presence.
Explore opportunities to improve the sales performance of N05C by conducting market research, identifying customer needs, and tailoring marketing strategies accordingly.
Continuously monitor and analyze sales trends on a daily, quarterly, and yearly basis to stay informed and adapt strategies accordingly.
