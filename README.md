# Police Use of Force Data Analysis: Work Methodology

## Overview

This project analyzes the dataset related to police use of force incidents from 2016 to 2022. Using R, the goal was to explore trends, demographic breakdowns, types of force used, and compliance with policy.

## Key Tools and Libraries
R: Core programming language.
dplyr: Data manipulation.
ggplot2: Data visualization.
tidyr: Data cleaning and tidying.

## Step-by-Step Methodology

### 1. Data Import and Initial Inspection
The first step was to load the dataset into R using read.csv(). To understand the data structure, basic inspection was performed with summary() and head().

### 2. Data Cleaning
Missing or inconsistent data were addressed using na.omit() to remove rows with missing values, and date conversions were handled using as.Date().

### 3. Separate Analyses Conducted
Each analysis was performed individually and visualized:
Incident Frequency Over Time
A time series analysis to explore how use of force incidents changed over time.

### 4. Demographic Breakdown
Data grouped by race and gender to show demographic distribution.

### 5. Type of Force
A bar chart displaying the frequency of each type of force used.

### 6. Policy Compliance
An analysis of whether the force used was deemed within policy.

Each analysis provided insights into the frequency of incidents, the demographics of subjects involved, and the types of force most commonly used—this separation of analyses allowed for a detailed understanding of each aspect of the dataset. Using R's powerful data manipulation and visualization libraries, I could break down the dataset into clear insights, focusing on different aspects of police use of force incidents.

