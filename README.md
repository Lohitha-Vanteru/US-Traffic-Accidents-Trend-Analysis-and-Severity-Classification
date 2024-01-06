#  US-Traffic-Accidents-Trend-Analysis-and-Severity-Classification

## Introduction

Roads are shared by various means of transportation such as cars, trucks, buses, motorcycles, pedestrians, and animals, and they play a significant role in the economic and social growth of many nations. However, every year, a large number of vehicles are involved in collisions that result in numerous fatalities and injuries. This project aims to address this issue by examining the primary factors that contribute to the increase in the rate of car accidents and developing a predictive model that accurately identifies accident-prone areas to help reduce the frequency and severity of accidents in the USA.

## Dataset Description

In recent decades, accident analysis has been the subject of considerable research due to the prevalence of road accidents. To assist the research community in overcoming limitations in existing datasets, Moosavi et al. (2019) developed a publicly accessible database of accident information called US-Accidents. This large-scale database includes information on 2.8 million traffic accidents that occurred in the contiguous United States between February 2016 and March 2023. The dataset covers various attributes such as location, time, weather, natural language description, points of interest, and more.

**Dataset Source**: [US-Accidents Dataset](https://www.kaggle.com/datasets/sobhanmoosavi/us-accidents)

![image](https://github.com/Lohitha-Vanteru/US-Traffic-Accidents-Trend-Analysis-and-Severity-Classification/assets/113141006/81e5600a-a97d-4f5c-a5a0-092f8d4db63f)


## Goals of the Project

- Analyze historical accident data to identify patterns and trends in accident occurrence, contributing factors, and potential solutions.
- Develop a predictive model to accurately identify accident-prone areas and reduce the frequency and severity of accidents in the USA.
- Identify significant predictors of accidents, including road conditions, vehicle types, and weather patterns.
- Explore the use of advanced technologies, such as machine learning and artificial intelligence, to improve the accuracy of accident prediction models.
- Develop recommendations for policymakers, transportation agencies, and stakeholders to prevent accidents and reduce their impact on public safety.

## Models Used

The following machine learning models were used in this project:

1. **Apriori Algorithm:**
   - Utilized for providing recommendations based on association rules.

2. **Decision Tree Classifier with SMOTE:**
   - Used for addressing class imbalance and predicting accident severity.

3. **BERT Model:**
   - Employed for predicting the consequences of car accidents on road traffic, with a particular emphasis on identifying the main factors that contribute to road accidents.

## Results

The models were trained and evaluated using the US-Accidents dataset. Here are some key results:

1. **Decision Tree Classifier with SMOTE:**
   - Despite balanced classes done with SMOTE, the model achieved a moderate accuracy of 71%.

2. **BERT Model:**
   - Showed promising results with a higher accuracy of 85% in classifying the severity of accidents.
   - Particularly excelled in identifying fatal accidents (severity 4) with a perfect F1 score.

The findings from this study can potentially inform the development of strategies and interventions aimed at reducing the frequency and severity of car accidents in urban areas.

## Insights from Data Analysis

### Geographical Distribution
![image](https://github.com/Lohitha-Vanteru/US-Traffic-Accidents-Trend-Analysis-and-Severity-Classification/assets/113141006/b940d713-71b3-42ec-909c-4be920764929)

1. **Highest Number of Road Accidents by State:**
   - Prior to standardization, the data reveals that California had the highest number of road accidents, followed by Florida and Texas.

2. **City-wise Analysis:**
   - Miami emerges as the city with the highest number of road accidents across all states in the US.
   - Three out of the top 10 cities with the highest number of accidents are located in California.

3. **Standardized Analysis:**
   - After standardizing the data by state population, the analysis shows that Oregon has the highest number of road accidents per 10,000 residents.

### Severity of Accidents
![image](https://github.com/Lohitha-Vanteru/US-Traffic-Accidents-Trend-Analysis-and-Severity-Classification/assets/113141006/28e6541b-b030-47b3-8798-fd9555419431)

1. **Impact on Traffic:**
   - In a large majority of road accident cases, accounting for 89% of all incidents, the impact on traffic was considered moderate (Severity-2).
   - This suggests that, while accidents may still cause significant disruption to traffic flow and safety, most incidents do not result in major, long-lasting impacts.

2. **Highly Severe Impact:**
   - However, a small but significant percentage of accidents, approximately 4.6%, had a highly severe impact on traffic (Severity-4).
   - These incidents are likely to have caused significant disruption and potentially resulted in serious injuries or fatalities.

### Temporal Trends

1. **Increase in Accidents Over Time:**
   - The data indicates a clear and significant increase in the percentage of road accidents over the last six years in the United States, from 2016 to 2021.

2. **Concentration in Recent Years:**
   - Concerningly, 75% of the total road accidents recorded over the last six years occurred during the most recent two years, 2020 and 2021.

### Monthly and Seasonal Patterns
![image](https://github.com/Lohitha-Vanteru/US-Traffic-Accidents-Trend-Analysis-and-Severity-Classification/assets/113141006/1642b9af-42b3-4bef-9883-f9c699da51ea)

1. **Accidents by Month:**
   - A significant percentage, around 16.7%, of road accidents in the US occurred during the month of December.
   - On the other hand, the months of July and March are associated with the least number of road accidents.

2. **Seasonal Analysis:**
   - Approximately 40% of all road accidents occurred within the three-month period from October to December, representing the transition period from autumn to winter.

### Weekly and Daily Patterns

1. **Weekday vs. Weekend Analysis:**
   - Weekdays have approximately twice the number of road accidents compared to weekends.
   - Fridays have the highest percentage of road accidents among weekdays, while Sundays have the lowest.

2. **Time of Day Analysis:**
   - Around 30% of road accidents occur in the evening, specifically between 3:00 PM and 6:00 PM.
   - The deadliest hour for accidents is 5:00 PM.

### Weather and Environmental Factors
![image](https://github.com/Lohitha-Vanteru/US-Traffic-Accidents-Trend-Analysis-and-Severity-Classification/assets/113141006/5d818866-d8bc-4566-a4f6-ff1d90ab0dea)

1. **Weather Conditions:**
   - The most frequent weather condition during road accidents was fair weather (39.9%).
   - Overcast weather with a certain amount of clouds was present in 41% of cases.

2. **Temperature, Humidity, and Wind Speed:**
   - The majority of road accidents, 55%, occurred within the temperature range of 61(F) to 91(F).
   - Humidity range between 81% and 91% accounted for the maximum number of road accidents (16.8%).
   - Almost all road accidents experienced wind speeds of less than 100 mph.

3. **Visibility and Air Pressure:**
   - Visibility range between 0(mi) to 15(mi) accounted for the maximum number of road accidents (99.97%).
   - Air pressure range between 30(in) to 35(in) accounted for 70% of road accidents.

## Community Contribution

This project aims to raise awareness and promote data-driven approaches to road safety. By sharing findings with the community, the project contributes to improved road signage, increased law enforcement presence in high-risk areas, public education campaigns, and open-sourcing the developed model for real-time accident alerts and risk assessment.

## Conclusion

The findings from this project can inform the development of strategies and interventions aimed at reducing the frequency and severity of car accidents in urban areas. Potential initiatives include encouraging the adoption of autonomous vehicles, improving public transportation infrastructure, and implementing measures to spread out peak traffic times.

## Acknowledgements

If you use this dataset, please kindly cite the following papers:

- Moosavi, Sobhan, Mohammad Hossein Samavatian, Srinivasan Parthasarathy, and Rajiv Ramnath. “A Countrywide Traffic Accident Dataset”, 2019.
- Moosavi, Sobhan, Mohammad Hossein Samavatian, Srinivasan Parthasarathy, Radu Teodorescu, and Rajiv Ramnath. "Accident Risk Prediction based on Heterogeneous Sparse Data: New Dataset and Insights." In proceedings of the 27th ACM SIGSPATIAL International Conference on Advances in Geographic Information Systems, ACM, 2019.

## License

This project is licensed under the [MIT License](LICENSE).

