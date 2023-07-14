# Gaming Analytics Dashboard

## Introduction
This repository contains all of the code and documentation for my Gaming Analytics Dashboard project. The goal of this project is to analyze and visualize data from the gaming industry to gain insights into player behavior, game performance, and business metrics. The project involves collecting and processing data from various sources, storing it in a database, and creating an analytics dashboard to visualize the data. 

This project has been divided into two main parts: Data Engineering and Data Science.

## Technologies Used
- Data Generation, Ingestion, Transformation: Python (via Google Colab)
- Data Storage: ElephantSQL (PostgreSQL)
- Data Science: Python (via Google Colab)
- Dashboard: Bubble

## Part 1: Data Engineering

### Step 1: Data Generation
Data was collected from various sources relevant to gaming analytics. These sources include Steam Store APIs. Scripts used for data generation are available in the `data_preparation` folder.

### Step 2: Data Storage
ElephantSQL, an instance of PostgreSQL, was used for data storage. The database schema and setup scripts can be found in the `data_preparation` folder.

### Step 3: Data Ingestion
Data was ingested using Python scripts, which can be found in the `data_preparation` folder. These scripts use libraries like `requests` for API interactions, `pandas` for data manipulation, and `psycopg2` to interact with ElephantSQL.

### Step 4: Data Transformation
The ingested data was transformed for analysis using Python scripts available in the `data_transformation` folder. This involved cleaning the data, integrating data from different sources, and transforming data into a suitable format for analysis.

## Part 2: Data Science
In progress... 

## Getting Started
Instructions on how to replicate this project are available in the `instructions.md` file. 

## Contributing
While this project is primarily for my own learning and portfolio, suggestions and improvements are welcome. Please open an issue to discuss or make a pull request.
