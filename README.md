## Customer-Segmentation-Clustering-Analysis
Comparative Analysis of K-Mean and Agglomerative Clustering for Customer Segmentation

## Table of Contents
- [Introduction](#introduction)
- [Objective](#objective)
- [Dataset Description](#dataset-description)
- [Dataset Source](#data-Source)
- [Data Mining Techniques and Procedures](#data-mining-techniques-and-procedures)
  - [Importing Libraries and Reading the Dataset](#importing-libraries-and-reading-the-dataset)
  - [Data Exploration and Visualization](#data-exploration-and-visualization)
  - [Data Transformation and Preprocessing](#data-transformation-and-preprocessing)
- [Exploratory Data Analysis (EDA)](#exploratory-data-analysis-eda)
- [Implementation in Python](#implementation-in-python)
  - [Clustering Algorithms](#clustering-algorithms)
  - [Results Visualization](#results-visualization)
- [Conclusion](#conclusion)
- [License](#license)

## Introduction
In today's data-driven landscape, clustering algorithms like **K-Means** and **Agglomerative Clustering** play a crucial role in discovering customer diversity through segmentation. This analysis aims to highlight the power of these tools in socio-demographic studies and targeted marketing.

## Objective
The goal is to conduct a comparative analysis of K-Mean and Agglomerative clustering models for customer segmentation, focusing on socio-demographic factors such as income, employment, age, and settlement size.

## Dataset Description
The study uses a dataset with 2000 entries, detailing individuals' socio-economic positions and demographics. Variables include:
- Customer Id
- Sex
- Marital Status
- Age
- Education
- Income
- Occupation
- Settlement Size

## Data Source
The dataset used in this project is sourced from publicly available data repositories. For more details, refer to the [original dataset](https://www.kaggle.com/datasets/dev0914sharma/customer-clustering).

## Data Mining Techniques and Procedures
### Importing Libraries and Reading the Dataset
The project begins with the loading of the dataset into a Jupyter notebook using Python's `pandas` library for preprocessing and exploration.

### Data Exploration and Visualization
Utilizing libraries such as `matplotlib` and `seaborn`, I perform an initial exploration and visual representation of the data to identify patterns and relationships.

### Data Transformation and Preprocessing
Preprocessing steps include standardizing numerical values and selecting relevant features for clustering.

## Exploratory Data Analysis (EDA)
A detailed EDA provides insights into the distribution and relationships of demographic attributes, using various visualizations to paint a comprehensive picture of the data structure.

## Implementation in Python
### Clustering Algorithms
- **KMeans Clustering:** Segments data into k non-overlapping clusters.
- **Agglomerative Hierarchical Clustering:** Builds a hierarchy of clusters using a bottom-up approach.

### Results Visualization
The clusters formed by each algorithm are visually represented through scatter plots and dendrograms, allowing for an intuitive comparison of their efficacy.

## Conclusion
The study provides a comparative look at how K-Means and Agglomerative Clustering can be used for customer segmentation, highlighting the strengths of each method in revealing customer diversity.

## License
This project is made available under the MIT License. See the [LICENSE](LICENSE.md) file for full details.

---

**Note:** For a detailed exploration of the methodologies, dataset, and findings, refer to the complete analysis documentation included in this repository.
