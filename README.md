# Ex03-Univariate-Analysis

# Aim
To read the given dataset and perform univariate analysis.

# Explanation
Univariate analysis is basically the simplest form to analyze data. Uni means one and this means that the data has only one kind of variable. The major reason for univariate analysis is to use the data to describe. The analysis will take data, summarise it, and then find some pattern in the data.

# DATE:

GITHUB LINK: https://github.com/viswapriyaG/Ex03-Univariate-Analysis.git

COLAB LINK: https://colab.research.google.com/drive/1cjczNOYtRbYNm3uc7e4G6uZVQfj3x0Qb#scrollTo=BMSpf46T7_M-

# Algorithm
## Step1 

Read the given data.

## Step2 

Get the information about the data.

## Step3 

Remove the null values from the data.

## Step4 

Mention the datatypes from the data.

## Step5 

Count the values from the data.

## Step6 

Do plots like boxplots,countplot,distribution plot,histogram plot.

# CODE

DEVELOPED BY: VISWA PRIYA G

REGISTER NUMBER: 212221220061

```
import pandas as pd
import numpy as np
import seaborn as sns
df=pd.read_csv("SuperStore.csv")
print(df)

df.info()

df.describe()

df.isnull().sum()

df.dtypes

df['Row ID'].value_counts()

sns.boxplot(x="Row ID", data=df)

sns.countplot(x="Row ID", data=df)

sns.distplot(df["Row ID"])

sns.histplot(x="Row ID", data=df)

```

# OUTPUT

Dataset 

![a](https://github.com/viswapriyaG/Ex03-Univariate-Analysis/assets/131427787/08fc4807-ddfe-4a16-88dc-382bd3e714b8)


Dataset info

![b](https://github.com/viswapriyaG/Ex03-Univariate-Analysis/assets/131427787/726aab46-addc-4f49-9c9f-34901a6d7586)


Dataset describe

![c](https://github.com/viswapriyaG/Ex03-Univariate-Analysis/assets/131427787/3be3493e-8787-4c13-97fb-d63b577ff00b)


Null value

![d](https://github.com/viswapriyaG/Ex03-Univariate-Analysis/assets/131427787/688bfba5-bf91-43d3-b7bd-f6976e0be896)


Data types

![e](https://github.com/viswapriyaG/Ex03-Univariate-Analysis/assets/131427787/dfc4bb67-546c-457f-8179-10e45f6a3d3c)


Value count

![f](https://github.com/viswapriyaG/Ex03-Univariate-Analysis/assets/131427787/f75a8fc3-6c13-4190-83c1-b3db5b8ab1f3)


Boxplot

![g](https://github.com/viswapriyaG/Ex03-Univariate-Analysis/assets/131427787/b1d54164-c166-4a00-9cc4-414600ebcc4f)


Count plot

![h](https://github.com/viswapriyaG/Ex03-Univariate-Analysis/assets/131427787/8d4b7ff8-81ab-4e4e-b4d6-bf8bace5115d)


Distribution plot

![i](https://github.com/viswapriyaG/Ex03-Univariate-Analysis/assets/131427787/eeebd181-eacc-4241-9401-cbab3c8dea92)


Histogram plot

![j](https://github.com/viswapriyaG/Ex03-Univariate-Analysis/assets/131427787/723326ad-085e-4989-8204-6ca77aafc715)


# Result:
Thus we have read the given data and performed the univariate analysis with different types of plots.
