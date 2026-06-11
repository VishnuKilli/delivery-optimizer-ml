# Delivery Time Optimizer

## Overview
An end-to-end machine learning pipeline that predicts food delivery times by processing logistics data. This project covers the full AI lifecycle, including data cleaning, feature engineering, and live model inference.

## Engineering Workflow
* **Data Preprocessing**: Handled missing values and standardized timestamp logs to ensure data quality.
* **Feature Engineering**: Used the Haversine formula to calculate the actual geographic distance (km) between restaurant and delivery locations.
* **Model Training**: Implemented a Linear Regression pipeline to model the relationship between delivery duration and factors such as distance, person age, and vehicle condition.

## Performance and Testing
* **Metric**: Mean Squared Error (MSE): 16.07
* **Inference**: The model was validated on unseen scenarios. For a 10km delivery, the model predicts a duration of 10.04 minutes, confirming the pipeline is functional and accurate.

## Project Structure
* **data**: Contains the processed training and test datasets.
* **notebooks**: Contains the primary notebook with the full pipeline and inference logic.

## How to Run
1. Clone the repository: `git clone https://github.com/VishnuKilli/delivery-optimizer-ml.git`
2. Install dependencies: `pip install -r requirements.txt`
3. Open and run the notebook in the /notebooks/ directory to explore the pipeline.
