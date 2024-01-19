import pandas as pd
import numpy as np
import matplotlib.pyplot as plt



data = pd.read_csv("C:\\Users\\Lenovo\\Downloads\\archive\\All_Countries_and_Economies.csv")
data.head(5)


selected_columns_2 = data[["GDP (current US$)", "GDP growth (annual %)"]].head(3)
print(selected_columns_2)


# Display 3 rows from the "Access to electricity (% of population)" and "Forest area (% of land area)" columns
selected_columns_4 = data[["Access to electricity (% of population)", "Forest area (% of land area)"]].head(3)
print(selected_columns_4)


# Display 5 rows from the "Individuals using the Internet (% of population)" and "Proportion of seats held by women in national parliaments (%)" columns
selected_columns_5 = data[["Individuals using the Internet (% of population)", "Proportion of seats held by women in national parliaments (%)"]].head(5)
print(selected_columns_5)

# Display 5 rows from the "Individuals using the Internet (% of population)" and "Proportion of seats held by women in national parliaments (%)" columns
selected_columns_5 = data[["Individuals using the Internet (% of population)", "Proportion of seats held by women in national parliaments (%)"]].head(5)
print(selected_columns_5)

