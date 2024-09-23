<p align="center"><a href="https://github.com/lily-pogodina/Data-Analyst-Portfolio-Ru/tree/main/Scooter_Rental_Service_ru"><b>Русская версия</b></a></p>


## A Study of Scooter Rental Service Users and their Trips
<p align="center"><a href="https://github.com/lily-pogodina/Data-Analyst-Portfolio-En/blob/main/Scooter_Rental_Service_en/Scooter_rental_service_users_and_their_trips_study_en.ipynb"><b>View project</b></a></p>

We have information on several GoFast mobile app users from several cities, as well as their trips.
In the study, we will study the main parameters, calculate the monthly revenue from each user, and test a number of hypotheses that can help the business grow.

**`Exploratory analysis`**

Main observations:
* **Frequency of occurrence of cities** — the most users are from Pyatigorsk, the least — from Moscow
* **Ratio of users with and without a subscription** — users without a subscription — 54%, with a subscription — 45.6%
* **Age of users** — from 12 to 43 years old, on average, the age of users is 25 years old.
* **Distance that a user has covered in one trip** — The distribution has two distinct peaks — about 600 and 3100 meters.
* **Ride duration** — the average ride duration is 18 minutes.
* **Features of users with and without an Ultra subscription** — on average, users with an Ultra subscription make longer and longer rides. But the difference is small, only 70 m and 1 minute. The total number of rides for users with a subscription is less.

**`Hypotheses testing and following conclusions`**

* Subscribed users probably spend more time on rides.
* It can be assumed that the average ride distance for users with an ultra subscription is 3,130 meters or more.
* Monthly revenue from users with subscriptions is higher than from users without a subscription.

**`Recommendations`**

* The study showed that users with a subscription are more profitable for the company. Therefore, it is worth developing strategies to increase the share of subscribers among users and attract new customers.
* It is worth paying attention to attracting new users over 33 years old.
* We need to clarify the proportion of users by city and make a stratified sample.
* It is necessary to investigate the presence of a second peak in the distribution of trip distances. Perhaps this is due to the type of trip (a walk or a trip to/from work) or other factors.
* The dependence of the number of trips on the month, sorted by city, needs to be studied. If it's impossible to ride in the city in winter, we can offer a seasonal subscription only for spring, summer or autumn.
* To better understand the business processes, we need to find out why users without a subscription have trips lasting half a minute. Is this a mistake or a promotion?

**`Tools`**

* Python
  * pandas
  * matplotlib 
  * seaborn
  * preprocessing
  * exploratory analysis
  * statistical analysis
  * visualization

<p align="center"><a href="https://github.com/lily-pogodina/Data-Analyst-Portfolio-En"><b>Table of contents.</b></a></p>
