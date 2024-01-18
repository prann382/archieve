import pandas as pd
import numpy as np
import matplotlib.pyplot as plt



data = pd.read_csv("C:\\Users\\Lenovo\\Downloads\\archive\\All_Countries_and_Economies.csv")
data.head(5)

highest_gdp_per_capita_country = df.loc[df["GDP per capita (current US$)"].idxmax(), "Country"]
highest_gdp_per_capita_country


average_hci_score = df["Human Capital Index (HCI) (scale 0-1)"].mean()
average_hci_score

highest_co2_emissions_country = df.loc[df["CO2 emissions (metric tons per capita)"].idxmax(), "Country"]
highest_co2_emissions_country

lowest_life_expectancy_country = df[df["Life expectancy at birth, total (years)"] == df["Life expectancy at birth, total (years)"].min()]
lowest_life_expectancy_country


