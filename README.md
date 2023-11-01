# HELP International Funding Allocation Project
Introduction:
HELP International is an NGO aiming to fight poverty and provide basic amenities to backward countries. After raising $10 million through fundraising, the challenge was to strategically distribute the funds to the countries most in need.

# Problem Statement:
To categorize 167 countries based on socio-economic and health factors, determining which countries need the most focus for fund allocation.

# Dataset Features:
Name of the country
Child mortality rate (under 5 years of age per 1000 live births)
Exports of goods and services per capita
Total health spending per capita
Imports of goods and services per capita
Net income per person
Annual growth rate of the Total GDP
Expected lifespan of a new-born child
Expected number of children born to each woman
GDP per capita

# Solution:
# 1. Data Preprocessing:
Handled missing values and standardized the data for consistency.

# 2. Principal Component Analysis (PCA):
PCA was used to reduce the dimensionality of the dataset while retaining maximum variance.

# 3. Clustering Algorithms:
K-means Clustering: The countries were segmented into clusters based on socio-economic and health factors. The optimal number of clusters was determined using the Elbow Method.

Hierarchical Clustering: Dendrograms were used to visualize and further confirm the optimal number of clusters derived from K-means.

# 4. Cluster Analysis:
Each cluster was analyzed to understand its characteristics. Based on factors like GDPP, Child Mortality, Income, and Health, clusters were named as:

Cluster 0: Underdeveloped (1st Priority for Funding)
Cluster 1: Developing (2nd Priority for Funding)
Cluster 2: Developed (No need for Funding)
Results:
Recommended fund distribution focusing primarily on the 'Child mortality rate', as it's the most sensitive socio-economic factor.

Identified the top 5 countries with the highest child mortality rate to be prioritized for fund allocation.

Provided an objective and honest fund distribution percentage for the selected countries.

# Conclusion:
The analysis provided a strategic roadmap for HELP International to allocate their funds effectively, ensuring that the countries in dire need receive adequate assistance.
