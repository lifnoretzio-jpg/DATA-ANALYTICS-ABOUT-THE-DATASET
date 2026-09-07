Absolutely. Below is the **complete 8-page record format** for **EX. NO. 3 – Data Analytics About the Dataset**, expanded so you can copy it directly into Word.

# EX. NO. 3

# DATA ANALYTICS ABOUT THE DATASET

---

# PAGE 1 – AIM AND INTRODUCTION

## AIM

To perform data analytics on a given dataset using Python and Pandas, understand the characteristics of the dataset, identify different types of data, examine missing values, and prepare the dataset for further analysis and machine learning.

## INTRODUCTION

Data Analytics is the process of examining, cleaning, transforming, and interpreting data to discover useful information, patterns, trends, and relationships.

In the modern world, huge amounts of data are generated every day from websites, mobile applications, businesses, sensors, social media, banking systems, and other digital platforms. Data analytics helps convert this raw data into meaningful information that can support decision-making.

A dataset generally contains:

* **Rows** – Individual observations or records.
* **Columns** – Attributes or features describing each record.
* **Numerical Data** – Data represented using numbers.
* **Categorical Data** – Data represented using categories or labels.

In this experiment, the dataset contains information about customers and their purchasing behavior.

The four attributes are:

1. **Country**
2. **Age**
3. **Salary**
4. **Purchased**

The dataset contains **10 records and 4 columns**.

The dataset can be analyzed using the Python programming language and the **Pandas library**. Pandas provides useful functions for reading, displaying, examining, cleaning, and analyzing datasets.

## OBJECTIVE

The main objectives of this experiment are:

* To understand the concept of data analytics.
* To load a dataset using Python.
* To examine the structure of the dataset.
* To identify numerical and categorical attributes.
* To check for missing values.
* To understand dataset characteristics.
* To prepare data for further analysis and machine learning.

---

# PAGE 2 – THEORY: DATA ANALYTICS

## 1. WHAT IS DATA ANALYTICS?

Data Analytics is the systematic process of studying, processing, and interpreting data to obtain useful information.

It involves collecting data, understanding its structure, cleaning incorrect or missing values, transforming the data, performing analysis, and interpreting the results.

The general data analytics process can be represented as:

**Data Collection → Data Understanding → Data Cleaning → Data Transformation → Data Analysis → Interpretation**

### Data Collection

Data is collected from different sources such as databases, websites, surveys, sensors, applications, and public datasets.

### Data Understanding

The collected dataset is examined to understand:

* Number of rows
* Number of columns
* Column names
* Data types
* Values present in each column

### Data Cleaning

Data cleaning involves identifying and correcting problems such as:

* Missing values
* Duplicate records
* Incorrect values
* Inconsistent formats
* Invalid entries

### Data Transformation

Data may need to be transformed into a suitable format for analysis.

Examples include:

* Converting categorical data into numerical form.
* Scaling numerical values.
* Changing date formats.
* Removing unnecessary columns.

### Data Analysis

Statistical and computational methods are applied to identify patterns and relationships in the data.

### Interpretation

The results obtained from analysis are interpreted to obtain meaningful conclusions.

## IMPORTANCE OF DATA ANALYTICS

Data analytics is important because it helps organizations:

* Make better decisions.
* Identify trends and patterns.
* Understand customer behavior.
* Predict future outcomes.
* Improve business performance.
* Detect errors and unusual activities.
* Support machine learning applications.

For example, an e-commerce company can analyze customer age, salary, country, and purchasing information to understand which customers are more likely to purchase a product.

---

# PAGE 3 – DATASET AND DATASET CHARACTERISTICS

## DATASET

A dataset is a collection of related data organized in the form of rows and columns.

Each row represents one observation or record, while each column represents an attribute or feature.

In this experiment, the dataset contains customer information.

The attributes are:

