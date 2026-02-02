# Amazon-Sales-Big-Data-Analysis
Big Data Analysis using PySpark on Amazon Sales Dataset

*COMPANY*: CODTECH IT SOLUTIONS PVT.LTD

*NAME*: RUTIKA SAWARKAR

*INTERN ID*: CTIS4003

*DOMAIN*: DATA ANALYTICS

*DURATION*: 4 WEEKS

*MENTOR*: NEELA SANTOSH KUMAR

# DESCRIPTION:
# Amazon Sales Big Data Analysis Using PySpark
This project focuses on performing scalable big data analysis on an Amazon sales dataset using PySpark to demonstrate the ability to handle large, real-world datasets efficiently. The dataset contains detailed information about products, including product names, categories, pricing, discounts, customer ratings, and review metadata. Due to the size and complexity of the data, traditional data processing techniques are inefficient, making distributed processing with PySpark an ideal solution.

The project was implemented on Google Colab, leveraging PySpark’s distributed computation engine. The first step involved setting up a Spark environment and loading the dataset into a Spark DataFrame. Initial exploration was conducted to understand the schema, data types, and overall structure of the dataset. Since pricing columns such as discounted price and actual price were stored as currency-formatted strings, a crucial data cleaning step was performed to remove currency symbols and commas and convert these values into numeric formats suitable for analysis.

 Once the data was cleaned, multiple analytical operations were performed using Spark SQL and DataFrame APIs. Category-wise product distribution was analyzed to identify dominant product segments on the platform. Pricing and discount analysis was conducted to understand Amazon’s discounting strategies, and average discounted prices were calculated to evaluate overall pricing trends. Additionally, rating and review count analysis helped identify popular and high-engagement products.

 This project highlights the advantages of PySpark, including lazy evaluation, in-memory processing, and scalability for large datasets. It also demonstrates practical skills such as data cleaning at scale, aggregation, and extracting meaningful business insights from raw data. Overall, the project showcases proficiency in big data tools and reflects an industry-relevant approach to analyzing large-scale e-commerce data.
# OUTPUT
The analysis produced the following key outputs:

The dataset contains a large number of Amazon products across multiple categories, demonstrating the ability to handle real-world big data.

Category-wise aggregation showed that Computers & Accessories is one of the most dominant product categories.

The average discounted price was calculated successfully after cleaning price data, providing insight into Amazon’s overall pricing strategy.

Discount analysis revealed that many products offer high discount percentages, indicating competitive pricing and promotional tactics.

Rating and rating-count analysis helped identify highly rated and popular products, showing strong customer engagement.

All computations were completed efficiently using PySpark’s distributed engine, validating the scalability of the solution. The final output confirms that the project meets the objective of performing big data analysis using PySpark and deriving meaningful business insights from a large e-commerce dataset.

