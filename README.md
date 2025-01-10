## ETL Data Pipeline on Google Cloud using Cloud Data Fusion and Airflow

![Screenshot (657)](https://github.com/user-attachments/assets/9a753243-1d06-4fb7-b223-bf603fb7ccab)


- **Data Extraction**: Created a Python script to extract employee data into a CSV file (dummy data using Faker library) and then stored the data on the Google Cloud Storage bucket.
- **Data Transformation**: Using Cloud Data Fusion created a data pipeline that transforms the data like masking passwords and ultimately loads the data into Big Query
- **Data Loading into Big Query**: Securely loaded the extracted and transformed data into Google Big Query.
- **Data Visualization**: Designed a dashboard on Looker Studio to visualize the data
- **Automation**: Automated the entire ETL Data Pipeline using an Airflow DAG in the Cloud Composer environment.

  ![Screenshot (656)](https://github.com/user-attachments/assets/40888204-4428-4f02-871c-12dd6ca9baa0)
