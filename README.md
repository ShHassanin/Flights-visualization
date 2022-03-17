# Flights-visualization
- build interactive dashboards with Tableau (explanatory visualization) and use them to discover and communicate insights from data.
Flights visualization.
## First visualization Dashboard:
    As usual, the weather is the most common reason for cancellations and delays of flights.
According to our cancellation dashboard (the link is cancellation reason | Tableau Public
), From the first visualization which includes at least 10 cancellations, TX (Texas) state had the 
most cancellation in the USA in 2015. And Chicago city of IL state had the most cancellation all 
over other cities in the USA. The weather caused 54% of the cancellation in the USA in 2015.
Southwest Airlines Co. had the most cancellation in the USA. So that takes us to the importance 
of weather forecasting, so these airlines and in these cities should care about weather 
forecasting.
#### design choices:
- **Bar chart** used for multi-classification of categorical data, and when that data 
includes **geographical** data (country, states, cities (as hierarchies)), so I merged a 
**map** to the dashboard, and I add the total cancellation to the marked size wherein 
the bigger size, the more number of flight cancellations. And to show the 
percentage and focus on the reason, I employed a **pie chart**. I employed a **colorblind** palette so everyone can see the difference. I added many **filters** (states, 
cities, airlines, and reasons) so that readers can dig which states, cities, airlines
have the highest and lowest cancellations and the most common reason and its 
percentage. I employed colors in the dashboard to Illustrates the reason for the 
cancellation.

## Second visualization:
    And as expected the most cancellation occurred in February and January as the 
visualization shows (the link: cancellation over months | Tableau Public ).
#### design choices:
- **Line chart** used for time series to show the cancellation over months as it is easier 
to perceive trend over time on line charts. I employed a color-blind palette so 
everyone can see the difference. I added the reason filter so that readers can detect 
which reason was raised over months. and the total of all reasons is the month’s 
trend.

## Third visualization:
    Third visualization shows the sum of cancellations over days of the week (the link: 
cancellation over days of week | Tableau Public ).
#### design choices:
- **bar chart** used for multi-classification of categorical data. I employed a color-blind 
palette so everyone can see the difference. I added the reason filter so that readers 
can detect which reason was raised mostly on each day of the week.

## Forth visualization:
    Delay of the flights might be multifactorial and the visualization shows that there is a 
correlation between arrival delay and air system delay, and between departure delay and both 
airline delay and late aircraft delay. (the link: delay reasons | Tableau Public ).
#### design choices:
- **scatter chart** used correlation between two numerical data, to show the correlation 
between arrival delay and air system delay, and between departure delay and both 
airline delay and late aircraft delay. I employed a color-blind palette so everyone can 
see the difference. I added the airline filter so that readers can dig in each airline
and its delay reasons. 
