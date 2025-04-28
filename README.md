# MIST-Group-7-Project-2

## Team Name:
71552 Group 7

## Team Members:
1. Leonard, Sean [@sleonard27] (https://github.com/sleonard27)
2. Sadiku, Agona [@as21860] (https://github.com/as21860)
3. Beaucejour, Ann [@acb77680] (https://github.com/acb77680)
4. Penso, Felipe [@FelipePenson] (https://github.com/FelipePenso)
5. Burke, Ward [@mikuism] (https://github.com/mikuism)

## Dataset:

The dataset used in this project is titled "MTA Daily Ridership", sourced from the Metropolitan Transportation Authority (MTA). It includes estimated average daily ridership data for various transit services across New York City from the years 2020 to 2025. Time Frame: 2020–2025, Daily ridership data, Breakdown by Service Type: Subways, Buses, Long Island Rail Road (LIRR), Metro-North Railroad, Staten Island Railway

Fields include (for every mode of transporation):

Total Estimated Ridership

% of Comparable Pre-COVID Ridership

Date (with weekday identification)

This dataset helps illustrate how public transit usage has evolved over time, particularly in response to major events like the COVID-19 pandemic, and offers insights into commuting patterns in one of the world’s busiest transit systems.



## Questions:

1. How has total ridership and usage of various modes of transit changed since the pandemic in 2020?

2. How do the average number of records for different modes of transportation vary throughout the week from Sunday to Saturday as well as their weekly totals?


## Manipulations:

1. Columns: Date in Years

   Rows: Measure Values (Sum of Ridership of Buses, Bridges & Tunnels, Subways, LIRR, Staten Island RR,

   Access-A-Ride, Metro-North Train)

   Filters: Date in Years (2020-2024)

   Color: Measure Names

   Detail: Measure Names

3. Columns: Weekdays

   Rows: Measure Values (Averages Ridership for Buses, Bridges & Tunnels, Access-A-Ride, Subways, LIRR,

   Staten Island RR, Metro-North Train)

   Color: Measure Names

   Label: Measure Names, Measure Values (Sum of Average Ridership per week)


## Results:

Graph 1

![Results1](https://github.com/sleonard27/MIST-Group-7-Project-2/blob/main/Picture1.0.png)



Graph 2

![Results2](https://github.com/sleonard27/MIST-Group-7-Project-2/blob/main/Picture2.png)

## Analysis:

Graph 1

Subway ridership has increased dramatically since the pandemic. Its increase is also significantly more than the other modes, showing that as fear of COVID has decreased, more people are willing to ride subways. There was more Bridge & Tunnel usage than Buses in 2020. This is likely due to that fact that more people chose individual cars over public buses during the pandemic to avoid health risk. In the following years, Buses overtook Bridges & and Tunnels meaning than more people no longer feared the risk of COVID. Long Island RR, and Metro-North RR ridership has steadily increased since COVID while the Staten Island RR has remained the same throughout the years. Overall, all modes of transit have increased in ridership since 2020. This makes sense because people have steadily become more and more comfortable with public transportation since the end of the pandemic.


Graph 2

Subways dominate ridership volume across all days, peaking midweek (around Wednesday/Thursday) with an average of 270,000 riders. Buses are the second most-used service, with peak usage also landing in the middle of the week, nearing 135,000 riders. LIRR and Metro-North follow similar curves, consistent usage patterns by commuters, while Staten Island Railway sees minimal traffic overall. There’s a noticeable dip during weekends (Days 1 & 7) across all systems, which suggests NYC has a heavily workweek-dependent transit flow. 


## Tableau Workbook:
