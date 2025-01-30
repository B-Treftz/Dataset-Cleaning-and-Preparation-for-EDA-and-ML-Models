<div style="text-align: center;">
<img title="a title" alt="Alt text" src="/Images/plane-marina-hinic.jpg">


<h1 style="text-align: center;">Cleaning and Preparing On-Time Flight Data for EDA and ML Models</h1>

<h3 style="text-align: center;">Notebook Link</h3>
<b>https://github.com/B-Treftz/Dataset-Cleaning-and-Preparation-for-EDA-and-ML-Models/blob/main/Notebooks/Data_Cleaning_and_Preparation.ipynb</b>

<h3 style="text-align: center;">Executive Summary</h3>

<p>In the world of data science, I believe the principle of 'Mise en place' to be of utmost importance, similar to its essential role in culinary practices. Much like organizing ingredients before cooking, meticulously preparing a dataset—verifying its completeness, addressing missing values, validating data types, and ensuring correct formatting—lays the groundwork for seamless analysis and interpretation.

Within this project, I focus on cleaning and preparing on-time performance data of commercial flights into a usable dataset. <b>The end result is a Pandas DataFrame conatining information about 6.7+ million flights from April 2023 to March 2024.</b> This dataset is a great for conducting exploratory data analysis (EDA) or serving as a dataset for designing machine learning models.

The raw data is sourced from an online database called “Airline On-Time Performance Data,” and can be found at the website for the Bureau of Transportation Statistics. According to the website, the database contains, “Monthly data reported by US certified air carriers that account for at least one percent of domestic scheduled passenger revenues--includes scheduled and actual arrival and departure times for flights.” This is the link to their aviation databases: https://www.transtats.bts.gov/databases.asp?Z1qr_VQ=E&Z1qr_Qr5p=N8vn6v10&f7owrp6_VQF=D </p>

<br>

<h3 style="text-align: center;">DF Transformation</h3>

           
|      | Rows       | Columns | DF Memory Usage|
|:-----------: | :--------: | :-----: | :--------------------: |
| Beginning    | 6,884,250  | 111     | 11.0 GB                |
| Ending       | 6,777,978  | 45      | 1.2+ GB                |



<br>

<h3 style="text-align: center;">Exported Dataset CSV</h3>

            
|   Compression   | Size       |
|:-----------: | :--------: | 
| Zipped    | 206.6 MB | 
| Unzipped  | 1.48 GB | 

