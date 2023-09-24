# Background

Congratulations on your new job! As the new lead analyst for the New York Citi. program, you are now responsible for overseeing the largest bike-sharing program in the United States. In your new role, you will be expected to generate regular reports for city officials looking to publicize and improve the city program.

Since 2013, the Citi Bike program has implemented a robust infrastructure for collecting data on the program's utilization. Each month, bike data is collected, organized, and made public on the Citi Bike (https://citibikenyc.com/system-data). webpage.

However, while the data has been regularly updated, the team has yet to implement a dashboard or sophisticated reporting process. City officials have questions about the program, so your first task on the job is to build a set of data reports to provide the answers


Instructions

Your task in this assignment is to aggregate the data found in the Citi Bike Trip History Logs and find two unexpected phenomena.

1. Design 2–5 visualizations for each discovered phenomenon (4–10 total). You may work with a timespan of your choosing. 
   Optionally, you can also merge multiple datasets from different periods.

2. Use your visualizations (not necessarily all of them) to design a dashboard for each phenomenon. The dashboards should be accompanied by an analysis explaining why the phenomenon may be occurring.

3.Create one of the following visualizations for city officials:
- Basic: A static map that plots all bike stations with a visual indication of the most popular locations to start and end a journey, with zip code data overlaid on top.

- Advanced: A dynamic map that shows how each station's popularity changes over time (by month and year). Again, with zip code data overlaid on the map.

- The map you choose should also be accompanied by a write-up describing any trends that were noticed during your analysis.

4. Create your final presentation:

- Create a Tableau story that brings together the visualizations, requested maps, and dashboards.

- Ensure your presentation is professional, logical, and visually appealing.


Data Source 

1. Initially I started with 3 years worth of data in my analysis. I selected years 2018, 2019, and 2020. I decided on these years to see if what impact the COVID-19 pandemic had on bike usage. I retrieved my data from the Citi Bike (https://citibikenyc.com/system-data). webpage. Here they house data starting from 2013 to present day. After downloading the data, I housed it locally in a folder named 'Resources'

2.  Once the data was downloaded the data I created a jupyter notebook titled "citibike.ipynb" where I began the data cleaning process. 

3. 
<img width="1411" alt="Screenshot 2023-09-21 at 12 19 33 PM" src="https://github.com/alexxisrangel/tableau_challenge/assets/129305054/b3e53d17-58fa-4396-a7e3-08f5dbfddbd6">

<img width="1395" alt="Screenshot 2023-09-21 at 12 19 45 PM" src="https://github.com/alexxisrangel/tableau_challenge/assets/129305054/1772268b-bd24-4e7c-90ff-2d4f0bcae62f">

<img width="1380" alt="Screenshot 2023-09-21 at 12 20 01 PM" src="https://github.com/alexxisrangel/tableau_challenge/assets/129305054/a9df4437-1cc8-46e9-be5e-6ea46c02c41b">

<img width="1369" alt="Screenshot 2023-09-21 at 12 20 13 PM" src="https://github.com/alexxisrangel/tableau_challenge/assets/129305054/751fce77-c2d1-4e7b-9401-875c4fc14215">

<img width="1308" alt="Screenshot 2023-09-21 at 12 21 41 PM" src="https://github.com/alexxisrangel/tableau_challenge/assets/129305054/60d97340-944f-4cd5-9353-79b916f821eb">




Dashboard 

In this dashboard we get an overview of our users. We can identify what demographic makes the vast majority of our consumer. 
<img width="1184" alt="Screenshot 2023-09-21 at 12 26 09 PM" src="https://github.com/alexxisrangel/tableau_challenge/assets/129305054/2d6c3f42-dc2e-4707-af09-f76a631d50b7">

User Analysis

![Screenshot 2023-09-21 at 12 39 14 PM](https://github.com/alexxisrangel/tableau_challenge/assets/129305054/b3fa1628-f8db-49f7-9212-15da44fe17e7)

Subscribers made up the vast majority of our users for the years 2018 and 2019. There were a total of 2,044,900 non-subscribers and 10,434,696 subscribers. 

If we breakdown users by gender we have Males at a majority with 8,204,884 and female users at 3,072,833

Between the years 2018 and 2019 we had a total of 12,479,488 riders 


What days are the most popular? 
![Screenshot 2023-09-21 at 12 44 16 PM](https://github.com/alexxisrangel/tableau_challenge/assets/129305054/3e827996-ed0a-4d95-af5d-e223d028d74e)

From the heatmap we can see that Tuesdays at 8am and 5pm are the days with more usage. This coincides with typical commute times. The periods with least usage would be the weekdays between the hours of 10am and 3pm. 


Year over year comparison 
![Screenshot 2023-09-21 at 12 47 22 PM](https://github.com/alexxisrangel/tableau_challenge/assets/129305054/213cbd71-8af7-440c-8e59-1af34e4cb747)

If we compare 2018 with 2019 its clear that 2019 has over 4 million rides, despite the COVID-19 Pandemic 


User Distribution Comparison 
![Screenshot 2023-09-21 at 12 49 06 PM](https://github.com/alexxisrangel/tableau_challenge/assets/129305054/08fc89ad-fe01-4cae-891b-9ed2566a26cc)

From this graph we can identify Males aged 33 as the top users (362,000) 


Geographical Analysis 

![Screenshot 2023-09-21 at 12 55 35 PM](https://github.com/alexxisrangel/tableau_challenge/assets/129305054/3f2c2168-c5ca-4dca-b7e4-51d64e22e378)

This dashboard displays our stations on a map so we can easily identify the most popular zipcodes 
![Screenshot 2023-09-21 at 1 03 39 PM](https://github.com/alexxisrangel/tableau_challenge/assets/129305054/3d6d95ae-c989-463e-8c14-adf0c35cf7d6)

Station 519 in area code 10178 is the most popular start and end destination. It makes sense since it's right next to 
Grand Central Station which is a popular destination for locals and tourist. 





