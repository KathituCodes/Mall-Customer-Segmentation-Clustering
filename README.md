#  Mall Customer Segmentation & Clustering

## Problem Statement
Businesses need to understand their customers better in order to provide more personalized services and improve marketing strategies. In this project, we explore customer segmentation using clustering techniques based on key features like age, annual income, and spending score.

## Objective
The goal of this project was to:
- Analyze customer data from a mall.
- Group customers into segments using clustering algorithms.
- Visualize these segments for insights that can guide business decisions.

## Project Pipeline
1. **Data Loading & Exploration**  
   - Imported necessary Python libraries and loaded the dataset.
   - Performed univariate and bivariate analysis to understand customer behavior.
   
2. **Clustering Techniques**  
   - Applied KMeans clustering on:
     - Univariate data (e.g., annual income).
     - Bivariate data (e.g., income vs. spending score).
     - Multivariate combinations of features.
   - Used Elbow Method and Silhouette Score to determine optimal number of clusters.

3. **Visualization**  
   - Used `matplotlib` and `seaborn` for visual analysis of the clusters.
   - Created intuitive graphs for decision-makers.

4. **GUI Implementation (Optional)**  
   - A basic GUI was created to make segmentation results more interactive.

## Challenges Faced
- Determining the ideal number of clusters required careful analysis.
- Data didn't include categorical variables like gender or location, limiting some segmentation possibilities.
- Avoiding overfitting while maintaining interpretability in cluster outputs.

## Results
- Successfully segmented mall customers into distinct groups based on behavioral and financial metrics.
- Visualizations clearly showed differences between customer types (e.g., high income, low spenders vs. low income, high spenders).
- Final clusters provide a solid basis for personalized marketing and business targeting strategies.

## Files
- `Python_Mall_Customer_Segmentation_&_Clustering.ipynb`: Full notebook with code, visualizations, and clustering implementation.

## Tools & Libraries Used
- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn

## Future Work
- Incorporate demographic features like gender, location, and shopping frequency.
- Apply advanced clustering methods like DBSCAN or hierarchical clustering.
- Integrate customer feedback data for qualitative segmentation.

---

### Author
Urbanus Kathitu  
