Customer Segmentation using K-Means Clustering
Overview
This repository contains a Python script for customer segmentation using K-Means clustering on a dataset of mall customers. The script utilizes popular data science libraries such as NumPy, Pandas, Matplotlib, Seaborn, and scikit-learn.

Project Structure
Customer_Segmentation.ipynb: Jupyter Notebook containing the script for customer segmentation.
Mall_Customers.csv: CSV file containing the dataset.
Installation
Clone the repository:

bash
Copy code
git clone https://github.com/your-username/customer-segmentation.git
Install the required libraries:

bash
Copy code
pip install numpy pandas matplotlib seaborn scikit-learn
Run the Jupyter Notebook Customer_Segmentation.ipynb to execute the customer segmentation script.

Dataset
The dataset (Mall_Customers.csv) contains information about mall customers, including their annual income, age, gender, and spending score.

Usage
Open the Jupyter Notebook and run each cell to perform the following tasks:

Data exploration and visualization.
Customer segmentation using K-Means clustering.
Visualization of the segmented customers based on annual income and spending score.
Visualizations
The notebook includes various visualizations such as:

Distribution of annual income, age, and spending score.
Bar plots depicting the number of customers in different age groups and spending score ranges.
Scatter plots showing the relationship between age and annual income, age and spending score, and annual income and spending score.
Elbow point graph for determining the optimal number of clusters in K-Means clustering.
Scatter plot of customers colored by cluster label after segmentation.
Conclusion
The K-Means clustering algorithm is applied to segment customers based on their annual income and spending score. The optimal number of clusters is determined using the elbow method, and customers are visualized in scatter plots based on their clusters.

Feel free to explore and modify the script to suit your specific requirements.

Note: Ensure that you have Python and Jupyter Notebook installed on your system before running the script.

Enjoy exploring customer segmentation with K-Means clustering!
