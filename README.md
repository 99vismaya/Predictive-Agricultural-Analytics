# Predictive-Agricultural-Analytics

# Project goal and introduction

Project related to agriculture prediction. This app suggest best crop that can be grown in Medak district for selected month with the maximum ROI using different features needed for crop to yield maximum.
Data analytics create predictive analytics related to future yields, market price, yield, cost of cultivation and help farmers make resources management decision based on proven trends.
The complete project comes up with the idea to help farmers to start with zero farming knowledge and helps them to yields the maximum profit.


# About data

Data was collected from Telangana.gov.in and other different sources, certain inputs were collected from client. Data is combined and converted to excel. Data has 1800 rows and 27 columns.Target variable - Crop name. It is categorical.

# Model building

As output variable was categorical, classification models are trained. Decission tree, Random forest, Support Vector Machine(SVM), Naive Bayes are some models trained and SVM polynomial model with 94% accuracy is selected for model building.

# Deployment

Streamlit framework is used for app building.Cloud deployment is done in Streamlit cloud platfrom . Top 10 crop based on ROI is displayed when month for sowing is selected.Filters are added to filter the crops based on farmers need. A graph comparing ROI and cost of cultivation for crops for the month selected is shown. As we have one time sown and mutiple time harvesting crops like apple that is long term crop, farmers can grow combination of crop with main crop. Mixed crop combination for crops is displayed.

App Link:https://99vismaya-predictive-agricultural-analytics-app-ami7k5.streamlit.app/

# App 
Crop recomendation for selected month
![image](https://user-images.githubusercontent.com/106010576/211984736-f8e95091-dc92-45e6-ab1e-44cf24ea8088.png)


Adding filters
![image](https://user-images.githubusercontent.com/106010576/211984806-9f27fe00-63de-49c8-a85b-d404f43b89ea.png)


Plot of Crops VS Cost of Cultivation and Profit
![image](https://user-images.githubusercontent.com/106010576/211984838-ea5a5054-1b32-4dba-8472-5fd6089ffb4c.png)


Recomendation of Mixed Crop combinations
![image](https://user-images.githubusercontent.com/106010576/211984857-b7417d89-dfe8-4135-b506-ccf511d62016.png)

