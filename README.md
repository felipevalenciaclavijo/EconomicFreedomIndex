# Index of Economic Freedom
Data Science project to compare countries, regions, and the world on 2022 Index of Economic Freedom

# Dataset Editing

The original 2022 dataset from [Heritage.org](https://www.heritage.org/index/download) does not include data about the World average, therefore, I manually added it with `ID` = _187_, but I keep many variable as N/A due to not knowing how to compute some or where to find them. However, I was able to compute and add the most relevant data for this project.

Here's an example of how the data is presented:

[2022 Index of Economic Freedom: Mexico vs World Average](2022_EFI_Mexico_vs_World.svg)

# Updates

+ I'm planning to turn this project into an interactive chart where the user can easily pick the observations to compare, I'm considering to do this on Streamlit.

+ I'm also planning on collecting all the historic data to see changes thorugh time

+ I'm planning to re-organize the dataset once I gathered all the past years' data, which will also include having to compute World and Regions averages and put them as observations for each year (be careful when computing those!).

## Required Technologies
---
* Python 3.8.0
* Quarto

## Authors

* Felipe Valencia fevacla@byui.edu