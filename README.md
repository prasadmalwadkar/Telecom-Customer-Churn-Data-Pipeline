# Automated Telecom Customer Churn Analysis with Actionable Insights

This project is aimed at helping telecommunications companies combat customer churn by implementing a robust and automated analysis pipeline on the AWS cloud platform. By leveraging advanced technologies and data analytics, the project enables proactive identification of churn risks and facilitates data-driven decision-making for enhanced customer retention strategies.
![Untitled design](https://github.com/ritikdhame/Automated-Telecom-Customer-Churn-Analysis/assets/7029092/5be08781-d006-4901-9bea-05a49cae6d4c)

## Features

### High-Throughput Data Pipeline

- **Data Extraction:** Customer data is extracted seamlessly from two primary sources:
    - **S3 Buckets:** Historical customer data is stored in scalable and cost-effective S3 buckets.
    - **Redshift Database:** Real-time customer activity data resides in the Redshift database for immediate analysis.
![Visual - Editor - AWS Glue Studio](https://github.com/ritikdhame/Automated-Telecom-Customer-Churn-Analysis/assets/7029092/a637801b-c9a2-4945-afea-40ef33f244c6)

- **Automating Data Discovery:** AWS Glue serves as the data orchestration engine, automatically defining data structures and discovering new datasets within designated S3 buckets through AWS Glue Crawlers.
- **Orchestration with Airflow:** Airflow, a robust workflow management tool, schedules extraction tasks from S3 and Redshift at regular intervals to ensure consistent churn analysis cycles.
![my_dag - Grid - Airflow](https://github.com/ritikdhame/Automated-Telecom-Customer-Churn-Analysis/assets/7029092/b5f0d88b-69ff-4903-8486-66f02da624b1)

- **Data Transformation (Optional):** The pipeline supports data transformation tasks to clean, engineer features, or preprocess data before churn analysis.

- **Data Loading:** Processed data is strategically loaded back into Redshift for churn analysis and visualization.

### Actionable Insights with Tableau

- **Interactive Dashboard:** A Tableau dashboard offers interactive visualization of key customer churn metrics.
- **Segmentation:** Users can segment data by various attributes to gain insights into the top reasons driving customer churn.
- **Geographical Visualization:** The dashboard potentially allows for geographical distribution visualization to analyze churn trends across different regions.


To view the Tableau dashboard, click on the following link:
[Automated Telecom Customer Churn Analysis Dashboard](https://public.tableau.com/views/AutomatedTelecomCustomerChurnAnalysis/Dashboard?:language=en-US&:sid=&:display_count=n&:origin=viz_share_link)

![file_2024-03-31_22 57 32](https://github.com/ritikdhame/Automated-Telecom-Customer-Churn-Analysis/assets/7029092/9067c107-72d7-4a32-a520-579f9dbb55fb)


Also tried to build a similar dashboard by connecting the redshift warehouse with Quicksight :
<img width="613" alt="Screenshot 2024-03-31 at 9 16 34 PM" src="https://github.com/ritikdhame/Automated-Telecom-Customer-Churn-Analysis/assets/7029092/c11f95e9-d76f-48e6-b250-f63ede83ef5c">


## Benefits

- **Early Churn Risk Identification:** Weekly churn analysis facilitates the proactive identification of customers at risk of churning.
- **Data-Driven Decision Making:** Actionable insights from the Tableau dashboard empower informed decision-making to address root causes of churn and implement effective retention strategies.
- **Improved Customer Retention:** Understanding key drivers of churn enables the development of targeted strategies to retain valuable customers, ultimately increasing customer lifetime value.

## Conclusion

This project equips telecommunications companies with a powerful tool to analyze customer churn, derive valuable insights, and implement effective retention strategies. By leveraging advanced data analytics and visualization techniques on AWS, companies can enhance customer retention rates and ultimately drive business growth.
