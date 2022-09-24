# Airbnb Dataset

This **repository is the first in a series of three** in which various Airbnb datasets are studied using different analysis methods.

- [Part 1: Exploratory Data Analysis](https://github.com/ignareyesa/airbnb_eda)
- [Part 2: Natural Language Processing on reviews](https://github.com/ignareyesa/airbnb_nlp)
- [Part 3: Time Series Forecasting](https://github.com/ignareyesa/airbnb_ts)

![Airbnb](https://upload.wikimedia.org/wikipedia/commons/thumb/6/69/Airbnb_Logo_Bélo.svg/320px-Airbnb_Logo_Bélo.svg.png)

Airbnb is an American company that operates an online marketplace for lodging, primarily homestays for vacation rentals, and tourism activities. Based in San Francisco, California, the platform is accessible via website and mobile app. Airbnb does not own any of the listed properties; instead, it profits by receiving commission from each booking.

### Airbnb Data
The data used in this series is collected by [Inside Airbnb](http://insideairbnb.com), and the study is mainly focus in Madrid, Spain until February 2020 (pre-Covid19)

The dataset consists on the following files:
| File Name | Description |
| ------ | ------ |
| listings.csv.gz | Detailed Listings data. |
| calendar.csv.gz | Detailed Calendar Data. |
| reviews.csv.gz | Detailed Review Data. |
| listings.csv | Summary information and metrics for listings in Madrid. |
| reviews.csv | Summary Review data and Listing ID. |
| neighbourhoods.csv | Neighbourhood list for geo filter. Sourced from city or open source GIS files. |

## Part 1: Exploratory Data Analysis
This repository consists on two Jupyter Notebook. 

In the first one a study of the distribution of the advertisements is carried out, analysing their
- Location
- Price
- Availability
- Type of room
- More variables

to see the way in which supply and demand in Madrid works in such an important sector as the such an important sector as the hotel industry.

The analysis moves from a generic to a more specific view. Starting with the distribution of listings according to different neighbourhoods, types of rooms and looking at the hosts with the highest number of listings.

Then, we then studied differences in overall behaviour and top hosts, including neighbourhoods, price, cleaning, check-in, communication and others variables.

When analysing AirBnB data, two of the most important characteristics cannot be left out, such as occupancy/demand and revenue received. However, the way to analyse this may change, as AirBnB does not provide this data as such, but an algorithm capable of providing such information must be created. For this section we will make use of the listings and reviews files.

As mentioned above, there is no single way to calculate the occupancy of an accommodation. This is due to the "scarce" amount of data that AirBnB offers in this regard. The only variable available to calculate the occupancy of an accommodation is the number of reviews it receives, and from there create a calculation algorithm. However, different variables can have an influence, such as whether the accommodation is available every day of the year or only during certain seasons, or many other factors for which no information is available. Thus, websites specialised in the study of AirBnB such as InsideAirBnB or AirDNA and even AirBnB itself obtain different results.

This analysis will discuss the model presented in InsideAirBnB, known as the San Francisco model, because it was designed by the city's urban planning and public works team in order to quantify the impact of AirBnB on the city. In this way, the average annual occupancy of a flat can be obtained by means of different estimates, as well as the income that can be earned.

Additionaly, a more specific study is performed for the different variables that are considered important, such us, cancelation policy, type of host, acceptance rate, response time, capacity, etc.

Also, a distinction is made between a good and a bad host on the following these variables and a study is carried out with this distinction in mind.

So, please feel free to take your time to look deeper into the code and conclusions.

Ignacio Reyes Arboledas

**[Go back to website](https://ignacioreyesarboledas.tech/)** &#128522;
