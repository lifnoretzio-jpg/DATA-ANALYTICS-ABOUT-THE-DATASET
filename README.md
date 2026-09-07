Got it — you want **this exact content expanded into a proper 8-page practical record**, without changing the topic. Here is the expanded version.

# EX. NO. 3

# DATA ANALYTICS ABOUT THE DATASET

---

# PAGE 1 – AIM AND INTRODUCTION

## AIM

To perform data analytics on a given dataset using Python and Pandas, understand the characteristics of the dataset, identify different types of data, examine missing values, and prepare the dataset for further analysis and machine learning.

## INTRODUCTION

Data Analytics is the process of examining, cleaning, transforming, and interpreting data to discover useful information, patterns, trends, and relationships.

In today's digital world, a large amount of data is generated every day. Data is collected from websites, mobile applications, social media, banking systems, hospitals, educational institutions, sensors, and businesses.

Raw data by itself may not provide useful information. Data analytics helps convert raw data into meaningful information that can be used for decision-making and prediction.

A dataset usually contains:

* **Rows** – Individual observations or records.
* **Columns** – Attributes or features describing each record.
* **Numerical data** – Values represented by numbers.
* **Categorical data** – Values represented by categories or labels.

In this experiment, the dataset contains information about customers and their purchasing behavior.

The four attributes are:

1. Country
2. Age
3. Salary
4. Purchased

The dataset contains **10 records and 4 columns**.

Python is widely used for data analytics because it provides powerful libraries for data processing. One of the most important libraries is **Pandas**, which provides DataFrame structures and functions for handling datasets.

## OBJECTIVES

The main objectives of this experiment are:

* To understand the concept of Data Analytics.
* To study the structure of a dataset.
* To identify different types of data.
* To examine rows and columns.
* To identify missing values.
* To understand publicly available datasets.
* To understand real-time datasets.
* To prepare data for further analysis and machine learning.

---

# PAGE 2 – THEORY: WHAT IS DATA ANALYTICS?

## 1. WHAT IS DATA ANALYTICS?

Data Analytics is the systematic process of studying data to obtain meaningful information.

It involves collecting, organizing, cleaning, transforming, analyzing, and interpreting data.

The general data analytics process is:

**Data Collection → Data Understanding → Data Cleaning → Data Transformation → Data Analysis → Interpretation**

## DATA COLLECTION

Data collection is the first stage of data analytics.

Data can be collected from:

* Surveys
* Databases
* Websites
* Mobile applications
* Sensors
* IoT devices
* Social media
* Government sources
* Business applications

The quality of collected data directly affects the quality of analysis.

## DATA UNDERSTANDING

After collecting the data, the dataset must be examined.

Data understanding involves identifying:

* Number of rows
* Number of columns
* Column names
* Data types
* Missing values
* Duplicate records
* Range of numerical values

## DATA CLEANING

Data cleaning is the process of identifying and correcting errors in a dataset.

Common problems include:

* Missing values
* Duplicate records
* Incorrect data
* Invalid entries
* Inconsistent formats

Cleaning the dataset improves the reliability of the analysis.

## DATA TRANSFORMATION

Data transformation converts data into a suitable format for analysis.

Examples include:

* Converting categorical values into numerical values.
* Scaling numerical values.
* Changing data formats.
* Creating new features.

## DATA ANALYSIS

During analysis, different statistical and computational methods are applied to identify patterns and relationships.

For example, an e-commerce company may analyze customer:

* Country
* Age
* Salary
* Product purchase information

This analysis can help identify customer purchasing patterns.

## INTERPRETATION

The final results are interpreted to obtain useful conclusions.

The results can be used for:

* Decision-making
* Prediction
* Business planning
* Research
* Machine learning

---

# PAGE 3 – DATASET

## DATASET

A dataset is a collection of related data organized in the form of rows and columns.

Each row represents an individual observation or record, while each column represents an attribute or feature.

In this experiment, the dataset contains information about customers and their purchasing behavior.

The four attributes are:

| Attribute | Description                                | Type        |
| --------- | ------------------------------------------ | ----------- |
| Country   | Country of the customer                    | Categorical |
| Age       | Age of the customer                        | Numerical   |
| Salary    | Salary of the customer                     | Numerical   |
| Purchased | Whether the customer purchased the product | Categorical |

## DATASET CHARACTERISTICS

The dataset contains:

* **Number of records = 10**
* **Number of columns = 4**
* **Numerical attributes = 2**
* **Categorical attributes = 2**

### COUNTRY

Country represents the geographical location of the customer.

Examples:

* France
* Spain
* Germany

Country is a **categorical variable**.

### AGE

Age represents the age of the customer.

It contains numerical values and can be used for mathematical and statistical calculations.

Therefore, Age is a **numerical variable**.

### SALARY

Salary represents the salary or annual income of the customer.

It is represented using numerical values.

Therefore, Salary is a **numerical variable**.

### PURCHASED

Purchased represents whether the customer purchased a product.

It contains categories such as:

* Yes
* No

