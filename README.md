import pandas as pd
import numpy as np
import matplotlib.pyplot as plt



data = pd.read_csv("C:\\Users\\Lenovo\\Downloads\\archive\\All_Countries_and_Economies.csv")
data.head(5)
# Find the country with the highest population
highest_population_country = data.loc[data["Population, total"].idxmax(), "Country"]
print("Country with Highest Population:", highest_population_country)

# Calculate the average life expectancy
average_life_expectancy = data["Life expectancy at birth, total (years)"].mean()
print("Average Life Expectancy:", average_life_expectancy)

# Find the country with the highest GDP per capita
highest_gdp_per_capita_country = data.loc[data["GDP per capita (current US$)"].idxmax(), "Country"]
print("Country with Highest GDP per Capita:", highest_gdp_per_capita_country)

# Calculate the average proportion of seats held by women in national parliaments
average_women_seats = data["Proportion of seats held by women in national parliaments (%)"].mean()
print("Average Proportion of Seats Held by Women:", average_women_seats)

# Find the country with the highest CO2 emissions per capita
highest_co2_emissions_country = data.loc[data["CO2 emissions (metric tons per capita)"].idxmax(), "Country"]
print("Country with Highest CO2 Emissions per Capita:", highest_co2_emissions_country)
