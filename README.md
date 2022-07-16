# Predictive-Agricultural-Analytics

# Project goal and introduction

Project related to agriculture prediction. This app suggest best crop that can be grown in Medak district for selected month with the maximum ROI.
Data analytics create predictive analytics related to future yields, market price, yield, cost of cultivation and help farmers make resources management decision based on proven trends.
The complete project comes up with the idea to help farmers to start with zero farming knowledge and helps them to yields the maximum profit.


# About data

Data was collected from Telangana.gov.in and other different sources, certain inputs were collected from client. Data was combined and converted to excel. Data has 1800 rows and 27 columns.

# Model building

As output variable was categorical, classification models were trained and SVM polynomial model with 94% accuracy was selected for model building

# Deployment

Streamlit framework was used for app building. Top 10 crop based on ROI is displayed when month for sowing is selected.Filters are added to filter the crops based on farmers need. A graph comparing ROI and cost of cultivation for crops displayed for the month selected is shown. As we have one time sown and mutiple time harvesting crops like apple that is long term crop, farmers can grow combination of crop with main crop. Mixed crop combination for crops that can be grown in given month is displayed.

App Link:https://kisan01.herokuapp.com/
