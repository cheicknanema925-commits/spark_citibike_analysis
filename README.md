<div align="center">



\# 🚲 Citi Bike NYC (2016)  

\### Big Data Analysis with Apache Spark \& PySpark



Large-scale analysis of New York City bike-sharing trips using distributed data processing.



</div>



---



\## 📌 Overview



This repository contains a \*\*complete Big Data analysis project\*\* based on \*\*Citi Bike NYC trip data (2016)\*\*.  

The analysis is implemented in a \*\*Jupyter Notebook\*\* using \*\*Apache Spark and PySpark\*\*, showcasing an end-to-end data analytics workflow on a real-world dataset.



This project is published as a \*\*personal portfolio project\*\*.



---



\## 🎯 Project Goals



\- Process large CSV datasets using \*\*Apache Spark\*\*

\- Perform data cleaning and preprocessing at scale

\- Execute analytical queries with \*\*Spark SQL\*\* and \*\*DataFrame API\*\*

\- Analyze temporal usage patterns and station popularity

\- Visualize key insights from bike-sharing data



---



\## 🧰 Tech Stack



| Category | Tools |

|--------|------|

| Big Data | Apache Spark |

| Processing | PySpark (SQL \& DataFrame API) |

| Language | Python 3 |

| Environment | Jupyter Notebook |

| Visualization | Matplotlib, Pandas |



---



\## 📊 Dataset



The dataset is provided by \*\*Citi Bike New York City Open Data\*\* and contains anonymized trip records.



🔗 \*\*Official portal\*\*  

https://citibikenyc.com/system-data  



🔗 \*\*Direct download (2016 data)\*\*  

https://s3.amazonaws.com/tripdata/2016-citibike-tripdata.zip  



\*\*Dataset characteristics:\*\*

\- Monthly CSV files (January–December 2016)

\- Millions of trip records

\- Start/end time and stations

\- Trip duration and user type

\- Optional demographic information



> ⚠️ Due to its size, the dataset is \*\*not included\*\* in this repository.



---



\## 📁 Expected Data Structure



After downloading and extracting the dataset:
2016-citibike-tripdata/

└── data/

└── 2016/

├── 201601-citibike-tripdata.csv

├── 201602-citibike-tripdata.csv

├── ...

└── 201612-citibike-tripdata.csv

---

## 📊 Data Visualizations

Below are some key visualizations generated directly from the Spark-based analysis notebook.

### 🚲 Monthly Number of Trips (2016)

This bar chart shows the total number of Citi Bike trips per month in 2016.  
It clearly highlights the **strong seasonality** of bike usage, with a peak during summer months.

<p align="center">
  <img src="image/visualisation1.png" alt="Monthly CitiBike Trips 2016" width="700"/>
</p>

---

### 📈 Daily Evolution of Trips (Day 1–365)

This time-series plot represents the **daily number of trips throughout the year**.  
It reveals:
- gradual growth from winter to summer
- high variability during peak season
- a decline toward the end of the year

<p align="center">
  <img src="image/visualisation2.png" alt="Daily CitiBike Trips 2016" width="800"/>
</p>

---

> 📌 All visualizations are produced using data processed with **Apache Spark** and plotted in the Jupyter Notebook.




