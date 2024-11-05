# LITA-CAPSTONE-PROJECT-2

### Project Title: Customers Data
---

- [Project Overview](#project-overview)
- [Data Sources](#data-sources)
- [Tools Used](#tools-used)
- [Data Cleaning and Preparation](#data-cleaning-and-preparation)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Data Analysis](#data-analysis)
- [Results](#results)
- [Recommendations](#recommendations)

### Project Overview 
---

### Data Sources
---
Excel file

### Tools Used
---
- Microsoft Excel
  1. For data cleaning
  2. For analysis
  3. For visualization
- Structured Query Language (SQL)
  1. For querying
  2. For analysis
- Microsoft Power BI
  1. For visualization
  2. For reports
- GitHub
  1. For portfolio building

### Data Cleaning and Preparation 
---
Data cleaning was performed at the initial phase of the analysis. It was carried out using the Microsoft Excel. The actions included;
 1. Data loading and inspection
 2. Removing duplicate data
 3. Formating and cleaning

![17308300632549041690275114795339](https://github.com/user-attachments/assets/34b76131-e06f-43a4-9929-8e9600e0d1f2)


### Exploratory Data Analysis 
---

The exploratory data analysis examined the customers' performance based on their region, revenue generated, and subscription type. The following questions were explored during the data analysis phase. They include;



### Data Analysis 
---
```
SELECT
  Region,
  COUNT (customer_id) AS total customers
FROM
  customers
GROUP BY
  region
ORDER BY
  total_customers DESC;
```

![17308301512174502959904179562460](https://github.com/user-attachments/assets/9b612607-bc5a-40f9-b9fc-c5c185753b39)


### Results 
---

![1730830221272851012269982373616](https://github.com/user-attachments/assets/3fac7930-1da2-402e-9f1d-b1605167593a)

