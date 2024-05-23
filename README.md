# Pymaceuticals, Inc. - Tumor Treatment Analysis

## Overview

This case study presents the analysis of a clinical trial conducted by Pymaceuticals, Inc., focusing on potential treatments for squamous cell carcinoma (SCC), a common form of skin cancer. As a senior data analyst, the objective is to visualize and summarize the performance of various drug regimens, particularly the company's drug of interest, Capomulin, using a dataset from an animal study involving 249 mice.

## Table of Contents
- [Background](#background)
- [Dataset](#dataset)
- [Project Tasks](#project-tasks)
  - [1. Prepare the Data](#1-prepare-the-data)
  - [2. Generate Summary Statistics](#2-generate-summary-statistics)
  - [3. Create Bar Charts and Pie Charts](#3-create-bar-charts-and-pie-charts)
  - [4. Calculate Quartiles, Find Outliers, and Create a Box Plot](#4-calculate-quartiles-find-outliers-and-create-a-box-plot)
  - [5. Create a Line Plot and a Scatter Plot](#5-create-a-line-plot-and-a-scatter-plot)
  - [6. Calculate Correlation and Regression](#6-calculate-correlation-and-regression)
- [Results Summary](#results-summary)
- [Conclusion](#conclusion)

## Background

Pymaceuticals, Inc. is a pharmaceutical company specializing in anti-cancer medications. The company's recent animal study aimed to identify effective treatments for SCC by comparing the tumor reduction performance of various drug regimens. The primary goal was to evaluate the efficacy of Capomulin in comparison to other treatments over a 45-day period.

## Dataset

The dataset comprises detailed observations of tumor development in 249 mice treated with different drug regimens. Key elements of the dataset include:
- Mouse Metadata: Basic information about each mouse.
- Study Results: Tumor measurements recorded at various time points.

## Project Tasks

### 1. Prepare the Data

**Objectives:**
- Merge mouse metadata and study results into a single DataFrame.
- Identify and remove any duplicate time points for each mouse.
- Verify the integrity of the data by ensuring all mice have unique time points.

**Steps:**
- Load and merge the data.
- Identify duplicates and remove them.
- Confirm the final count of unique mice.

### 2. Generate Summary Statistics

**Objectives:**
- Compute key statistical metrics for each drug regimen.

**Metrics:**
- Mean Tumor Volume
- Median Tumor Volume
- Tumor Volume Variance
- Tumor Volume Standard Deviation
- Standard Error of the Mean (SEM)

### 3. Create Bar Charts and Pie Charts

**Objectives:**
- Visualize the distribution of data points across drug regimens.
- Illustrate the gender distribution of the mice in the study.

**Charts:**
- Bar Charts: Total number of data points for each drug regimen.
- Pie Charts: Distribution of male versus female mice.

**Methods:**
- Use both Pandas DataFrame.plot() and Matplotlib's pyplot methods for visualization.

### 4. Calculate Quartiles, Find Outliers, and Create a Box Plot

**Objectives:**
- Analyze the distribution of final tumor volumes for the most promising treatments.
- Identify potential outliers.

**Steps:**
- Determine the final tumor volume for each mouse.
- Calculate quartiles and interquartile ranges (IQR).
- Identify and highlight outliers.

**Visualizations:**
- Box plots for each treatment regimen, highlighting outliers.

### 5. Create a Line Plot and a Scatter Plot

**Objectives:**
- Track tumor volume changes over time for a specific mouse treated with Capomulin.
- Explore the relationship between mouse weight and tumor volume.

**Steps:**
- Generate a line plot for a selected mouse.
- Create a scatter plot for mouse weight versus average tumor volume for the Capomulin regimen.

### 6. Calculate Correlation and Regression

**Objectives:**
- Determine the correlation between mouse weight and tumor volume.
- Fit a linear regression model to the data and visualize the trend.

**Steps:**
- Calculate the correlation coefficient.
- Perform linear regression and plot the regression line on the scatter plot.

## Results Summary

**Key Findings:**
- Capomulin demonstrated a significant reduction in tumor volume compared to other regimens.
- Tumor volume showed a positive correlation with mouse weight, suggesting a potential link between the two variables.

**Visualizations:**
- Summary statistics tables.
- Bar charts and pie charts illustrating data distributions.
- Box plots identifying outliers in tumor volume data.
- Line plot for tumor volume over time.
- Scatter plot with regression line showing the relationship between weight and tumor volume.

## Conclusion

The analysis provides a comprehensive overview of the clinical trial's findings, demonstrating the effectiveness of Capomulin in reducing tumor size. The visualizations and statistical summaries offer valuable insights for the executive team, supporting data-driven decision-making in the development of anti-cancer treatments.

