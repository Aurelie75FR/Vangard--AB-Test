# Vanguard A/B Testing Analysis

## Project Overview

Welcome to the Vanguard A/B Testing Analysis repository! This project contains the analysis of an A/B test conducted to evaluate the effectiveness of a new digital interface for Vanguard's clients. The goal was to determine if an intuitive User Interface (UI) and timely in-context prompts would increase the completion rate of an online process.

As a data analyst, you are tasked with analyzing the results of this experiment, which was conducted between March 15, 2017, and June 20, 2017. This repository contains the necessary notebooks and scripts to clean, analyze, and perform hypothesis testing on the collected data.

## Project Context

### The Digital Challenge
Vanguard, a US-based investment management company, wanted to improve the digital experience for its clients. The company hypothesized that a new UI, combined with in-context prompts (hints, instructions, etc.), would encourage more clients to complete a given online process.

The primary question was: **Would these changes lead to a higher process completion rate among clients?**

### The A/B Testing Experiment

- **Control Group**: Clients experienced Vanguard's traditional online process.
- **Test Group**: Clients interacted with the newly designed digital interface.

Both groups navigated through the same process, consisting of:
1. An initial page
2. Three subsequent steps
3. A final confirmation page indicating process completion.

The primary goal was to compare the completion rates between the two groups and assess the impact of the new UI and prompts.

## Project Structure

The repository is organized as follows:

- **`load_and_clean.ipynb`**: A Jupyter notebook for loading and cleaning the dataset. This includes data preprocessing steps such as handling missing values and preparing the dataset for analysis.
  
- **`eda_plot.ipynb`**: This notebook contains the exploratory data analysis (EDA) and visualization steps. It provides insights into the distribution of the data, key trends, and comparisons between the control and test groups.

- **`hypothesis_testing.ipynb`**: A notebook focused on hypothesis testing. It includes statistical tests to determine if there is a significant difference in the process completion rates between the two groups.

## Running the Code

To run the analysis, follow these steps:

1. **Load and Clean the Data**: Start by running the `load_and_clean.ipynb` notebook to load and preprocess the data.
2. **Exploratory Data Analysis**: Next, run the `eda_plot.ipynb` notebook to explore and visualize the data.
3. **Hypothesis Testing**: Finally, run the `hypothesis_testing.ipynb` notebook to perform statistical analysis and test your hypothesis.

## Tableau Files

We have a directory for Tableau files. You can see our sheets, dashboards and stories in our files. 

## Requirements

Before running the notebooks, make sure you have the following libraries installed:

```bash
pip install pandas numpy matplotlib seaborn scipy
