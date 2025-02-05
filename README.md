# Hierarchical Clustering and Multidimensional Scaling (MDS)

## Project Overview
This project focuses on applying **Hierarchical Clustering** and **Multidimensional Scaling (MDS)** techniques to analyze patent data from 13 Telecom companies. The objective is to measure the similarity between companies based on their patents and visualize these relationships using clustering and MDS plots.

## Dataset
- **Name:** Patents_xls.zip  
- **Contents:** 13 Excel files, each containing patents (Title + Abstract) for a Telecom company.

## Project Workflow
1. **Data Preparation:**  
   - Unzip the `Patents_xls.zip` file.
   - Load and merge Title and Abstract for each company's patents to create a corpus.

2. **Data Preprocessing:**  
   - Text cleaning (removal of stopwords, punctuation, and special characters).
   - Tokenization and normalization.
   - Vectorization (TF-IDF or similar methods).

3. **Cosine Distance Calculation:**  
   - Compute pairwise cosine distances between the patent corpora of different companies.

4. **Hierarchical Clustering:**  
   - Use the distance matrix to perform hierarchical clustering.
   - Visualize the dendrogram to identify clusters of companies with similar patent content.

5. **Multidimensional Scaling (MDS):**  
   - Apply MDS to project high-dimensional data into 2D space.
   - Visualize the relationships between companies based on patent similarity.

## Technologies Used
- **Python Libraries:** pandas, numpy, sklearn, scipy, matplotlib, seaborn

## How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/hierarchical-clustering-mds.git
   ```
2. Navigate to the project directory:
   ```bash
   cd hierarchical-clustering-mds
   ```
3. Install the required libraries:
   ```bash
   pip install -r requirements.txt
   ```
4. Run the main script:
   ```bash
   python main.py
   ```

## Results
- **Dendrogram:** Displays hierarchical clustering of Telecom companies.
- **MDS Plot:** Visual representation of companies in a 2D space based on cosine distances.


---
**Author:** Nivetha Thangaraj  
**Date:** February 2025

