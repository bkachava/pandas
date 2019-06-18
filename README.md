# Python, Pandas, Jupyter Notebooks, Matplotlib and APIs Assignments

Apply the skills learned so far to some real-world situations.
 
 
## PyCitySchools

Pandas library and Jupyter Notebooks were used for helping a School Board and Mayor to make strategic decisions
regarding future school budgets and priorities, an analysis to the district-wide standardized test results was made. 
Also, data was aggregated to show [trends](PyCitySchools) in school performance.


The [final report](PyCitySchools/Scripts/PyCitySchools.ipynb) includes:

- District Summary. A high level snapshot (in table form) of the district's key metrics, including: Total Schools, 
Total Students, Total Budget, Average Math Score, Average Reading Score, % Passing Math, % Passing Reading, and
Overall Passing Rate.

- School Summary. An overview table that summarizes key metrics about each school, including: School Name, School Type
Total Students, Total School Budget, Per Student Budget, Average Math Score, Average Reading Score, % Passing Math, 
% Passing Reading, and Overall Passing Rate.

- Top Performing Schools (By Passing Rate). A table that highlights the top 5 performing schools based on Overall 
Passing Rate, including: School Name, School Type, Total Students, Total School Budget, Per Student Budget,
Average Math Score, Average Reading Score, % Passing Math, % Passing Reading, and Overall Passing Rate.

- Bottom Performing Schools (By Passing Rate). A table that highlights the bottom 5 performing schools based 
on Overall Passing Rate, including all of the same metrics as above.

- Math Scores by Grade. A table that lists the average Math Score for students of each grade level (9th, 10th,
11th, 12th) at each school.

- Reading Scores by Grade. A table that lists the average Reading Score for students of each grade level (9th,
10th, 11th, 12th) at each school.

- Scores by School Spending. A table that breaks down school performances based on average Spending Ranges 
(per Student), with 4 bins to group school spending, including: Average Math Score, Average Reading Score,
% Passing Math, % Passing Reading, and Overall Passing Rate.

- Scores by School Size. Same as above, but group schools are based on an approximation of school size 
(Small, Medium, Large).

- Scores by School Type. Same as above, but group schools are based on school type (Charter vs. District).


## Pymaceuticals

Python, Jupyter Notebooks, Pandas and Matplotlib libraries were used to analyze data from an animal study made by 
a company that specializes in drug-based, anti-cancer pharmaceuticals. In this study, 250 mice were treated
through a variety of drug regimes over the course of 45 days and their physiological responses were monitored.

The analysis, to show how four treatments (Capomulin, Infubinol, Ketapril, and Placebo) compare, includes:
 - A scatter plot that shows how the tumor volume changes over time for each treatment
 - A scatter plot that shows how the number of metastatic (cancer spreading) sites changes over time for
 each treatment
 - A scatter plot that shows the number of mice still alive through the course of treatment (Survival Rate)
 - A bar graph that compares the total % tumor volume change for each drug across the full 45 days. The 
 tumor growth is indicated as color red and the tumor reduction as color green

A written description of the observable trends based on the data can be found [here](Pymaceuticals).

Also, the scatter plots include error bars, allowing the company to account for variability between mice. 
See the [Jupyter Notebook](Pymaceuticals/pymaceuticals.ipynb).


## PyWeather

Jupyter Notebooks, Pandas and Matplotlib libraries, Python requests, APIs, and JSON traversals were used to 
answer a fundamental question: `What's the weather like as we approach the equator?`.

A script to visualize the weather of 500+ cities across the world, of varying distance from the equator 
was created, based on random coordinates, and a weather check on each of the cities, using successive calls 
to OpenWeatherMap API, was performed.

[Scatter plots](PyWeather/Output_data) were built to show the following relationships:
 - Temperature (F) vs. Latitude
 - Humidity (%) vs. Latitude
 - Cloudiness (%) vs. Latitude
 - Wind Speed (mph) vs. Latitude

See the observable [trends](PyWeather/WeatherPy.ipynb) and the resulting [csv](PyWeather/Output_data/cities.csv) 
of all data retrieved.
