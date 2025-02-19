# Book Reviews Sentiment Analysis: A Data Engineering Approach
# Overview
This project builds a scalable data pipeline that extracts and processes book reviews from the Goodreads API. Using Apache Airflow, the system automates data extraction and stores raw data in AWS S3. Apache Spark on Amazon EMR then cleans, transforms, and analyzes the data, with processed results stored back in S3 for further use.

# Requirements
## Functional
### Data Extraction and Storage
- Extract book reviews and ratings from the Goodreads API.
- Store raw data in AWS S3.

### Data Processing and Transformation
- Use Apache Spark on Amazon EMR to clean and preprocess data.
- Perform sentiment analysis on reviews
- Store processed data and model predictions in S3 for further use.

### Workflow Automation
- Orchestrate the pipeline using Apache Airflow.
- Implement logging, retries, and error handling for failures.

## Non-Functional
### Scalability and Performance
- Support increasing API requests and data volume.
- Optimize Spark performance.

### Reliabilty and Security
- Ensure fault tolerance.
- Secure API Keys and control AWS access with IAM roles.

### Extensibility and Maintainability
- Allow adding new data sources in the future.
- Maintain modular training and inference pipelines for reusability