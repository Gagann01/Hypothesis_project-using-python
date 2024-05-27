# Hypothesis Testing Project

## Overview

This project is a comprehensive analysis of hypothesis testing using Python, executed within a Jupyter Notebook environment. The primary objective is to demonstrate various statistical methods and hypothesis testing techniques using a dataset of website performance metrics. The project includes data exploration, visualization, and hypothesis testing.

## Table of Contents

- [Introduction](#introduction)
- [Installation](#installation)
- [Dataset](#dataset)
- [Methodology](#methodology)
  - [Data Exploration](#data-exploration)
  - [Data Visualization](#data-visualization)
  - [Hypothesis Testing](#hypothesis-testing)
- [Insights](#insights)
- [Conclusion](#conclusion)

## Introduction

Hypothesis Testing is a statistical method used to make inferences or decisions about a population based on sample data. It starts with a null hypothesis (H0), which represents a default stance or no effect, and an alternative hypothesis (H1 or Ha), which represents what we aim to prove or expect to find. The process involves using sample data to determine whether to reject the null hypothesis in favor of the alternative hypothesis, based on the likelihood of observing the sample data under the null hypothesis. This project demonstrates the application of Hypothesis Testing using Python, showcasing the process with a dataset that compares the performance of two website themes.

## Installation

To run this project, you need to have the following software and libraries installed:

- Python 3.x
- Jupyter Notebook
- NumPy
- Pandas
- Matplotlib
- Seaborn
- SciPy

You can install the required libraries using pip:

```bash
pip install numpy pandas matplotlib seaborn scipy

## Dataset

The dataset used in this project contains performance metrics for two website themes: Light Theme and Dark Theme. The key metrics include Click Through Rate, Conversion Rate, Bounce Rate, Scroll Depth, Age, Location, Session Duration, Purchases, and Added to Cart status.

## Methodology

### Data Exploration

Initial exploration of the dataset includes understanding its structure, summary statistics, and any potential data quality issues.

### Data Visualization

Visualization techniques are employed to uncover patterns, trends, and relationships within the data. Key visualizations include:

- Histograms
- Box plots
- Scatter plots
- Heatmaps

### Hypothesis Testing

Several hypothesis tests are conducted to draw conclusions about the population. These tests include:

- Two-sample t-tests for comparing means of different metrics between the two themes.

## Insights

### Dataset Summary

- **Number of Records:** 1,000
- **Number of Columns:** 10
- **Missing Values:** None

### Numerical Columns Summary

- **Click Through Rate:** Mean ~ 0.256, Std Dev ~ 0.139
- **Conversion Rate:** Mean ~ 0.253, Std Dev ~ 0.139
- **Bounce Rate:** Mean ~ 0.506, Std Dev ~ 0.172
- **Scroll Depth:** Mean ~ 50.32, Std Dev ~ 16.90
- **Age:** Mean ~ 41.53, Std Dev ~ 14.11
- **Session Duration:** Mean ~ 925 seconds, Std Dev ~ 508 seconds

### Theme Performance Comparison

- **Click Through Rate (CTR):** Dark Theme slightly higher (0.2645 vs. 0.2471)
- **Conversion Rate:** Light Theme slightly higher (0.2555 vs. 0.2513)
- **Bounce Rate:** Dark Theme slightly higher (0.5121 vs. 0.4990)
- **Scroll Depth:** Light Theme slightly higher (50.74 vs. 49.93)
- **Age:** Similar across themes (Light: 41.73, Dark: 41.33)
- **Session Duration:** Light Theme slightly longer (930.83s vs. 919.48s)

### Hypothesis Testing Results

- **Click Through Rate:** Statistically significant difference, p-value = 0.048 (Dark Theme likely better)
- **Conversion Rate:** No significant difference, p-value = 0.635
- **Bounce Rate:** No significant difference, p-value = 0.230
- **Scroll Depth:** No significant difference, p-value = 0.450

## Conclusion

The analysis demonstrates the application of hypothesis testing to compare the performance of two website themes. While the Dark Theme shows a statistically significant higher Click Through Rate, other metrics like Conversion Rate, Bounce Rate, and Scroll Depth do not show significant differences.
