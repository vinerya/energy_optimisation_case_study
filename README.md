# Company X Data Science Challenge

Welcome to the **Company X Data Science Challenge**! This challenge is designed to assess your skills in optimization, forecasting, and data exploration—key competencies we value in our data scientists. Additionally, it evaluates your ability to quickly understand and address problems that our products solve.

## Table of Contents

- [Overview](#overview)
- [Challenge Structure](#challenge-structure)
  - [Question 1 - Optimization](#question-1---optimization)
    - [Question 1.1](#question-11)
    - [Question 1.2](#question-12)
  - [Question 2 - Optimization Utilizing Forecasting](#question-2---optimization-utilizing-forecasting)
  - [Question 3 - Data Exploration](#question-3---data-exploration)
- [Instructions](#instructions)
- [Further Reads](#further-reads)

## Overview

This challenge consists of **3 questions** focusing on:

1. **Optimization**
2. **Forecasting**
3. **Data Exploration**

These questions simulate a simplified version of the problems our products address at Company X. We encourage you to approach the questions in any order, emphasizing areas where you feel strongest while efficiently progressing through the others.

**Note:** If you're unfamiliar with optimization techniques, **Question 1.2** might be challenging. However, **Question 1.1** can be approached effectively with heuristic methods.

## Challenge Structure

### Question 1 - Optimization

You are provided with data for a **1MW, 1MWh battery**, which can charge and discharge at a maximum power of 1 MW and store up to 1 MWh of energy. The goal is to maximize profits by buying electricity when wholesale prices are low and selling when they are high, utilizing the battery to store electricity between these transactions.

**Data Provided:**

- Day-ahead 60-minute data containing hourly wholesale electricity prices for the first 6 months of 2022.

**Assumption:**

- Full information: All prices are known in advance.

#### Question 1.1

**Task:**

For each day in the dataset, determine the profit-maximizing times to charge and discharge the battery.

**Deliverables:**

- Illustrative findings showing:
  - Total revenue earned.
  - Optimal times of day for charging and discharging.
- List of any assumptions made.

#### Question 1.2

**Scenario Update:**

The battery specifications change to **1 MW, 2 MWh**, allowing:

- Charging for 2 hours at full power when completely empty.
- Discharging for 2 hours at full power when completely full.
- Partial charging/discharging (e.g., half full) by adjusting the charging/discharging duration.

**Task:**

Re-evaluate your approach from **Question 1.1** based on the new battery specifications.

### Question 2 - Optimization Utilizing Forecasting

**Scenario:**

You must decide the charging and discharging times at the beginning of each day without prior knowledge of that day's or future prices. However, you have access to historical price data to inform your decisions.

**Battery Specifications:**

- **1MW, 1MWh** (as in Question 1.1).

**Task:**

- Design a strategy for charging and discharging under these constraints.
- Explain your approach, particularly how you train your trading strategy using available historical information.
- Illustrate your findings and compare them with the results from **Question 1.1**.

### Question 3 - Data Exploration

**Data Provided:**

- **60-minute data:** Prices for hourly electricity contracts.
- **15-minute data:** Prices for 15-minute electricity contracts.

Both datasets cover the first 6 months of 2022.

**Task:**

- Summarize and statistically compare both datasets.
- Identify shared patterns and differences.
- Recommend which type of contract (**15-minute** or **60-minute**) would be more beneficial for trading at Company X, based on your analysis.