Therefore, Purchased is a **categorical variable**.

## SAMPLE DATASET

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

---

# PAGE 4 – TYPES OF DATA

## 1. NUMERICAL DATA

Numerical data consists of values represented using numbers.

Numerical data can be used for mathematical operations such as:

* Addition
* Subtraction
* Average
* Minimum
* Maximum
* Standard deviation

In the given dataset:

* Age is numerical.
* Salary is numerical.

### EXAMPLES

Age:

20, 25, 30, 35, 40

Salary:

30000, 45000, 60000, 75000

Numerical data can be classified into discrete and continuous data.

## DISCRETE DATA

Discrete data consists of countable values.

Examples:

* Number of students
* Number of products
* Number of customers
* Number of vehicles

## CONTINUOUS DATA

Continuous data can take any value within a particular range.

Examples:

* Height
* Weight
* Temperature
* Time

## 2. CATEGORICAL DATA

Categorical data represents groups, labels, or categories.

In the given dataset:

* Country is categorical.
* Purchased is categorical.

Country contains:

* France
* Spain
* Germany

Purchased contains:

* Yes
* No

## DIFFERENCE BETWEEN NUMERICAL AND CATEGORICAL DATA

| Numerical Data                           | Categorical Data                                     |
| ---------------------------------------- | ---------------------------------------------------- |
| Represents numbers                       | Represents categories                                |
| Mathematical operations can be performed | Mathematical operations are generally not meaningful |
| Example: Age                             | Example: Country                                     |
| Example: Salary                          | Example: Purchased                                   |

## IMPORTANCE OF IDENTIFYING DATA TYPES

Identifying data types is an important step in data analytics.

Different types of data require different processing methods.

For example, the average Age or Salary can be calculated because they are numerical.

However, calculating an average for Country is not meaningful because Country contains categories.

Before applying machine learning algorithms, categorical variables may need to be converted into numerical representations.

---

# PAGE 5 – PUBLICLY AVAILABLE DATASET

## PUBLICLY AVAILABLE DATASET

A publicly available dataset is a collection of data made accessible to students, researchers, developers, and the general public.

These datasets can usually be downloaded or accessed online for analysis and research.

Public datasets are commonly used for:

* Data Analytics
* Data Science
* Machine Learning
* Artificial Intelligence
* Research
* Laboratory experiments

Public datasets allow students to practice data analysis without collecting data themselves.

## COMMON DATASET FORMATS

Public datasets may be available in formats such as:

* CSV
* Excel
* JSON
* XML
* Text
* Images
* Audio

### CSV

CSV stands for **Comma-Separated Values**.

It is one of the most commonly used formats for storing tabular datasets.

## SOURCES OF PUBLIC DATASETS

Examples include:

### UCI Machine Learning Repository

A collection of datasets commonly used for machine learning and research.

### Kaggle

A popular platform that provides datasets and resources for data science and machine learning.

### Government Open Data Portals

Governments provide datasets related to public services, education, health, transportation, economy, and other areas.

### Google BigQuery Public Datasets

Provides access to publicly available datasets that can be analyzed using cloud-based tools.

### India's Open Government Data Platform

The platform **data.gov.in** provides publicly accessible datasets related to areas such as:

* Education
* Health
* Environment
* Economy
* Agriculture
* Science and Technology
* Transport

## EXAMPLES OF PUBLIC DATASETS

### Iris Dataset

Used for flower classification.

### Heart Disease Dataset

Used for healthcare-related analysis and prediction.

### Student Performance Dataset

Used to analyze student academic performance.

### Online Retail Dataset

Used for customer purchasing and retail analysis.

### Weather Dataset

Used for analyzing environmental and weather information.

## ADVANTAGES

Public datasets:

* Reduce data collection effort.
* Provide real-world information.
* Help students learn analytics.
* Support research.
* Can be used for machine learning.
* Allow different analytical techniques to be tested.

---

# PAGE 6 – REAL-TIME DATASET

## REAL-TIME DATASET

A real-time dataset contains data that is generated or collected continuously from a real-world system.

The data is made available for processing and analysis immediately or with very little delay after it is generated.

Real-time data can continuously change as new observations arrive.

## SOURCES OF REAL-TIME DATA

Real-time data is often produced by:

* Sensors
* IoT devices
* Mobile applications
* GPS devices
* Smart meters
* Websites
* Financial systems
* Medical devices

## EXAMPLES OF REAL-TIME DATA

### 1. SMART TRAFFIC

Traffic monitoring systems can collect:

* Vehicle speed
* Vehicle count
* Traffic density
* Vehicle location

This information can be used to monitor traffic and improve transportation systems.

### 2. SMART GRID

Smart electricity systems can collect:

* Electricity consumption
* Voltage
* Current
* Power usage
* Smart-meter readings

This information can be used to monitor electricity consumption.

### 3. HEALTHCARE

Medical devices can continuously collect:

* Heart rate
* Blood pressure
* Temperature
* Oxygen level

Real-time analysis can help monitor patient conditions.

### 4. WEATHER

