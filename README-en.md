[![pt-br](https://img.shields.io/badge/language-pt--br-green.svg)](https://github.com/GustavoNascimento98/new-york-airbnb/blob/main/README.md)
[![en](https://img.shields.io/badge/language-en-red.svg)](https://github.com/GustavoNascimento98/new-york-airbnb/blob/main/README-en.md)

![](img/new-york-city.jpg)

# New York City Airbnb Data Analysis

This project develops a comprehensive Power BI report analyzing homestays in New York City, offering insights into pricing, popular neighborhoods, and growth performance metrics.

Acesse o [relatório](https://app.powerbi.com/view?r=eyJrIjoiOGZhNGM0ZDEtYzY5OC00YzA4LTkzM2MtNzRkOTFlM2FjZjQ2IiwidCI6ImRhNmQ0OWRhLTU1N2MtNDQxNy04YWVmLTg4ZTA1MDcxOTE0MyJ9):

[![](img/dashboard.gif)](https://app.powerbi.com/view?r=eyJrIjoiOGZhNGM0ZDEtYzY5OC00YzA4LTkzM2MtNzRkOTFlM2FjZjQ2IiwidCI6ImRhNmQ0OWRhLTU1N2MtNDQxNy04YWVmLTg4ZTA1MDcxOTE0MyJ9)

## Overview
This project aims to develop a comprehensive Power BI report on homestays in New York City. The report utilizes a dataset sourced from the [kaggle](https://www.kaggle.com/datasets/dgomonov/new-york-city-airbnb-open-data). The objective is to provide insights into the homestay market in NYC, including pricing trends, popular neighborhoods, and host performance metrics.

## Dataset Description:
Since 2008, guests and hosts have used Airbnb to expand on traveling possibilities and present more unique, personalized way of experiencing the world. This dataset describes the listing activity and metrics in NYC, NY for 2019.

This dataset includes all needed information to find out more about hosts, geographical availability, necessary metrics to make predictions and draw conclusions.

<details>
  <summary>Dataset</summary>
</br>

| Column Name         | Data Type |
| ------------------- | --------- |
| id                  | Integer   |
| name                | Text      |
| host_id             | Integer   |
| host_name           | Text      |
| neighbourhood_group | Text      |
| neighbourhood       | Text      |
| latitude            | Decimal   |
| longitude           | Decimal   |
| room_type           | Texto     |
| price               | Decimal   |
| minimum_nights      | Inteiro   |
| number_of_reviews   | Inteiro   |
| last_review         | Date      |

</details>


## Report Components
The Power BI report comprises several key components:

1. **Overview Dashboard:** Provides an overview of the homestay market in NYC, including total number of homestays, average price distribution, and distribution by borough.

2. **Price Analysis:** Analyzes pricing trends over time and compares average prices across different neighborhoods and districts.

3. **Neighborhood Insights:** Explores the popularity of neighborhoods based on the number of homestays available and their average prices.

4. **Performance Metrics:** Evaluates performance metrics such as average rating, number of listings, and response rate.

## Future Enhancements:
Potential enhancements for the Power BI report include:

1. Integration with real-time data sources for up-to-date insights.

2. Incorporation of predictive analytics to forecast pricing trends.