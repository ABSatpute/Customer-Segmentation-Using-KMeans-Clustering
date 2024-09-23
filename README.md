<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta name="description" content="Customer Segmentation Using KMeans Clustering">
</head>
<body>

  <h1>Customer Segmentation Using KMeans Clustering</h1>

  <p>This project aims to segment customers of a mall based on their <strong>Age</strong>, <strong>Annual Income</strong>, and <strong>Spending Score</strong>. The segmentation helps in identifying distinct customer groups for targeted marketing and improved customer experience.</p>

  <h2>Business Problem</h2>
  <p>Mall management faces a challenge in understanding the diverse needs of its customers. Without clearly defined customer segments, marketing strategies and promotional efforts lack precision, resulting in reduced customer engagement and inefficient allocation of marketing budgets. By segmenting customers based on demographic and behavioral data, the mall can tailor its marketing efforts and promotions to better meet the specific needs of different customer groups, leading to higher customer satisfaction and increased sales.</p>

  <h2>Project Objective</h2>
  <p>The goal is to group similar customers together using the <strong>KMeans Clustering</strong> algorithm, enabling the mall management to understand customer behavior and make data-driven decisions.</p>

  <h2>Dataset</h2>
  <p>The dataset consists of information on 200 mall customers, including the following attributes:</p>
  <ul>
    <li><strong>CustomerID</strong> (dropped for analysis)</li>
    <li><strong>Gender</strong></li>
    <li><strong>Age</strong> (in years)</li>
    <li><strong>Annual Income</strong> (in k$)</li>
    <li><strong>Spending Score</strong> (1-100)</li>
  </ul>

  <h2>Data Story</h2>
  <p>Our journey begins with a mall, eager to boost its business by understanding its customers better. Equipped with basic data—such as age, annual income, and spending score—the mall sought a way to make sense of these attributes to craft more targeted marketing campaigns. The challenge was to identify distinct customer segments from the noisy, mixed data they had on hand.</p>

  <p>We started by diving deep into the data, running descriptive statistics and visualizations to get a clear view of customer patterns. After cleansing and preparing the data, we leveraged the <strong>KMeans</strong> clustering algorithm, a powerful tool to help divide customers into homogeneous groups. Through the process, we identified distinct clusters, each representing a unique segment of customers.</p>

  <p>From the young, high-spending shoppers to the older, cost-conscious patrons, the data began to reveal the mall's customer landscape. Through visualizations and analysis, the mall now had a roadmap for delivering more personalized shopping experiences and efficient promotional offers. Each cluster represented an opportunity: a group of customers that could be engaged with more relevant, tailored strategies.</p>

  <h2>Project Workflow</h2>
  <ol>
    <li><strong>Data Exploration:</strong> Initial descriptive statistics and visualizations were performed to understand the data distribution and relationships.</li>
    <li><strong>Data Preprocessing:</strong> Handling of missing values and preparation of features for clustering.</li>
    <li><strong>Clustering:</strong> The <em>KMeans</em> algorithm was applied, and the <em>Elbow Method</em> was used to determine the optimal number of clusters.</li>
    <li><strong>Visualization:</strong> Clusters were visualized in 2D and 3D plots to interpret the customer segments.</li>
  </ol>

  <h2>Clustering Details</h2>

  <h3>1. Clustering Based on Age and Spending Score</h3>
  <p>Four customer segments were identified, based on customers' age and spending habits. The Elbow Method determined 4 clusters.</p>

  <h3>2. Clustering Based on Annual Income and Spending Score</h3>
  <p>Five customer segments were identified, focusing on customers' income levels and spending patterns. The Elbow Method suggested 5 clusters.</p>

  <h3>3. 3D Clustering Based on Age, Income, and Spending Score</h3>
  <p>Using all three features (Age, Income, and Spending Score), we created a comprehensive clustering model with distinct customer groups visualized in a 3D plot.</p>

  <h2>Insights and Recommendations</h2>
  <ul>
    <li><strong>High-Value Customers:</strong> Focus on high-income, high-spending customers for premium product offerings.</li>
    <li><strong>Young High-Spenders:</strong> Target young customers with high spending scores for tech and lifestyle products.</li>
    <li><strong>Moderate Spenders:</strong> Engage middle-income customers with loyalty programs and discounts.</li>
    <li><strong>Cost-Sensitive Shoppers:</strong> Provide value-for-money options for budget-conscious customers.</li>
  </ul>

  <h2>Conclusion</h2>
  <p>The KMeans clustering model provided valuable insights into customer segmentation. These insights can help the mall tailor its marketing strategies and improve customer engagement by focusing on specific groups of customers.</p>

  <h2>Technologies Used</h2>
  <ul>
    <li>Python</li>
    <li>scikit-learn</li>
    <li>pandas</li>
    <li>matplotlib</li>
    <li>seaborn</li>
  </ul>

  <h2>How to Run</h2>
  <ol>
    <li>Clone the repository: <code>git clone https://github.com/ABSatpute/Customer-Segmentation-Using-KMeans-Clustering.git</code></li>
    <li>Install required libraries: <code>pip install -r requirements.txt</code></li>
    <li>Run the Jupyter notebook to see the analysis and clustering process.</li>
  </ol>

  <h2>License</h2>
  <p>This project is licensed under the <a href="LICENSE">MIT License</a>.</p>

  <h2>Author</h2>
  <p>Developed by Akash Satpute</p>

</body>
</html>
