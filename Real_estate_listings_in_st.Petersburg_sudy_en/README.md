<p align="center"><a href="https://github.com/lily-pogodina/Data-Analyst-Portfolio-Ru/tree/main/Real_estate_listings_in_st.Petersburg_sudy_ru"><b>Русская версия</b></a></p>


## Real Estate Listings in St. Petersburg Study.
<p align="center"><a href="https://github.com/lily-pogodina/Data-Analyst-Portfolio-En/blob/main/Real_estate_listings_in_st.Petersburg_sudy_en/Real_estate_listings_in_st.Petersburg_sudy_en.ipynb"><b>View project</b></a></p>

We have data from the Yandex Real Estate service — an archive of apartment listings in St. Petersburg (Russia) and neighboring settlements for several years. For each apartment for sale, two types of data are available. The first is filled in by the user, the second is obtained automatically based on map data. For example, distance to the center, airport and other objects — this data is automatically obtained from geoservices. The number of parks and water bodies is also filled in without user participation.

**`Study Objective`**
* To conduct a research analysis of the data from the Yandex Real Estate service;
* To determine the market value of real estate objects in St. Petersburg and neighboring settlements based on the data obtained;
* To establish the parameters that affect the price of real estate objects;
* To provide recommendations for automating a system that will track anomalies and suspicious activity.

**`Main observations`**
* One-room apartments with an area of 42 and 46 square meters are most common.
* The standard ceiling height is 2.5 meters.
* Residential area of apartments usually makes up 17 or 18 square meters, but apartments with an area of 30 square meters also often occur.
* Kitchen areas on average make up 6, 8 or 10 square meters.
* Parks are usually located no more than 450 meters from houses. There is almost always a park within one kilometer.
* Distance to the city center is usually less than 17 kilometers, and the most common distance is 13 kilometers.
* Offers for sale are available on all floors, but the ground floor is slightly less common than the top floor.
* Five-story buildings are common.

**Real estate price** — The most common real estate cost is about 3.5 million. Most ads are in the price range from 0.43 to 10 million rubles, and the median value is 4.6 million rubles.

In our study, we found out the average price per square meter in 10 localities with the largest number of ads.

**Average time for selling an apartment:** — The average period for posting an apartment sale ad on the platform is 45 days. Sales with a period shorter than the median value of 94 days can be considered fast, which indicates that sales generally happen quickly. Offers with a duration of more than 20 months can be considered abnormally long publications.


**The market value of real estate objects depends on many factors. We found out that the following parameters most affect the price:**

* total area;
* living space;
* number of rooms;
* floor where the apartment is located;
* location;
* distance from the center.

**`Automation recommendations`**

* Analyze the algorithm for obtaining data in the «days_exposition» column. It is worth finding out why the values of 1 and 2 days disappear. You should also pay attention to the frequency of posting ads for a week, 30, 45, 60 and 90 days — perhaps this is related to publication settings.

* In the questionnaire, it is necessary to make fields that are filled in manually mandatory (for example, in the «is_apartment» field, you can automatically choose from two values: «Yes» or «No»). It is also worth automatically filling in the field with the name of the location and adding automatic verification of the format of the data entered by the user.

* Clarify information about the area, which is located at a distance of 27 km from the city center, to understand the reason for the high average cost of housing in this area.

**`Tools`**

* Python
  * pandas
  * matplotlib 
  * seaborn


<p align="center"><a href="https://github.com/lily-pogodina/Data-Analyst-Portfolio-En"><b>Table of contents.</b></a></p>
