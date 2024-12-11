# Will the Customer Accept the Coupon?

This Jupyter Notebook analyzes bar and coffee house visit patterns and behaviors based on various factors such as companion type, time, weather, and age group accepting coupons. The analysis is mainly done to see different patterns in variables to see customer behavior in relation to coupon acceptance.

## Table of Contents
1. [Introduction](#introduction)
2. [Data Preprocessing](#data-preprocessing)
3. [Data Analysis and Visualizations](#data-analysis-and-visualizations)
4. [Key Observations and Insights](#key-observations-and-insights)
5. [Differences Between Coupon Accepting and Non-Accepting Customers](#differences-between-coupon-accepting-and-non-accepting-customers)
6. [Conclusion](#conclusion)
7. [Requirements](#requirements)
8. [Usage](#usage)

## Introduction
This notebook explores customer behavior and visit patterns to bars and coffee houses, with a focus on companion types (alone, friends, partner, kids) and factors like time of day, weather conditions, occupation and age group. The goal is to derive insights into when and with whom people visit bars, coffee houses the most, in order to enhance customer targeting and promotional strategies.

Additionally, we will compare the behaviors of customers who accepted coupons versus those who did not, in order to understand key trends that can help improve coupon marketing strategies.

## Data Preprocessing
- Imported and cleaned the dataset.
- Filtered relevant columns for analysis, including companion type, time, weather, and age group.
- Grouped the data by companion type and time, followed by aggregation to count occurrences.

## Data Analysis and Visualizations
- **Heatmap**: Visualized the frequency of visits based on companion type, time, weather, and age group.
- **Bar Plots**: Displayed counts of male and female visitors who accepted coupons, segmented by companion type and visit time.
- **Pivot Tables**: Used for segmenting the data based on multiple categorical variables.

## Key Observations for Bar w.r.t Accepting Coupon# My observations and hypotheses:
- **Frequent Bar Visits**: Drivers visiting bars more than once a month are likelier to accept coupons.
- **Age Factor**: Drivers over 25 years old accept bar coupons at higher rates.
- **Passenger Demographics**: Non-kid passengers and occupations outside farming, fishing, or forestry correlate with higher acceptance.
- **Lifestyle Choices**: Frequent visits to cheap restaurants and income under $50K also influence acceptance rates.
- **Social/Active Profiles**: Socially active and younger drivers tend to accept bar coupons more.

## Key Observations for Coffee House w.r.t Accepting Coupons
- **Peak times**: The most active visits occur at the Coffee House is at **10 AM Sunny**, with **friends** being the largest group.
- **Weather impact**: Visits are significantly reduced on rainy or snowy days.
- **Companion Type**: **Friends** are the most likely to visit, while visits from **kids** are the least frequent.

## Differences Between Coupon Accepting and Non-Accepting Customers
- **Coupon Acceptance Behavior**: 
   - Customers who accepted coupons are generally more likely to visit during **daytime hours** (10 AM and 2 PM), especially on **sunny days**.
   - Those who did not accept coupons tend to visit **later in the day** (6 PM onwards), with a slightly higher frequency during **rainy** and **snowy weather**.
   - The **companion type** also plays a role, with **friends** and **partners** more likely to accept coupons, while those visiting alone or with kids tend to decline the offer more frequently.
  
- **Age Group**:
   - **Younger age groups** (18-25) are more likely to accept coupons compared to older groups, especially when visiting with **friends**.
  
- **Weather and Time of Day**:
   - Coupon acceptors tend to favor **sunny weather** and are most active around **10 AM**. In contrast, non-acceptors tend to visit on **rainy** or **snowy** days, primarily in the late afternoon and evening.

## Conclusion
- **Key recommendation**: Focus promotions on **10 AM Sunny** with **friends** as the primary target group, especially targeting younger customers.
- **Weather impact**: Consider tailoring coupon strategies based on weather conditions, as customers are more likely to accept coupons during sunny weather.

## Requirements
- Python 3.x
- Pandas
- Seaborn
- Matplotlib

## Usage
1. Clone this repository:  
   ```bash
   git clone https://github.com/nabiharaza/amazon-mechanical-turk.git
2. Install the necessary dependencies:
   ```bash
    pip install -r requirements.txt
3. Run the notebook:
Open the `prompt.ipynb` file in Jupyter or any compatible environment.

