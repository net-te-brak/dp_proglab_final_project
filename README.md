# Final project: Development
Final project for Data Processing 2022 <br>
Studentnr: 12146218 <br>
Date: 14-12-2022

## Usage
To access the interactive plot, download *at least* the project_main.ipynb and the data folder. In a terminal, go to the directory containing both assets and run the following command:<br> **bokeh serve --show project_main.ipynb**<br>
If you do not run the script via a Bokeh server, the interactive slider used for filtering years in the world map will not work.

## Research Questions
In this project, global life expectancy and fertility data is visualised to answer two questions. <br> How did life expectancy and fertility change between 1964 - 2013 for different countries and continents?<br>Which regions developed most in this time period?

Over this time period, the global life expectancy increased by exactly 17 years. Fertility fell with an average rate of 3.02 children per woman.<br>
South Asia has seen the biggest increase in life expectancy, going from 43.9 years in 1964 to 69.2 years in 2013 - a rise of 25.3 years. Fertility in this region has fallen with a rate of 3.75 children, but this was not the biggest decrease in fertility of all regions.

## Visualizing Life Expectancy and Fertility
Using the Bokeh library, the code creates an interactive plot showing two world maps displaying each country's fertility rate and life expectancy for every year between 1964 and 2013. The page also shows two graphs, averaging fertility rates and life expectancies on a regional - and global - level for the same time period.

### Resources:
[Bokeh library](https://docs.bokeh.org/en/latest/)<br>
[Country Converter library](https://github.com/konstantinstadler/country_converter)<br>
[Fertility and Life Expectancy data](https://raw.githubusercontent.com/spcourse/visualisation/main/development/gapminder.csv) from [Gapminder.org](https://www.gapminder.org/)<br>
[Geodata from Natural Earth Data](https://www.naturalearthdata.com/downloads/50m-cultural-vectors/50m-admin-0-countries-2/)
