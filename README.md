# Walmart Sales Prediction

## Overview

This project aims to predict department-wide sales for 45 Walmart stores located in different regions. The provided dataset contains historical sales data for each store, including various departments. Additionally, the dataset includes information about promotional markdown events associated with major holidays, such as the Super Bowl, Labor Day, Thanksgiving, and Christmas.

The goal is to develop a predictive model that can accurately forecast department-wide sales for each store, taking into account the impact of promotional markdown events, especially during holiday weeks.

## Dataset

The dataset is provided in 4 different CSV files, containing information about historical sales, store details, features, and promotional markdown events. The files are:

1. `sales_data.csv`: Contains historical sales data for each store and department.
2. `store_data.csv`: Provides details about each Walmart store, including its size and location.
3. `features_data.csv`: Includes additional features that may affect sales, such as temperature, fuel price, and unemployment rate.
4. `markdown_data.csv`: Specifies the details of promotional markdown events, including their timing and impact.

## Problem Statement

The main challenge is to build a robust predictive model that accurately forecasts department-wide sales for each store. Special emphasis should be given to handling and incorporating the impact of promotional markdown events, especially during the weeks surrounding the four major holidays (Super Bowl, Labor Day, Thanksgiving, and Christmas). Evaluation of the model will give higher weight to holiday weeks, being five times more significant than non-holiday weeks.

## Getting Started

Follow these steps to get started with the project:

1. Clone the repository:

    ```bash
    git clone  https://github.com/MdZaid27/Walmart-Sales-Prediction.git
    ```

2. Navigate to the project directory:

    ```bash
    cd walmart-sales-prediction
    ```

3. Install the required dependencies:

    ```bash
    pip install -r requirements.txt
    ```


