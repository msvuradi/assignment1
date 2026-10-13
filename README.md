# Assignment1
Berkeley Assignment 1: 
This project explores factors that influence whether drivers accept a coupon in the UCI coupon dataset.

## Objective
Analyze differences between drivers who accepted and rejected coupons, with a focus on bar-related coupons and customer characteristics such as:
- age
- marital status
- passenger type
- education
- income
- destination and travel context
- weather and time of day

## Dataset
The data comes from the UCI Machine Learning repository and is stored in:
- data/coupons.csv

## Key analyses performed
- Data loading and inspection
- Missing-value review and preprocessing
- Acceptance rate calculation
- Coupon type distribution
- Temperature distribution
- Focused analysis of bar coupon behavior
- Comparisons among driver subgroups:
    - frequent bar-goers vs. infrequent bar-goers
    - drivers under 30
    - drivers without kids and not widowed
    - drivers with low-income and frequent restaurant visits

## Example findings
The notebook shows that:
- overall coupon acceptance is about 56.8%
- bar coupon acceptance is about 41.0%
- bar-goers who visit bars more than three times per month show a much higher acceptance rate than those who visit fewer times

## Repository structure
- data/ — input dataset
- notebook(s) — analysis and visualizations
- README.md — project overview
- 
## Dataset Files and colab file name
- data/coupons.csv
- prompt.ipynb
- 
## Requirements
Install the following Python packages:
- pandas
- numpy
- matplotlib
- seaborn

## Run
Open the notebook in Jupyter and execute the cells in order.
