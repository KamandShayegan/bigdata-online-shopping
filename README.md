# E-Shopping Clickstream - A Big Data Analysis

## Introduction
In this project, we analyzed a clickstream dataset from an online store for maternity clothing. We started with a review of related works and a detailed description of the dataset, including schema and data types. Using Matplotlib, we visualized the data with bar and pie charts to explore distributions and relationships. Our analysis included predictive modeling with a Gradient Boosted Tree, evaluated using various techniques, yielding promising results. We also applied association rule mining to uncover significant patterns, using metrics like support, confidence, and lift. Clustering analysis revealed natural groupings in the data, enhancing our understanding. Overall, these analyses provide insights for developing further predictive models on practical features. Check out the complete report analysis [here](https://docs.google.com/document/d/1NK89SPzYWs3y18eXTLbReuBRhSjyfPMD17CS1p-qzvA/edit?usp=sharing).

## Contributors
- Kamand Sedaghat Shayegan (grade: 5/5)
- Nastaran Taefi Aghdam 

## Building
1. **Python 3.x** - Download and install from [python.org](https://www.python.org/downloads/).
2. **Java Development Kit (JDK)** - Required for PySpark. Download and install from [oracle.com](https://www.oracle.com/java/technologies/javase-downloads.html).
3. **Apache Spark** - Download and install from [spark.apache.org](https://spark.apache.org/downloads.html).
4. **Jupyter Notebook** - Install via pip.
5. **Required Python Packages**: pyspark, matplotlib, pandas - Install via pip
6. **Run Each Project File**
 <!-- ## Distribution of Variables

### 1. Price 2
#### The price of a particular product is higher than the average price for the entire product category.
<img width="280" alt="price_2" src="https://github.com/KamandShayegan/bigdata-online-shopping/assets/77912859/7f4fcdde-cd6a-415a-bf84-0a76723dae40">

### 2. Location
#### Photo location on the page, the screen has been divided into six parts.
<img width="280" alt="location" src="https://github.com/KamandShayegan/bigdata-online-shopping/assets/77912859/851dd153-f5d3-4399-a63b-f766d073163e">

### 3. Page
#### Page number within the e-store website (from 1 to 5)
<img width="280" alt="page" src="https://github.com/KamandShayegan/bigdata-online-shopping/assets/77912859/f17c0a11-301d-4f84-b07e-35d2a1450bb6">

### 4. Distribution of orders by country
#### Most orders are from Poland, the Czech Republic, and Lithuania.
<img width="480" alt="distribution_of_orders_by_country" src="https://github.com/KamandShayegan/bigdata-online-shopping/assets/77912859/ca2d2d16-8395-44ce-b6e4-c4d6118e93fe">

### 5. Distribution of orders by price

<img width="480" alt="distribution_of_orders_by_price" src="https://github.com/KamandShayegan/bigdata-online-shopping/assets/77912859/0e2713de-8e4e-4f25-ada4-e0dc1d889a15">

### 6. Distribution of orders by color
<img width="480" alt="orders_by_color" src="https://github.com/KamandShayegan/bigdata-online-shopping/assets/77912859/1179f390-5de4-42cb-a5c0-a233952ea071">

### 7. Price over months
<img width="480" alt="price_over_months" src="https://github.com/KamandShayegan/bigdata-online-shopping/assets/77912859/e99c86dd-09ea-4a11-b0cf-e4534287caea">

## The relationship between the variables

### 1. Correlation
#### - Moreover, the most negative correlation belongs to “price” and “price 2”.
<img width="400" alt="correlation" src="https://github.com/KamandShayegan/bigdata-online-shopping/assets/77912859/96cf2cc6-23db-41c3-8ecb-7f976e8ea376">

### 2. Price distribution to product category
<img width="480" alt="price_dist_to_page_1" src="https://github.com/KamandShayegan/bigdata-online-shopping/assets/77912859/a7f9cf64-b3aa-4e1d-9940-a5a0e6dcaf29">


## Association Rules (Support, Confidence, and Lift)

### 1. Association rules for different products
#### - Customers who buy B10 are 4.85 times more likely also to buy B13, suggesting a bundling opportunity.
#### - Similarly, buying A3 significantly increases the likelihood of buying A2.
<img width="400" alt="association_rules" src="https://github.com/KamandShayegan/bigdata-online-shopping/assets/77912859/3e8dd3d1-78ed-465c-b7ae-7af3a509af3a">

## Predictive Analysis

### 1. The probability percentage of buying from a category in 4 specific price ranges
#### The price range (USD 18-82) was divided into four equal segments to calculate the proportion of each product category within those ranges.
<img width="480" alt="predictive" src="https://github.com/KamandShayegan/bigdata-online-shopping/assets/77912859/b401c6cd-2781-4169-8fd6-e964dc301983">

### 2. Model Evaluation and Results:
#### - Mean Absolute Error (MAE): 0.03974245497554473
#### - Mean Squared Error (MSE): 0.0064731610206736605
#### - R-squared (R2): 0.9999654853058938
#### - Accuracy: 0.89

<img width="480" alt="model_eval" src="https://github.com/KamandShayegan/bigdata-online-shopping/assets/77912859/6e3838d0-5f88-471d-af4e-16af2f7dc0bd">

## Clustering
Used **Elbow Method** to help with the number of clusters: 3

### 1. Order percentage in each cluster grouped by colour
<img width="480" alt="order_per_in_each_cluster_grouped_by_color" src="https://github.com/KamandShayegan/bigdata-online-shopping/assets/77912859/d13214f1-486d-4b22-ab8a-6d0f80c2dcb8">




### 2. Order percentage in each cluster grouped by main category
<img width="480" alt="order_perc_of_clusters_grouped_by_main_cat" src="https://github.com/KamandShayegan/bigdata-online-shopping/assets/77912859/19700e4d-df02-41a2-8d61-61132da286c7">
-->

## Final Note 
This dataset is licensed under the GNU General Public License (GPL) Version 3, which permits copying and distribution while preserving certain freedoms. However, it's important to note that the license prohibits modifications. 
