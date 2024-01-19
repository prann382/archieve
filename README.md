import pandas as pd
import numpy as np
import matplotlib.pyplot as plt



data = pd.read_csv("C:\\Users\\Lenovo\\Downloads\\archive\\All_Countries_and_Economies.csv")
data.head(5)

data = pd.read_csv(r"C:\Users\Lenovo\Downloads\archive\All_Countries_and_Economies.csv")

# Find the country with the highest GDP per capita
highest_gdp_per_capita_country = data.loc[data["GDP per capita (current US$)"].idxmax(), "Country"]

# Calculate the average HCI score
average_hci_score = data["Human Capital Index (HCI) (scale 0-1)"].mean()

# Find the country with the highest CO2 emissions per capita
highest_co2_emissions_country = data.loc[data["CO2 emissions (metric tons per capita)"].idxmax(), "Country"]

# Find the country with the lowest life expectancy
lowest_life_expectancy_country = data[data["Life expectancy at birth, total (years)"] == data["Life expectancy at birth, total (years)"].min()]

