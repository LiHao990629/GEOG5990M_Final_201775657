# **Is there an association between building age and price in Leeds?**

<br>

**1. The background/context of the project:**
This project is designed for the final assignment of GEOG5990M in University of Leeds. 
The name of the project is "Is there an association between building age and price in Leeds?"

<br>

**2. What data the GitHub repository contains:**
<p>LSOA_2011_Boundaries_Super_Generalised_Clipped_BSC_EW_V4_-6793269404754981576.geojson</p>
<p></p>Description: LSOA data of entire UK in 2011 with geometry information</p>
<p>Souce:https://geoportal.statistics.gov.uk/datasets/f23b8af6504640558a5100dfcd19a7ee_0/explore?location=52.619015%2C-2.489798%2C6.97</p>
<br>
<p>voapropertyage.csv</p>
<p>Description: Building Age Dataset</p>
<p>Source:https://data.cdrc.ac.uk/dataset/dwelling-ages-and-prices#data-and-resources</p>
<br>
<p>Median_Prices_Quarterly.csv</p>
<p></p>Description: Building Price Dataset</p>
<p>Souce:https://data.cdrc.ac.uk/dataset/dwelling-ages-and-prices#data-and-resources</p>

<br>

**3. What the code aims to do:**
<p>The aim of the code is to analyze wheather there is a relationship between building price and building age in Leeds.</p>
<p>In the code, we follow the general working flow of data science to prepare, clean, modelling, and visualize the data.</p>
<p>The first part of the code is data cleanning which removes the unwanted columns and calculates additional variables we need. 
  Besides, we remove outliers and check missing values and data types in this part.Last, we merge the three datasets to one.
</p>
<p>Then we applied k-fold cross validiation and multiple linear regression model to the datasets. 
  To check the fit of the model and if there is a relationship between the building price and the building ages, we calculate the 
  p-value, RMSE, and R-squared.
</p>
<p>Last, we produce one non-spatial plot and one spatial plot to show visualize the variable mode of building ages and building price.</p>
<br>

**4. Any further information someone might need to be able to run the code and reproduce the analysis:**
<p>The .ipynb is created in Google Colab, so you should also run it in Google Colab.</p>
<p>To reproduce the result, you do not need to change anything.</p>
<p></p>If you are interested in using your own data, you can modify the url of the dataset.</p>
