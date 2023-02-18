# Customer-Segmentation-python
This project is a small clustering exercise in which we use KNN algorithm to cluster customers of a mall based on their age, annual income, and spending score. The data is stored in a CSV file named "customersegmentation.csv".

The project is implemented using Python programming language and JupyterLab environment. The main file is "mall_customer_clustering.ipynb", which contains the code and the explanation of the steps taken to cluster the customers.

Prerequisites
To run this project, you need to have the following installed:

Python 3.x
JupyterLab
Required libraries: numpy, pandas, matplotlib, and scikit-learn.
Getting Started
Clone the project to your local machine using git clone https://github.com/TheMightyEmad/Customer-Segmentation-python.git.
Open JupyterLab and navigate to the project directory.
Open the "mall_customer_clustering.ipynb" file.
Run the code cells in order to see the output and results.
Data
The dataset contains the following columns:

CustomerID: unique ID assigned to the customer
Gender: gender of the customer (Male/Female)
Age: age of the customer
Annual Income (k$): annual income of the customer in thousands of dollars
Spending Score (1-100): score assigned by the mall based on customer behavior and spending nature
Results
The KNN algorithm was used to cluster the customers into different groups based on their age, annual income, and spending score. The number of clusters was determined by the elbow method. The results were visualized using a scatter plot, which shows the distribution of the customers among the clusters.

Conclusion
In this project, we used the KNN algorithm to cluster the customers of a mall based on their age, annual income, and spending score. The results show that the customers can be grouped into different clusters based on these features, which can be used to target specific customer groups with marketing strategies.