| Column    | Description                                | Data Type   |
| --------- | ------------------------------------------ | ----------- |
| Country   | Country of the customer                    | Categorical |
| Age       | Age of the customer                        | Numerical   |
| Salary    | Salary of the customer                     | Numerical   |
| Purchased | Whether the customer purchased the product | Categorical |

## SAMPLE DATASET

The customer dataset contains 10 records:

| Country | Age | Salary | Purchased |
| ------- | --: | -----: | --------- |
| France  |  44 |  72000 | No        |
| Spain   |  27 |  48000 | Yes       |
| Germany |  30 |  54000 | No        |
| Spain   |  38 |  61000 | No        |
| Germany |  40 |  64000 | Yes       |
| France  |  35 |  58000 | Yes       |
| Spain   |  32 |  52000 | No        |
| France  |  48 |  79000 | Yes       |
| Germany |  50 |  83000 | No        |
| France  |  37 |  67000 | Yes       |

## CHARACTERISTICS OF THE DATASET

The important characteristics of this dataset are:

* Number of records = **10**
* Number of attributes = **4**
* Categorical columns = **Country, Purchased**
* Numerical columns = **Age, Salary**

### Country

Country represents the geographical location of the customer. It is categorical data because it contains labels such as France, Spain, and Germany.

### Age

Age represents the customer's age. It is numerical data because it is represented using numbers.

### Salary

Salary represents the customer's salary. It is numerical data.

### Purchased

Purchased indicates whether the customer purchased the product. It contains categorical values such as Yes and No.

---

# PAGE 4 – TYPES OF DATA

## 1. NUMERICAL DATA

Numerical data contains values represented using numbers.

Numerical data can be used for mathematical and statistical calculations.

In the given dataset:

* **Age** is numerical data.
* **Salary** is numerical data.

### Examples

Age:

22, 25, 30, 35, 40

Salary:

35000, 45000, 55000, 65000

Numerical data can be further divided into:

### Discrete Data

Discrete data consists of countable values.

Examples:

* Number of students
* Number of products
* Number of customers

### Continuous Data

Continuous data can take values within a range.

Examples:

* Height
* Weight
* Temperature
* Time

## 2. CATEGORICAL DATA

Categorical data represents groups, labels, or categories.

In the given dataset:

* **Country** is categorical.
* **Purchased** is categorical.

Examples of Country:

* France
* Spain
* Germany

Examples of Purchased:

* Yes
* No

Categorical data is generally not directly used for mathematical calculations. In machine learning, it may need to be converted into numerical form.

## DIFFERENCE BETWEEN NUMERICAL AND CATEGORICAL DATA

| Numerical Data                       | Categorical Data                                     |
| ------------------------------------ | ---------------------------------------------------- |
| Represents numbers                   | Represents labels/categories                         |
| Mathematical operations are possible | Mathematical operations are generally not meaningful |
| Example: Age                         | Example: Country                                     |
| Example: Salary                      | Example: Purchased                                   |

## IMPORTANCE OF IDENTIFYING DATA TYPES

Identifying data types is an important step in data analytics because different types of data require different processing methods.

For example, the average salary can be calculated because Salary is numerical. However, calculating the average of Country does not make sense because Country is categorical.

---

# PAGE 5 – PUBLICLY AVAILABLE DATASETS

## PUBLICLY AVAILABLE DATASET

A publicly available dataset is a collection of data that is accessible to students, researchers, developers, and the general public.

Public datasets are commonly used for:

* Data Analytics
* Data Science
* Machine Learning
* Artificial Intelligence
* Research
* Laboratory experiments

Public datasets allow students and researchers to practice data analysis without having to collect the data themselves.

## COMMON DATASET FORMATS

Public datasets can be available in several formats:

* CSV
* Excel
* JSON
* XML
* Text
* Images
* Audio

The **CSV (Comma-Separated Values)** format is one of the most commonly used formats for data analytics.

## SOURCES OF PUBLIC DATASETS

Examples of public dataset sources include:

