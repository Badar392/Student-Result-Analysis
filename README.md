## Student Performance Analysis: Exploratory Data Analysis (EDA)

## Project Overview

This project presents a complete **Exploratory Data Analysis (EDA)** workflow applied to a student performance dataset.
The main objective is to investigate how various demographic and socio-economic factors influence academic outcomes — specifically **math**, **reading**, and **writing** scores.

The analysis demonstrates essential **data science techniques** including data preparation, descriptive analytics, and visual storytelling — making it an excellent **portfolio project** for aspiring data analysts or data scientists.



##  Key Features

The project adheres to a standard data analytics workflow, emphasizing structured exploration and clear insights:

* **Data Acquisition & Quality Assessment:**
  Initial inspection for data integrity, structure, and types.

* **Descriptive Statistics:**
  Computation of central tendencies, spread, and score distributions.

* **Data Cleaning & Preparation:**
  Handling of missing data, duplicate entries, and categorical normalization.

* **Comparative Analysis:**
  Evaluation of how academic scores vary across categorical dimensions:

  * **Gender** – Score distribution comparison between male and female students.
  * **Parental Education** – Influence of parents’ education level on student outcomes.


* **Data Visualization:**
  Effective visual communication using:

  * **Boxplots:** To highlight score variance and median differences.
  * **Pie Charts:** To illustrate student distribution by ethnic groups.


## 💻 Technical Stack

| Component                   | Technology                      | Purpose                                |
| :-------------------------- | :------------------------------ | :------------------------------------- |
| **Development Environment** | Google Colab                    | Interactive, cloud-based analysis      |
| **Programming Language**    | Python                          | Core data analytics language           |
| **Data Libraries**          | Pandas, NumPy                   | Data manipulation and computation      |
| **Visualization Tools**     | Matplotlib, Seaborn             | Plotting and statistical visualization |



##  Dataset

**Source:** Public dataset from [Kaggle: Student Exam Scores Extended Dataset](https://www.kaggle.com/)

**Key Columns:**

* `gender`
* `ethnic group`
* `parental level of education`
* `lunch type`
* `test preparation course`
* `math score`
* `reading score`
* `writing score`



## Setup & Execution (Google Colab)

Designed for **Google Colab**, the setup is simple and requires no local configuration.

### 1️⃣ Launch the Environment

* Go to [Google Colab](https://colab.research.google.com/)
* Create a **new notebook** and connect to a runtime.

### 2️⃣ Install Dependencies

Google Colab comes preloaded with the required libraries.
However, you can manually install them if needed:

```python
!pip install pandas numpy matplotlib seaborn
```

###  Import Libraries

At the beginning of your notebook:

```python
import numpy as np
import pandas as pd
import matplotlib.pyplot as plt
import seaborn as sns

sns.set(style="whitegrid", palette="pastel")
```

###  Load the Dataset

You can upload your dataset manually to Colab or access it from Google Drive:

```python
from google.colab import files
uploaded = files.upload()

df = pd.read_csv('/data.csv')
---

### Output Highlights

* Summary statistics tables for numerical features.
* Boxplots and histograms visualizing score distributions.
* Grouped mean comparisons by demographic factors.
* Correlation insights between score categories.

---

##  Future Enhancements

Potential next steps include:

* Predictive modeling using regression or classification techniques.
* Feature importance analysis via tree-based models.
* Integration of socio-behavioral factors (e.g., study hours, extracurricular participation).

---

## Author

**Project Author:** *[Muhammad Badar Maaz]*
**Role:** Data Analyst 

---


