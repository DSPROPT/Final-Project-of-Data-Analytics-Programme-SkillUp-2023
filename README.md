# Final Project of Data Analytics Programme | SkillUp | 2023

This Jupyter notebook is a project focused on analyzing Airbnb data. Here's an overview of the initial sections:

**Introduction:** The notebook begins with personal information about me, Julio Cesar Gouveia Cordero, from Funchal, Portugal. 

**Project Overview:** The project is titled "Capstone Project Creation" and is part of the IBM SkillsBuild Europe Delivery - Data Analytics program. The pre-requisites listed include an understanding of Python, Power BI or Tableau, data cleaning, and data visualization. The exercise level is intermediate, and the estimated duration is around 3 hours.

### Data Analytics of Airbnb Data:

**Objective:** The exercise involves performing data analytics on an open dataset from Airbnb. Key tasks include data cleaning, data transformation, and data visualization.
Overview of Airbnb Data: The dataset provides information on Airbnb accommodations, including neighborhood details, room types, pricing, availability, reviews, service fees, cancellation policies, and house rules. The analysis aims to help Airbnb improve its services.
Dataset Source: The data can be accessed from a specified Kaggle link.
**Task 1: Data Loading (Python):**

The task involves reading a CSV file into a pandas DataFrame and then displaying the first five rows and the data types of the columns.
I will now delve deeper into the notebook to extract key findings and conclusions from the analysis.​​

The analysis of the Airbnb dataset in your Jupyter notebook has yielded several important findings and conclusions:

Exclusion of Certain Columns for Data Analytics:

The notebook explains why certain columns like 'host id', 'id', 'country', and 'country code' were excluded from the analysis. These columns were deemed redundant or not directly relevant to the analytical insights being sought.
Exploratory Data Analysis (EDA) Results:

Room Types: The dataset contains 52,003 listings for entire homes/apartments, 44,895 for private rooms, 2,150 for shared rooms, and 115 hotel rooms. The 'Entire home/apt' category has the most strict cancellation policy.
Average Price per Neighborhood Group: The analysis revealed the average rental prices across different neighborhoods, with Queens being the most expensive based on average price.
Impact of Review Rate and Host Identity Verification on Price:

Review Rate Number: The analysis shows that the review rate number doesn't significantly affect listing prices. There's consistency in median prices across all review rate numbers, and no clear distinction in price based on the review rate number.
Host Identity Verified: Listings with 'unconfirmed' and 'verified' hosts have higher median prices than those categorized as 'unknown'. Verified listings exhibit a wider range of prices, indicating more variability and potentially more premium options.
Conclusions:

The review rate number is not a strong predictor of price in the Airbnb listings.
Verified listings might offer more premium options, which could explain the higher variability in prices.
Listings where the host's identity status is 'unknown' tend to have lower median prices, suggesting guests might be paying less for these listings.
These insights provide a comprehensive understanding of the Airbnb market, highlighting factors like room type, neighborhood, review rates, and host verification status in determining rental prices and policies.​
