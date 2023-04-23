# AIR QUALITY INDEX PREDICTION

## PROBLEM STATEMENT

The Air Quality Index (AQI) is a widely-used measure of air pollution that provides information on the quality of air in a city on a daily basis.
The AQI calculation takes into account the levels of five major air pollutants, including ground-level ozone, particle pollution/particulate matter (PM2.5/pm 10), carbon monoxide, sulfur dioxide, and nitrogen dioxide. These pollutants can have different impacts on health, and their levels are measured to determine the overall AQI. 

🌡️ The AQI is divided into six levels of air quality, ranging from "good" to "hazardous". It's important to pay attention to the AQI in your area and take precautions if the air quality is poor to protect yourself and those around you from the harmful effects of air pollution.

👉 The AQI bucket categories are outlined below:

- 0 - Good (0-50) - This indicates minimal impact.
- 1 - Satisfactory (51-100) - This category can cause minor breathing difficulties in susceptible individuals.
- 2 - Moderately polluted (101-200) - This category can cause breathing difficulties in people with lung diseases, such as asthma, as well as discomfort for heart disease patients, children, and older adults.
- 3 - Poor (201-300) - This category can cause breathing difficulties in people who are exposed to it for prolonged periods, as well as discomfort for individuals with heart disease.
- 4 - Very Poor (301-400) - This category can cause respiratory illness in people who are exposed to it for prolonged periods.
- 5 - Severe (401-500) - This category can cause respiratory issues in otherwise healthy people, and may result in very severe health problems for those with lung or heart disease.
- 6 - Very Severe (500 and above) - This category is considered uninhabitable.

## OBJECTIVE 

To train a ML model on the dataset to predict the AQI index in the range 0 to 6, classifying AQI in the categories ranging from Good to Very Severe

## DATASET

The dataset contains 495512 entries in the training dataset with 15 features.

Columns: City, Datetime, PM2.5, PM10, NO, NO2, NOx, NH3, CO, SO2, O3, Benzene, Toluene, Xylene and AQI_Bucket

## APPROACH

An RNN and 1-D CNN model was used to predict the AQI bucket value


