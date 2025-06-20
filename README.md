# Importing Dataset with Pandas in Python

<p align="center">
  <a href="https://skills.network" target="_blank">
    <img src="https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/assets/logos/SN_web_lightmode.png" width="300" alt="Skills Network Logo">
  </a>
</p>

---

## Estimated Time Needed  
**15 minutes**

---

## Objectives

After completing this lab, you will be able to:

- Acquire data in various ways  
- Obtain insights from data using the Pandas library

---

## Table of Contents

1. [Data Acquisition](#data-acquisition)  
2. [Basic Insights from the Data Set](#basic-insights-from-the-data-set)  

---

## Data Acquisition

A data set is typically a file containing data stored in formats such as `.csv`, `.json`, `.xlsx`, etc. The data may be stored locally, on a server, a website, or cloud storage.

To analyze data in a Python notebook, you must load the dataset into your environment.

This lab uses the Automobile data set, available online as a CSV:

- **Data source:** [Automobile Data Set](https://archive.ics.uci.edu/ml/machine-learning-databases/autos/imports-85.data)  
- **Data type:** CSV

We use the Pandas library, which is pre-installed in Jupyter notebooks, to load and manipulate data.

### Reading the Data

To read CSV files, we use:

```python
import pandas as pd

df = pd.read_csv('file_path_or_url')
