# Calculate Performance Efficiency Rating (PER) with Machine Learning in League of Legends (README)

## Introduction
This project aims to evaluate player performance in League of Legends by calculating a Performance Efficiency Rating (PER) using data from the Riot Games API. The notebook explores data loading, preprocessing, model training, and evaluation to achieve this objective.

## Table of Contents
- [Data loading and preprocessing](#data_loading)
- [Raw data exploration](#raw_data)
- [Model training and evaluation](#model_training)
- [Results](#results)
- [Conclusion](#conclusion)

## Data Loading and Preprocessing <a id='data_loading'></a>
I begin by fetching raw match data from the Riot Games API, including information about top summoners, match timelines, and various in-game statistics. Key steps in this section include:

- Defining API constants and functions to fetch top summoner IDs, PUUIDs, match IDs, and match timelines.
- Preprocessing the fetched data to prepare it for analysis and modeling.

## Raw Data Exploration <a id='raw_data'></a>
In this section, we explore the raw data to understand its structure and key characteristics. This includes visualizing distributions of various in-game statistics and identifying important features for the PER calculation.

## Model Training <a id='model_training'></a>
I train machine learning models to calculate the PER for each player based on the preprocessed data. Key steps include:

- Feature selection and engineering.
- Splitting the data into training and testing sets.
- Training and fine-tuning machine learning models.

## Model Evaluation
I evaluate the performance of the trained models using various metrics and visualizations to ensure accuracy and reliability.

## Results <a id='results'></a>
The results section presents various analyses and visualizations, including:

- Distribution of the PER stat.
- Top 10 champions based on average, highest, and lowest PER.
- Time series analysis of PER for top champions.
- Top 10 players based on average PER and their performance over time.

## Conclusion <a id='conclusion'></a>
In this notebook, I successfully calculated and analyzed the PER for League of Legends players using machine learning models. This comprehensive analysis provides insights into player performance and helps identify top-performing players and champions.

### Acknowledgments
I would like to thank Riot Games for providing the API and data used in this project.