1. **UCI Machine Learning Repository**
2. **Kaggle**
3. **Government Open Data Portals**
4. **Google BigQuery Public Datasets**
5. **India's Open Government Data Platform – data.gov.in**

India's Open Government Data Platform provides publicly accessible datasets related to areas such as:

* Education
* Health
* Environment
* Economy
* Science and Technology
* Agriculture
* Transport

## EXAMPLES OF PUBLIC DATASETS

### Iris Dataset

Used for flower classification based on characteristics such as sepal and petal measurements.

### Heart Disease Dataset

Used for healthcare-related data analysis and prediction.

### Student Performance Dataset

Contains information about students and their academic performance.

### Online Retail Dataset

Contains information related to customer purchases and retail transactions.

### Weather Dataset

Contains environmental information such as temperature, rainfall, humidity, and wind speed.

## ADVANTAGES OF PUBLIC DATASETS

Public datasets:

* Save data collection time.
* Provide real-world information.
* Help students learn data analytics.
* Support research activities.
* Can be used to develop machine learning models.
* Allow comparison of analytical methods.

---

# PAGE 6 – REAL-TIME DATASET

## REAL-TIME DATASET

A real-time dataset contains data that is generated or collected continuously from a real-world system.

The data can be processed immediately or with very little delay after it is generated.

Unlike a static dataset, real-time data can continuously change as new observations arrive.

## SOURCES OF REAL-TIME DATA

Real-time data is commonly generated by:

* Sensors
* IoT devices
* Mobile applications
* GPS devices
* Smart meters
* Websites
* Financial systems
* Medical devices

## EXAMPLES OF REAL-TIME DATASETS

### 1. SMART TRAFFIC

Real-time traffic systems can collect:

* Vehicle speed
* Vehicle count
* Traffic density
* Vehicle location

This information can be analyzed to monitor traffic conditions and improve transportation systems.

### 2. SMART GRID

Smart electricity systems can collect:

* Electricity consumption
* Voltage
* Current
* Power usage
* Smart-meter readings

This information can help monitor electricity usage.

### 3. HEALTHCARE

Medical devices can continuously collect:

* Heart rate
* Blood pressure
* Temperature
* Oxygen level

Real-time analysis can help healthcare systems monitor patients.

### 4. WEATHER

Weather monitoring systems collect:

* Temperature
* Humidity
* Rainfall
* Wind speed

The data can be used for weather monitoring and forecasting.

### 5. BANKING

Banking systems generate data related to:

* Transactions
* Payments
* Account activity

Real-time analytics can help detect unusual transactions and monitor financial activities.

### 6. E-COMMERCE

Online shopping platforms generate real-time data such as:

* Customer clicks
* Product views
* Orders
* Purchases

This information can be analyzed to understand customer behavior.

### 7. TRANSPORTATION

Transportation systems can collect:

* Vehicle location
* Speed
* Travel time
* Traffic conditions

This data can be used for route planning and transportation management.

## STATIC DATASET VS REAL-TIME DATASET

| Static Dataset                   | Real-Time Dataset            |
| -------------------------------- | ---------------------------- |
| Usually collected beforehand     | Continuously generated       |
| Does not change frequently       | Continuously changes         |
| Can be stored and analyzed later | Often analyzed immediately   |
| Example: Student dataset         | Example: GPS location data   |
| Example: Iris dataset            | Example: Traffic sensor data |

---

# PAGE 7 – PYTHON PROGRAM AND DATA ANALYSIS

## PYTHON PROGRAM

The following Python program uses the **Pandas** library to examine the customer dataset.

