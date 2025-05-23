# OnlyBears
News & Stock Data Analytics Pipeline on Google Cloud Platform
This repository showcases a comprehensive data engineering and machine learning pipeline built on Google Cloud Platform (GCP). The project is designed to collect, process, and analyze real-time news articles and stock market data, ultimately leveraging machine learning for sentiment analysis and generating actionable insights.

Project Overview
This project implements a distributed, microservice-oriented architecture to handle the full lifecycle of data, from ingestion to transformation, storage, and machine learning inference. Each component is containerized using Docker and deployed on GCP using Cloud Build for continuous integration and continuous deployment (CI/CD). 





The pipeline's core functionalities include:

Data Ingestion: Automatically fetching news articles and stock market data from external sources. 
Data Transformation & Cleaning: Processing raw news and stock data to make it analysis-ready. 
Dynamic Data Storage: Utilizing Google BigQuery to dynamically create and manage tables for both raw and processed data. 

Machine Learning Integration: Training and deploying a machine learning model (likely for sentiment analysis) using the processed news data to generate valuable insights. 
