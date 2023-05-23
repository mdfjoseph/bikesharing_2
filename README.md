# Module 15 bikesharing Challenge

## Project Overview
In order to convince investors that a bike-sharing program in Des Moines is a solid business proposal one of the key stakeholders would like to see a bike trip analysis.

For this analysis, we use Pandas to change the "tripduration" column from an integer to a datetime datatype. Then, using the converted datatype, we have to create a set of visualizations to:
1.  Show the length of time that bikes are checked out for all riders and genders
2.  Show the number of bike trips for all riders and genders for each hour of each day of the week
3.  Show the number of bike trips for each type of user and gender for each day of the week.

## Deliverable 1:  Change Trip Duration to a Datetime Format
Using Python and Pandas functions, convert the "tripduration" column from an integer to a datetime datatype to get the time in hours, minutes, and seconds (00:00:00).
After the "tripduration" column is converted to a datetime dataytpe, export the DataFrame as a CSV file to use for the trip analysis.

#### Please find below screen shots of my Jupyter Notebook to accomplish this Deliverable:

![Screenshot 2023-05-23 at 2 20 43 PM](https://github.com/mdfjoseph/bikesharing_2/assets/114943747/62f77c1a-55db-4f68-b800-d5ecdfb3258a)

![Screenshot 2023-05-23 at 2 20 57 PM](https://github.com/mdfjoseph/bikesharing_2/assets/114943747/34b07832-3410-4934-855f-aab524379772)

![Screenshot 2023-05-23 at 2 21 07 PM](https://github.com/mdfjoseph/bikesharing_2/assets/114943747/38260764-4ed1-483e-8caf-effea375aff2)

![Screenshot 2023-05-23 at 2 21 18 PM](https://github.com/mdfjoseph/bikesharing_2/assets/114943747/0ef3d747-6087-4bf1-b3ab-8107c4841aa1)

## Deliverable 2: Create Visualizations for the Trip Analysis
Using Tableau, create visualizations that show:
1.  How long bikes are checked out for all riders and genders.
2.  How many trips are taken by the hour for each day of the week, for all riders and genders.
3.  A breakdown of what days of the week a user might be more likely to check out a bike, by type of user and gender.

#### Graph the length of time that bikes are checked out for all riders

<img width="1560" alt="Screenshot 2023-05-23 at 2 35 36 PM" src="https://github.com/mdfjoseph/bikesharing_2/assets/114943747/f84f9dcb-10ea-4c6e-bedc-69d3963aac7e">

#### Graph the length of time that bikes are checked out for each gender

<img width="1569" alt="Screenshot 2023-05-23 at 2 35 52 PM" src="https://github.com/mdfjoseph/bikesharing_2/assets/114943747/5df85bac-2a2a-4472-9d3b-78f2f87766e1">

#### Graph the number of bike trips by weekday for each hour of the day as a heatmap

<img width="1567" alt="Screenshot 2023-05-23 at 2 36 06 PM" src="https://github.com/mdfjoseph/bikesharing_2/assets/114943747/3c2d94be-fd13-4348-8d2e-8e8f25025d93">

#### Graph the number of bike trips by gender for each hour of each day of the week as a heatmap

<img width="1568" alt="Screenshot 2023-05-23 at 2 36 18 PM" src="https://github.com/mdfjoseph/bikesharing_2/assets/114943747/716a4545-8914-4695-a624-15c2e9a543e9">

#### Create a heatmap that shows the number of bike trips broken down by gender for each day of the week by each Usertype

<img width="1565" alt="Screenshot 2023-05-23 at 2 36 28 PM" src="https://github.com/mdfjoseph/bikesharing_2/assets/114943747/6cde8114-124b-4019-be4c-c5fe35e688dc">

## Deliverable 3: Create a Story and Report for the Final Presentation

### Tableau Story: NYC Bike Trip Analysis

### Purpose of Analysis
The purpose of this analysis is to provide investors with statistics and visuals that will convince them to invest in a bike-sharing program in Des Moines.  The data for the analysis is from New York City and is based off of statistics for the entire month of August 2019.

#### The following information is presented in the story analysis:
1. Total Number of Bike Trips
2. Peak Hours:  Includes top riding peak hours as well as off-peak hours

![Screenshot 2023-05-23 at 2 54 39 PM](https://github.com/mdfjoseph/bikesharing_2/assets/114943747/202f2833-77e6-4919-8959-be546b24f2ff)

3.  NYC Bike Customers Breakdown:  Provides details on Usertypes (Annual Subscribers vs Short-Term Customers) and the total number of riders for the month by 
Gender.

![Screenshot 2023-05-23 at 2 58 53 PM](https://github.com/mdfjoseph/bikesharing_2/assets/114943747/e17c43f3-b3c7-4996-b5c1-4360ae24e714)

4.  Checkout Analysis:  Shows the peak and off-peak hours that Users checkout bikes and gives a breakdown of by gender type.

![Screenshot 2023-05-23 at 3 01 27 PM](https://github.com/mdfjoseph/bikesharing_2/assets/114943747/71f80444-c194-44d6-9ed2-7b2421535648)

5.  Weekday Trips by Hour:  Provides details on the specific hours of the day, during the week, that bike riders start and end their bike rides.

![Screenshot 2023-05-23 at 3 03 58 PM](https://github.com/mdfjoseph/bikesharing_2/assets/114943747/436e0a38-479f-447f-ad67-e9f31ab26916)

6.  Weekday Trips by User and Gender:  Provides a breakdown on the days of the week bike riders ride.  It also specifically shows which days of the week the riders
ride by gender.

![Screenshot 2023-05-23 at 3 07 05 PM](https://github.com/mdfjoseph/bikesharing_2/assets/114943747/d6426767-5847-48e7-9a8d-e897da4db291)

### Summary
1.  There is a very high percentage of riders that will pay annually to subscribe to a bike-sharing service.
2.  Even though the numbers were not as high, the percentage and total number of short-term customers were also good.  
3.  Overall, out of the number of total riders, Males make up 65.28%, Females - 25.10% and Unknown Genders - 9.62%.
4.  Therefore, in regards to a marketing plan and/or stategy the target audience would be Men.
5.  The checkout times and weekday trip analysis give great insight on the volume of customers to expect at any given time of the day.  And, if you have hired 
staff/help, business (opening and closing) hours can be determined.

Overall, more research needs to be down in the city of Des Moines to determine if a bike-sharing service will be profitable because in New York City, there is alot
of congestion (people, cars, etc...) and riding a bike is a convenient mode of transporation that keeps people from having to get stuck in traffic. 

## Link to my Tableau Story
https://public.tableau.com/app/profile/marcia5121/viz/Module15ChallengeStory/NYCBikeTripAnalysis



