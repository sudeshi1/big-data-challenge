# Big Data Challenge: Alexa, can you handle big data? 📦

## Background 🌎

- Many of Amazon's shoppers depend on product reviews to make a purchase. Amazon makes these datasets publicly available 
- However, they are quite large and can exceed the capacity of local machines to handle. One dataset alone contains over 1.5 million rows; with over 40 datasets, this can be quite taxing on the average local computer

**Goal** 🥅
- Perform ETL process completely in the cloud and upload a DataFrame to an RDS instance
- The second goal will be to use PySpark or SQL to perform a statistical analysis of selected data

**Step 1:** Create DataFrames to match production-ready tables from two big Amazon customer review datasets

**Step 2:** Analyze whether reviews from Amazon's Vine program are trustworthy

![Amazon GIF](/images/1.gif)

## Requirements 👩🏻‍💻

1. Notebook: *Google Collab*
2. Scripting: *Python*
3. Libraries Used: *os, findspark, PySpark*
4. *AWS RDS*

![Code](/images/1.jpg)

## Accomplishments 🎯

### Level 1 1️⃣

- Used the furnished schema to create tables in the RDS database
- Created two separate Google Colab notebooks and extracted any two datasets from the list at review dataset, one into each notebook.

#### Tasks ✅

1. Count the number of records (rows) in the dataset
2. Transform the dataset to fit the tables in the schema file
3. Load the DataFrames that correspond to tables into an RDS instance

### Level 2 2️⃣

- In Amazon's Vine program, reviewers receive free products in exchange for reviews

**Amazon has several policies to reduce the bias of its Vine reviews: [Vine Reviews](https://www.amazon.com/gp/vine/help?ie=UTF8)**

#### Tasks ✅

1. Investigate whether Vine reviews are free of bias
2. Use either PySpark or SQL to analyze the data


