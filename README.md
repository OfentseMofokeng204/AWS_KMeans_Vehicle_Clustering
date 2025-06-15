# AWS_KMeans_Vehicle_Clustering
# 🚗 Vehicle Clustering with KMeans  
**An Unsupervised Machine Learning Project using K-Means Clustering**

## 📌 Overview

This project is part of the **AWS AI & Machine Learning Learning Path** and focuses on applying **unsupervised learning** to cluster vehicles based on their specifications.

Using synthetic data representing various vehicle attributes, we implement a **KMeans clustering algorithm** to group vehicles with similar characteristics. This approach can be useful in applications like product segmentation, market analysis, and design optimization.

## 🎯 Objective

Cluster vehicles based on key attributes such as:

- **Weight**
- **Engine Size**
- **Horsepower**

…to identify natural groupings or similarities in the vehicle dataset without using predefined labels.

## 🛠️ Technologies Used

- **Python**
- **Pandas** – for data manipulation  
- **NumPy** – for generating synthetic numerical data  
- **Matplotlib** – for visualization  
- **scikit-learn** – for implementing KMeans clustering
- 
## 📊 How It Works

1. **Synthetic Data Generation**:  
   300 samples of vehicle data are randomly generated to simulate a real-world dataset.

2. **Feature Selection**:  
   All three numeric features are used directly for clustering.

3. **Modeling with KMeans**:  
   A KMeans model with `n_clusters=3` is trained to find natural groupings.

4. **Visualization**:  
   The clustered results are visualized in a 2D scatter plot using `Weight` and `Horsepower`, with colors indicating different clusters.

## 📁 Project Structure

```bash
vehicle-clustering/
│
├── vehicle_clustering.ipynb      # Jupyter Notebook with all steps
├── README.md                     # Project description
└── sample_output.png             # Example of the final clustering plot
