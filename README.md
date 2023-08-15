# Amazon Reviews Exploratory Data Analysis

This repository contains code and analysis for performing exploratory data analysis (EDA) on Amazon reviews data. The dataset includes various details about Amazon product reviews, such as user information, product details, review text, and sentiment analysis.

## Getting Started

To begin, you'll need to have Python and Jupyter Notebook installed on your system. You can install the required packages by running the following command:


Additionally, ensure that you have the `database.sqlite` file available in the specified path: `Downloads/Amazon_EDA/database.sqlite`.

## Contents

- **Importing Packages and Establishing Connections:** This section involves importing necessary Python packages, connecting to the SQLite database, and loading the data into a pandas DataFrame. It also includes checking the dimensions of the DataFrame.

- **Data Preparation:** In this section, the dataset is cleaned and prepared for analysis. The steps include handling invalid data, removing duplicates, converting timestamp columns, and calculating various statistics on the data.

- **Exploratory Data Analysis:** This part of the analysis involves exploring different aspects of the data. It includes:

  - Analyzing user behaviors and statistics such as the number of summaries, texts, average scores, and products purchased.
  - Visualizing the top users who have purchased the most products.
  - Analyzing the distribution of product purchases and scores.
  - Distinguishing between frequent and not-frequent viewers based on their behavior and analyzing score distributions.
  - Comparing text length between frequent and not-frequent viewers.
  
- **Buyer Sentiment Analysis:** In this section, sentiment analysis is performed on review summaries using the TextBlob library. The polarity of review summaries is calculated, and sentiment trends are analyzed. The most common positive and negative keywords are also identified.

## Usage

You can run the provided Jupyter Notebook to replicate the analysis. Make sure to adjust file paths and configurations as necessary to match your setup. The notebook is organized into different sections, each focusing on a specific aspect of data analysis. Comments and explanations are provided throughout the notebook to guide you through the analysis process.

## Contribution

Feel free to contribute to this project by adding more analyses, visualizations, or improvements to the code. If you encounter any issues or have suggestions for enhancements, please submit an issue or pull request.

