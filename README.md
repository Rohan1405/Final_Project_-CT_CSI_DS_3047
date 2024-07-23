# Customer Lifetime Value Prediction

## Overview

Predicting the future value of a customer to a business over the entire duration of their relationship is crucial for enhancing business strategies. This project incorporates various factors such as past purchase history, frequency of purchases, and customer demographics to predict customer lifetime value (CLV).

## Project Highlights

- **Innovative Approach**: Introduces a new dimension called Inter-Purchase Time (T) to the traditional RFM (Recency, Frequency, Monetary) model.
- **Customer Segmentation**: Enhances segmentation by analyzing customer purchasing behavior more deeply.
- **Modeling**: Uses the KMeans algorithm to cluster customers based on their RFM attributes and Inter-Purchase Time.

## Resources

- [Online Retail Dataset](https://www.kaggle.com/datasets/lakshmi25npathi/online-retail-dataset) - The dataset used for this analysis.

## Key Sections

<div style="border: 2px solid #ff4d4d; border-radius: 8px; background-color: #ffe6e6; padding: 15px; margin: 20px 0; box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);">
    <h2 style="color: #ff4d4d;">1. Customer Lifetime Value Prediction</h2>
    <p>This section provides an overview of the project and its objectives. We introduce the concept of Inter-Purchase Time (T) and discuss its significance in improving the traditional RFM model.</p>
</div>

<div style="border: 2px solid #ff4d4d; border-radius: 8px; background-color: #ffe6e6; padding: 15px; margin: 20px 0; box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);">
    <h2 style="color: #ff4d4d;">2. Introduction</h2>
    <p>Explains customer segmentation and its importance in maintaining long-term customer relationships. Emphasizes the need for better market segmentation and consumer behavioral studies.</p>
</div>

<div style="border: 2px solid #ff4d4d; border-radius: 8px; background-color: #ffe6e6; padding: 15px; margin: 20px 0; box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);">
    <h2 style="color: #ff4d4d;">3. Importing the Libraries</h2>
    <p>Lists and imports the essential libraries used in the project, including <code>pandas</code>, <code>numpy</code>, <code>seaborn</code>, and <code>matplotlib</code>.</p>
</div>

<div style="border: 2px solid #ff4d4d; border-radius: 8px; background-color: #ffe6e6; padding: 15px; margin: 20px 0; box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);">
    <h2 style="color: #ff4d4d;">4. Loading and Reading the Dataset</h2>
    <p>Describes how the dataset is loaded and read into the environment. Provides an overview of the data's structure and contents.</p>
</div>

<div style="border: 2px solid #ff4d4d; border-radius: 8px; background-color: #ffe6e6; padding: 15px; margin: 20px 0; box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);">
    <h2 style="color: #ff4d4d;">5. Data Wrangling</h2>
    <p>Covers various data cleaning steps:
        <ul>
            <li>Handling missing values</li>
            <li>Removing canceled products</li>
            <li>Deleting duplicates</li>
            <li>Checking for negative values</li>
            <li>Cleaning outliers</li>
        </ul>
    </p>
</div>

<div style="border: 2px solid #ff4d4d; border-radius: 8px; background-color: #ffe6e6; padding: 15px; margin: 20px 0; box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);">
    <h2 style="color: #ff4d4d;">6. EDA Feature Engineering</h2>
    <p>Explains the process of creating new features:
        <ul>
            <li>Calculating the Revenue</li>
            <li>Constructing RFM features</li>
            <li>Introducing the Interpurchase Time feature</li>
        </ul>
    </p>
</div>

<div style="border: 2px solid #ff4d4d; border-radius: 8px; background-color: #ffe6e6; padding: 15px; margin: 20px 0; box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);">
    <h2 style="color: #ff4d4d;">7. Modeling with KMeans Algorithm</h2>
    <p>Describes the modeling phase using the KMeans algorithm:
        <ul>
            <li>Finding the optimal number of clusters using the Elbow Method</li>
            <li>Visualizing clusters and their distribution</li>
            <li>Evaluating clustering quality</li>
        </ul>
    </p>
</div>

<div style="border: 2px solid #ff4d4d; border-radius: 8px; background-color: #ffe6e6; padding: 15px; margin: 20px 0; box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);">
    <h2 style="color: #ff4d4d;">8. Model Evaluation</h2>
    <p>Evaluates the performance and stability of the clustering model using various metrics:
        <ul>
            <li>Silhouette score</li>
            <li>Davies-Bouldin Index</li>
            <li>Cluster Stability Score</li>
        </ul>
    </p>
</div>




   
