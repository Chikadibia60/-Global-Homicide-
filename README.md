
**Discovering Global Homicide Patterns Using K-Means Clustering**

## Project Overview

You can post this with your project:

> I built a **machine learning project exploring global homicide trends using K-Means clustering**.
>
> The analysis includes **feature engineering, clustering evaluation, PCA visualization, and a full ML pipeline** built with Scikit-Learn.
>
> Using over **22,000 global crime records**, the model identified meaningful patterns in homicide rate behavior across countries.
>
> Tools: Python, Pandas, Scikit-Learn, Seaborn, Matplotlib.
>
> GitHub: *(insert link)*

-
This project explores **global homicide rate patterns** using **unsupervised machine learning**.
By applying **K-Means clustering**, the model groups countries with similar homicide trends, revealing hidden crime patterns across the world.

The workflow includes **feature engineering, data preprocessing, clustering evaluation, dimensionality reduction, and visualization**.


## Dataset

Global homicide statistics containing:

* Country
* Year
* Gender
* Age Group
* Homicide Rate (per 100,000 people)

Total observations: **22,000+ records**

---

## Key Features Engineered

To capture trend behavior:

* **rate_delta** – year-to-year change in homicide rate
* **moving_avg** – 3-year rolling average
* **prev_year_rate** – previous year homicide rate

---

## Machine Learning Approach

A **Scikit-Learn Pipeline** was used for:

* Feature scaling (`StandardScaler`)
* Categorical encoding (`OneHotEncoder`)
* Clustering (`KMeans`)

Cluster selection was evaluated using:

* **Silhouette Score**
* **Calinski-Harabasz Index**
* **Inertia**

Best result:

* **Clusters:** 2
* **Silhouette Score:** **0.617**

---

## Visual Analysis

To interpret the clusters:

* **PCA projection**
* Cluster distribution plots
* Homicide trend visualization
* Feature comparison across clusters

---

## Technologies

* Python
* Pandas
* Scikit-Learn
* Matplotlib
* Seaborn
* Joblib

---

## Author

**Obiaeli Chika**
Machine Learning & Data Science Enthusiast

