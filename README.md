# Spark HR Data Pipeline.

A project for the IBM Data Engineer Professional Certificate

## Overview

This repository hosts a data pipeline built using Apache Spark to process and analyze employee data. The project simulates a real-world scenario where an HR department needs to transform raw, unstructured employee data from CSV files into a structured format for business intelligence and analytics.

## Key Features

This pipeline demonstrates a comprehensive data engineering workflow by executing the following tasks:

- **Data Ingestion and Preparation**:
    - Generates a DataFrame from raw CSV data.
    - Defines and applies a specific schema to the DataFrame to ensure data integrity.
    - Creates a temporary SQL view to allow for powerful SQL-based queries.

- **Data Transformation**:
    - Adds a new column for an employee bonus by calculating a 10% increase in salary.
    - Filters the dataset to focus on specific groups, such as employees in the IT Department or those with the letter 'o' in their name.
    - Sorts data by multiple criteria, including age and salary.

- **Data Analysis**:
    - Calculates key metrics, including the average salary and total salary by department.
    - Identifies the maximum salary by age group.
    - Calculates the average employee age and counts the number of employees in each department.
    - Performs a self-join to analyze relationships within the employee data.

## Technologies Used

- Apache Spark: Core engine for distributed data processing.
- PySpark: Python API for interacting with Spark.
- Python: Programming language for scripting the pipeline.
- Jupyter Notebooks: Environment for developing and documenting the data pipeline logic.

## Project Goal

The primary goal of this project is to demonstrate proficiency in using Apache Spark for building scalable and robust data pipelines, showcasing skills in data ingestion, transformation, and analysis.