```python
import pandas as pd

# Create the dataset
data = {
    'Country': ['France', 'Spain', 'Germany', 'Spain', 'Germany',
                'France', 'Spain', 'France', 'Germany', 'France'],
    'Age': [44, 27, 30, 38, 40, 35, 32, 48, 50, 37],
    'Salary': [72000, 48000, 54000, 61000, 64000,
               58000, 52000, 79000, 83000, 67000],
    'Purchased': ['No', 'Yes', 'No', 'No', 'Yes',
                  'Yes', 'No', 'Yes', 'No', 'Yes']
}

df = pd.DataFrame(data)

# Display the dataset
print("Dataset:")
print(df)

# Display first five records
print("\nFirst five records:")
print(df.head())

# Display dataset information
print("\nDataset Information:")
print(df.info())

# Display statistical information
print("\nStatistical Description:")
print(df.describe())

# Check missing values
print("\nMissing Values:")
print(df.isnull().sum())

# Display shape of dataset
print("\nShape of Dataset:")
print(df.shape)
```

## IMPORTANT PANDAS FUNCTIONS

### `pd.DataFrame()`

Creates a DataFrame from the given data.

### `head()`

Displays the first five records of the dataset.

### `info()`

Provides information about:

* Number of entries
* Column names
* Data types
* Non-null values

### `describe()`

Provides statistical information about numerical columns, including:

* Count
* Mean
* Standard deviation
* Minimum
* Maximum

### `isnull().sum()`

Checks the number of missing values in each column.

### `shape`

Returns the number of rows and columns.

For this dataset:

**Shape = (10, 4)**

This means there are **10 rows and 4 columns**.

## MISSING VALUE ANALYSIS

Missing values are empty or unavailable values in a dataset.

They must be identified before performing further analysis or machine learning.

The following command is used:

```python
df.isnull().sum()
```

If the result is zero for all columns, the dataset does not contain missing values.

---

# PAGE 8 – ANALYSIS, APPLICATIONS AND CONCLUSION

## DATA ANALYSIS INTERPRETATION

After examining the dataset using Pandas, the following observations can be made:

1. The dataset contains **10 customer records**.
2. There are **4 attributes**.
3. Country and Purchased are categorical attributes.
4. Age and Salary are numerical attributes.
5. The dataset can be represented using a Pandas DataFrame.
6. Missing values can be identified using `isnull()`.
7. Statistical information about numerical columns can be obtained using `describe()`.
8. The dataset is suitable for further preprocessing and machine learning.

## DATA PREPARATION FOR MACHINE LEARNING

Before using a dataset for machine learning, several preprocessing operations may be required.

### 1. Handling Missing Values

Missing values can be:

* Removed
* Replaced with mean
* Replaced with median
* Replaced with mode

### 2. Encoding Categorical Data

Categorical attributes such as Country and Purchased may need to be converted into numerical values.

For example:

**Purchased**

* Yes → 1
* No → 0

### 3. Feature Scaling

Numerical values such as Age and Salary may have different ranges. Scaling can be applied when required by the machine learning algorithm.

### 4. Removing Unnecessary Data

Columns that do not contribute to the analysis can be removed.

## APPLICATIONS OF DATA ANALYTICS

Data analytics is widely used in:

* **Business** – Sales and customer analysis.
* **Healthcare** – Patient and medical data analysis.
* **Education** – Student performance analysis.
* **Banking** – Transaction and fraud analysis.
* **E-commerce** – Customer purchasing behavior.
* **Transportation** – Traffic and route analysis.
* **Weather** – Weather pattern analysis.
* **Manufacturing** – Production and quality analysis.

## RESULT

The given customer dataset was successfully studied using Python and Pandas. The dataset characteristics, number of rows and columns, numerical and categorical attributes, and missing-value checking were analyzed.

## CONCLUSION

Thus, the concepts of **Data Analytics, datasets, numerical data, categorical data, publicly available datasets, and real-time datasets** were studied successfully.

The customer dataset containing **Country, Age, Salary, and Purchased** attributes was examined using Python and Pandas. The structure and characteristics of the dataset were identified, and methods for checking missing values and preparing the data for further analysis and machine learning were understood.

Data analytics plays an important role in converting raw data into useful information and supports effective decision-making in various real-world applications.