Weather systems can collect:

* Temperature
* Humidity
* Rainfall
* Wind speed

This information can be used for weather monitoring and forecasting.

### 5. BANKING

Banking systems generate data such as:

* Transactions
* Payments
* Account activity

Real-time analytics can help monitor financial activity.

### 6. E-COMMERCE

E-commerce platforms generate real-time information such as:

* Customer clicks
* Product views
* Orders
* Purchases

This information can be used to understand customer behavior.

### 7. TRANSPORTATION

Transportation systems can collect:

* Vehicle location
* Speed
* Travel time
* Traffic conditions

This information can be used for route planning and traffic management.

## STATIC DATA VS REAL-TIME DATA

| Static Dataset               | Real-Time Dataset            |
| ---------------------------- | ---------------------------- |
| Usually collected beforehand | Continuously generated       |
| Changes infrequently         | Continuously changes         |
| Can be analyzed later        | Often analyzed immediately   |
| Example: Student dataset     | Example: Traffic sensor data |
| Example: Iris dataset        | Example: GPS data            |

---

# PAGE 7 – PYTHON AND PANDAS DATA ANALYSIS

## PYTHON

Python is a popular programming language used for data analytics, data science, artificial intelligence, and machine learning.

Python provides several libraries for data analysis.

One of the most important libraries is **Pandas**.

## PANDAS

Pandas is a Python library used for:

* Data manipulation
* Data cleaning
* Data analysis
* Data transformation
* Handling tabular data

Pandas provides a data structure called a **DataFrame**, which represents data in rows and columns.

## PROGRAM

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

print("Dataset:")
print(df)

print("\nFirst five records:")
print(df.head())

print("\nDataset Information:")
df.info()

print("\nStatistical Description:")
print(df.describe())

print("\nMissing Values:")
print(df.isnull().sum())

print("\nShape of Dataset:")
print(df.shape)
```

## IMPORTANT PANDAS FUNCTIONS

### `pd.DataFrame()`

Creates a DataFrame from the given data.

### `head()`

Displays the first five records.

### `info()`

Displays information about:

* Number of entries
* Column names
* Data types
* Non-null values

### `describe()`

Provides statistical information about numerical columns.

It includes:

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

This means:

* 10 rows
* 4 columns

## MISSING VALUE CHECK

The following statement is used:

```python
df.isnull().sum()
```

If all values returned are zero, there are no missing values in the corresponding columns.

---

# PAGE 8 – RESULT, APPLICATIONS AND CONCLUSION

## ANALYSIS AND INTERPRETATION

After analyzing the dataset using Python and Pandas, the following observations can be made:

1. The dataset contains **10 records**.
2. The dataset contains **4 columns**.
3. Country is a categorical attribute.
4. Age is a numerical attribute.
5. Salary is a numerical attribute.
6. Purchased is a categorical attribute.
7. Pandas can be used to examine the structure of the dataset.
8. Missing values can be checked using `isnull()`.
9. Statistical information can be obtained using `describe()`.
10. The dataset can be prepared for further analysis and machine learning.

## DATA PREPARATION FOR MACHINE LEARNING

Before applying a machine learning algorithm, the dataset may require preprocessing.

### 1. HANDLING MISSING VALUES

Missing values can be:

* Removed
* Replaced with mean
* Replaced with median
* Replaced with mode

### 2. ENCODING CATEGORICAL DATA

Categorical data such as Country and Purchased may need to be converted into numerical form.

For example:

**Purchased**

* Yes → 1
* No → 0

### 3. FEATURE SCALING

Numerical attributes such as Age and Salary may have different ranges.

Feature scaling can be applied when required by the machine learning algorithm.

### 4. REMOVING UNNECESSARY DATA

Unnecessary columns can be removed to improve the quality of analysis.

## APPLICATIONS OF DATA ANALYTICS

Data analytics is widely used in many fields.

### BUSINESS

Used for sales analysis, customer analysis, and business decision-making.

### HEALTHCARE

Used for analyzing patient information and medical data.

### EDUCATION

Used for studying student performance and attendance.

### BANKING

Used for transaction analysis and financial monitoring.

### E-COMMERCE

Used for analyzing customer purchasing behavior.

### TRANSPORTATION

Used for traffic analysis, route planning, and vehicle monitoring.

### WEATHER

Used for analyzing weather patterns and forecasting.

### MANUFACTURING

Used for production monitoring and quality analysis.

## RESULT

The given customer dataset was successfully studied using Python and Pandas. The characteristics of the dataset, types of data, number of records and columns, and missing-value analysis were understood.

## CONCLUSION

Thus, the dataset and Data Analytics concepts were studied successfully.

The customer dataset containing **Country, Age, Salary, and Purchased** attributes was analyzed. The differences between numerical and categorical data were identified. The concepts of publicly available datasets and real-time datasets were also studied along with their applications.

Python and Pandas provide useful tools for examining, cleaning, transforming, and analyzing datasets. The knowledge gained from this experiment can be used for further data analysis, machine learning, and artificial intelligence applications.
