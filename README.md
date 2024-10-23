# Customer Segmentation using Clustering Algorithms

## Project Overview
This project tackles a classic business problem faced by retail stores: how can we better understand our customers beyond surface-level demographics? Analyzing customer data from a mall, aimed to uncover deep, actionable insights that can transform marketing strategies and customer engagement.

## Problem Statement
Understanding customer behaviour is key to optimizing retail strategies. In this project, I used unsupervised machine learning techniques to segment customers based on spending patterns and demographic features. This can help businesses target marketing campaigns, optimize store layouts, personalize promotions, and improve customer retention.

## Approach
We experimented with four clustering algorithms:
- **K-Means Clustering**
- **DBSCAN (Density-Based Spatial Clustering)**
- **Hierarchical Clustering**
- **Gaussian Mixture Models (GMM)**

### Evaluation Metrics
To evaluate the performance of these models, we used two key metrics:
- **Silhouette Score**
- **Calinski-Harabasz Index**

### Key Findings
After a thorough evaluation, **K-Means Clustering** emerged as the most suitable model, with a Silhouette score of **0.555**. This allowed us to identify five distinct customer personas:

1. **Average Balanced Spenders**
   - Age: 42 years
   - Income: $55.3k
   - Spending habits: Moderate
   - Regular mall visitors.
   
2. **High Income Savers**
   - Age: 41 years
   - Income: $88.2k
   - Spending habits: Low
   - Target group for marketers.
   
3. **Budget Conscious Seniors**
   - Age: 45 years
   - Income: $26.3k
   - Spending habits: Conservative
   - Value seekers.

4. **Young Enthusiastic Spenders**
   - Age: 25 years
   - Income: $25.7k
   - Spending habits: High
   - FOMO-driven consumers.

5. **Affluent Shoppers**
   - Age: 33 years
   - Income: $86.5k
   - Spending habits: Highest
   - The dream customers for retailers.

## Technologies Used
- **Python**
- **scikit-learn**
- **Pandas**
- **Matplotlib**

## Why This Matters
Each customer segment provides a unique perspective that can help retailers develop:
- **Targeted marketing campaigns**
- **Optimized store layouts**
- **Personalized promotions**
- **Better customer retention strategies**

## How to Run the Code
1. Clone the repository:
    ```bash
    git clone https://github.com/avinishaaa/Mall-Segmentation-Algorithms.git
    ```
2. Install the required packages:
    ```bash
    pip install -r requirements.txt
    ```
3. Run the notebook: Open `MallSegmentation.ipynb` in Jupyter Notebook or any other supported platform.

## Future Work
- Explore more clustering techniques.
- Analyze additional features, such as time spent in the mall.
- Test the approach on larger datasets.

## Let's Connect
I’d love to hear your thoughts and feedback on this project. Feel free to open an issue or contact me directly for suggestions, collaborations, or discussions about customer behavior analytics.
