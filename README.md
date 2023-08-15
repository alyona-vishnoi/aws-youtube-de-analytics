# AWS Data Engineering - Youtube Analytics
This project aims to securely manage, streamline, and perform analysis on the structured and semi-structured YouTube videos data based on the video categories and the trending metrics.

## Project Objectives
- **Data Ingestion:** Develop a robust mechanism to ingest data from diverse sources.
- **ETL System:** Transform raw data into a refined format for analysis.
- **Data Lake:** Create a centralized repository for data from multiple sources.
- **Scalability:** Ensure the system scales seamlessly as data volume increases.
- **Cloud Infrastructure:** Utilize AWS (Amazon Web Services) for processing large datasets efficiently.
- **Reporting:** Construct a dynamic dashboard to provide insights on key questions.

## Services used
- Amazon S3: I leveraged Amazon S3 as a cornerstone of the project. It acted as a scalable and secure object storage solution, enabling me to store, manage, and access vast amounts of data efficiently.

- AWS IAM: With AWS Identity and Access Management (IAM), I ensured secure and fine-grained control over access to AWS resources. This helped me manage permissions and protect sensitive data.
  
- QuickSight: Amazon QuickSight was pivotal in transforming raw data into actionable insights. Its serverless, machine learning-powered business intelligence capabilities allowed me to create interactive and embeddable visualizations.
  
- AWS Glue: Utilizing AWS Glue, I streamlined the data integration process. Its serverless architecture facilitated the discovery, preparation, and combination of data from various sources, making it ready for analysis and application development.
  
- AWS Lambda: : AWS Lambda proved to be invaluable for running code without the need to manage servers. I utilized it to execute functions as needed within the project's workflow, optimizing efficiency and resource utilization.
  
- AWS Athena: Athena emerged as a key player in the interactive querying process. Its seamless integration with S3 allowed me to perform queries on data stored directly in S3, eliminating the need for data loading and enhancing query agility.

<img width="984" alt="Screenshot 2023-08-15 at 5 52 15 PM" src="https://github.com/alyona-vishnoi/aws-youtube-de-analytics/assets/88257366/c8275520-8d00-4d73-ae3e-d79a8e408680">

## Dataset Source

The project utilizes the YouTube Trending Videos Dataset available on Kaggle. This dataset contains daily statistics in CSV files for popular YouTube videos across various regions. With up to 200 trending videos published daily, the dataset includes video titles, channel details, publication times, tags, views, likes, dislikes, descriptions, comment counts, and region-specific category IDs.

https://www.kaggle.com/datasets/datasnaek/youtube-new 
