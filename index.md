# **Portfolio**

---

# **Predictive Analytics**
## **I. Identify performance issues in a wind farm and predict future power outputs**

<div align="center"><img src="images/icons8-wind-turbine-64.png?raw=true"/></div>

### **Introduction**
This project aims to:
1. detect performance issues in a given wind farm such as certain inverters require slight maintenance or become faulty that require replacement.
2. predict windfarm output in the short future for better grid management.

Data source: [kaggle](https://www.kaggle.com/anikannal/solar-power-generation-data)

### **Project Highlights**
#### Filter outliers from solar panel's inverter outputs:

In order to identify instances of sub-optimal performance of the inverters, a model that describes the 'optimal' performance needs to be constructed. And any actual output significantly deviates from the predicted value of this 'optimal' performance model would be deemed as problematic that requires further processing.

<div align="center">Data Before filtering</div>

<div align="center"><img src="images/Before_Filtering.JPG" width="700"/></div>

<div align="center">Data filtering process</div>

<div align="center"><img src="images/After_Filtering.JPG" width="700"/></div>

#### Predict future power outputs based on historical data:

In order to perdict future power outputs based on historical data, time-series analysis is required. But traditional univariate time-series models' perfromance is limited (more biased) as they rely only on time and the target variable itself to make predictions. In this project we assume that the current time T is only dependent on the past X time periods. Using data manipulation, a dataset is constructed as below.

<div align="center">Data manipulation</div>

<div align="center"><img src="images/IID_Manipulation.JPG" width="700"/></div>

After data manipulation, the time-series problem could be converted to an I.I.D (Independent and Identically Distributed) problem. Conventional ML model such as random forest could be used to make predictions.

<div align="center">Prediction</div>

<div align="center"><img src="images/IID_Prediction.JPG" width="700"/></div>


### **Project Delivery**

[Project presentaion](/pdf/WindFarm_Presentation.pdf)

[Project report](/pdf/WindFarm_Report.pdf)

---

# **Natural Language Processing**
## **I. Sentiment classification with US Airline twitts**

<div align="center"><img src="images/icons8-twitter-64.png?raw=true"/></div>

### **Introduction**
This project aims to classify positive and negative sentiments from a set of unlabeled twitts about major US airlines.

### **Project Delivery**
[Code](/Codes/R/US_Airline_Sentiment)

[Project report](/pdf/USAirline_Report.pdf)

## **II. Food trend identification from facebook posts**

<div align="center"><img src="images/icons8-facebook-100.png?raw=true"/></div>

### **Introduction**
This project aims to help identifying food related trends from 4 million food related facebook posts span across 4 years.

### **Project Delivery**
[Code](/Codes/R/Food_Trend_Facebook)

[Project report](/pdf/Cauliflower_Report.pdf)

---

# **Information System & Design**
## **Coming soon!**


---




---
<p style="font-size:11px">Page template forked from <a href="https://github.com/evanca/quick-portfolio">evanca</a></p>
<!-- Remove above link if you don't want to attibute -->
