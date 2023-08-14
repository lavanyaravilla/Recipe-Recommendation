# Recipe-Recommendation
AWS_Pyspark Recipe Recommendation EDA 
**objective :**
  As an ML engineer working at food.com design a recommender system to recommend recipes to users based on their choice and the current     recipe they are looking at.
  Perform Exploratory Data Analysis and feature extraction from the raw data.
  
The recommendation engine is a way to increase the website's user engagement. If a user is shown relevant recipes, they are more likely to spend more time on your site reading about recipes. Higher user engagement will likely result in more business opportunities like collaborations, promotions, etc.

 
The performance of a recommendation engine will significantly impact the revenue your recipe site can generate.  
**Data used in this project are present under below link:**
# raw recipe data
s3a://raw-recipes-clean-upgrad/RAW_recipes_cleaned.csv

# raw ratings data
s3a://raw-interactions-upgrad/RAW_interactions_cleaned.csv

**Solution:** For this case study explore the structured data in spark environment under AWS platform using EMR  and create features that will be used to build the recommender. The steps involved are as mentioned below:

**Setting up Apache Spark instance:**
create key pair
Create cluster in EMR (1 master node with m4.xlarge ,1 cluster node with m4.large)
Connecting to Master Node via SSH using PuTTY and PuTTYGen
Launch jupiter notebook 
import pyspark Kernel
**Perform EDA**
  Data Loading 
  Data Exploration a.k.a Exploratory Data Analysis

  **Technologies**
  AWS 
    Spark on Elastic Map Reduce service (EMR)
    1 master node with m4.xlarge 
    1 cluster node with m4.large
    Jupyter notebook using Pyspark
    Python
    NumPy
    Pandas
 
