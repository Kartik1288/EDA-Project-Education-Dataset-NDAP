# EDA-Project-Education-Dataset-NDAP


**Project Title:**  Exploratory Data Analysis of Indian School Infrastructure


**Date:** November 15, 2023

**## Overview**

The GetUp project aims to provide a comprehensive analysis of the state of educational infrastructure across India. We believe that access to quality infrastructure is a crucial factor in ensuring equal educational opportunities for all children.  This project delves into the Indian schools dataset, uncovering patterns, disparities, and potential areas for improvement in infrastructure.

**## Key Findings**

* **Disparities Exist:** There are significant variations in the availability of essential infrastructure across different states in India.
* **Technology Integration:** Schools are increasingly adopting technology, with a higher prevalence of tablets and laptops compared to traditional desktop computers.
* **Cluster Analysis:** We identified three distinct clusters of schools based on infrastructure levels:
    * *Cluster 0:* Good Infrastructure, Basic Facilities, Limited Resources
    * *Cluster 1:* Best Infrastructure, Advanced Facilities, Adequate Resources
    * *Cluster 2:* Inadequate Infrastructure, Intermediate Facilities, Abundant Resources
* **Focus on the Northeast:** Our analysis highlights a need to improve infrastructure in the northeastern states of India, despite the availability of resources in the region.

**## Methodology**

1. **Data Source:** The dataset was obtained from the NDAP Portal and uploaded by the Unified District Information System for Education (UDISE).
2. **Data Preprocessing:**
    * Removed redundant and irrelevant features
    * Handled missing values 
    * Mitigated outliers
    * Created a new feature ('computers') to represent technology resources.
3. **Exploratory Data Analysis (EDA):**  
    * Examined distributions and correlations.
4. **Clustering:**
    * Employed K-Means and Hierarchical Clustering to group schools based on infrastructure.
    * Utilized Elbow Method and Silhouette Score to determine the optimal number of clusters.
5.  **Dimension Reduction:**
    * Applied Principal Component Analysis (PCA) to identify key influencing factors. 
    * Used Multidimensional Scaling (MDS) to visualize the non-linear structure of the data.

**## Jupyter Notebook**

The Jupyter Notebook attached to this project (**Final_Notebook.ipynb**) contains a detailed walkthrough of our work, including:

* Code for data preprocessing
* Visualizations from EDA
* Implementation of clustering algorithms
* Results and interpretations from dimension reduction techniques.


