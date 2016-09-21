# Preface
Some time ago I have implemented test task when I participated in the competition on vacancy of Tableau / BI-developer which was opened in the S7 Group company.

The head of reporting and BI department suggested me discover and visualize some data array using my favorite BI / data discovery tool. At that moment I had experince only in QlikView / Qlik Sense (of course I had experience in the Microsoft SSRS but this is not a data discovery tool). So I have implemented three dashboards in Qlik Sense. These dashboards were overview, quantitative and financial analysis. 

Now I have implemented the same dashboards in the Tableau. I needed to modify original data a little bit because currently I do not know how to join tables each others using calculated fields. I have modified departure and arrival airports fields and added codes of airports mapped with the original codes of the cities. For example, the Moscow has code MOW I mapped on Sheremetyevo International Airport
SVO. Let us consider these dashboards.

# Dashboards
## Overview
On this dashboard you can see three vizes Profit treemap, Statistics of passengers and Profit per arrivals. I use two brand colors of S7 company (green and red) for partition positive and negative values of the profit. I use these colors for all vizes. Treemap shows us distribution of profits by departures and by arrivals. The square of rectangle is equal profit. You can quickly and easy understand which flight direction give us more profit than other. Statistics of passengers shows us distribution of passengers by date. You can drill down through the date and see statistics more detailed. Using this viz you can analyze how much passengers flew for a chosen period. The last viz on this dashboard is a map. On this map we can see arrival airports and profit per passengers. Looking on the map you can immediately to check which airports / cities are profitable or non profitable. For each airports you can see profit per passenger in a tooltip. I think the map is a great viz for data analyzing.

## P&L
P&L means profit and loss statement. On this dashboard you can see pivot table and bar chart. Pivot table is the profit and loss statement. It contains income, revenue, loss and profit which are detailed by departure and arrivals airports and by date. You can see detailing or collapse data through these dimensions. Pivot table is an ideal for accurate analyzing of the financial measures. Using bar chart you can analyze and compare revenue and loss visually.

## PAX
PAX is an abbreviation for a word "passengers". On this dashboard you can see pivot table with statistics of passengers, bar charts which shows us distribution of passengers in a general and can help you make a comparison of passengers quantity of a business and an economy classes. You can analyze average and total measures as well as quantity of passengers a business and economy classes which presented in the table form or as the diagram.
