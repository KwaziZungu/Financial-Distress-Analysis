# Financial Distress

## 1. Summary

In this project we focus on using predictive analysis to figure out which companies will be in financial distress depending on their characteristics. From the dataset that's analysed, you will notice that dummy/abstract labels are used for the data, i.e. Company names are labelled company 1, company 2, etc. Regardless, the analysis is still very useful as the algorithm can easily be applied to data containing real companies with all their features in avail.

For this analysis, the **Support Vector Machine Algorithm** is used, taking advantage of scikit-learn's **Support Vector Classifier** method. The **SVM** was chosen because because the data contains dozens of features and this algorithm has been favoured for these types of applications.

Feel free to tackle the code yourself, and see how this algorithm fares against other machine learning methods, or improve on it as you see fit. I would love to view your analysis.

## 2. Relevant Files

Let's take a brief look at some relevant featured files in this projects

### (a) Financial_Distress.csv

[Financial_Distress.csv](Financial_Distress.csv) contains the original data, raw and unedited. Useful for referencing and reproducing, or improving, on the processes performed in this project.

### (b) requirements.txt

[requirements.txt](requirements.txt) is a typical requirements file in software engineering, which is composed of packages and software required to run the given code.
Thankfully, a lot of the packages used are common community softwares and you should have no problem installing them on your machine.

### (c) main.ipynb

[main.ipynb](main.ipynb) is a python jupyter notebook file where all of our coding and analysis takes place. Familiarity with python is required of course but the code has been divided into sections:

1. Packages
2. Initialise Data
3. Model
4. Testing

for the code to be easy to read.

## 3. Dataset Structure

The data contains _3673_ rows with _86_ columns.

- The **first row** is the header.
- **First column**, called **Company** lists all the companies, with _422_ companies in total (note the companies are listed/labelled as numbers).
- **Second column**, called **Time** shows the time periods, also labelled as numbers.
- **Third column**, called **Financial Distress** tells us about the financial distress level of the company at that period in time. Although this is shown as random floating numbers, note that if the value in this column is less than _-0.5_ then the company is in distress but it is healthy otherwise.
- The remaining _83_ columns, called **'x1', 'x2', ..., 'x83'** are features for each company at each time period.

As an example on how to read this data using the first _3_ columns,
company _1_ was financially healthy at time _3_ but it was in distress at time _4_.

## 4. Machine Learning Algorithm Used

## 5. Results

## 6. Recommendations
