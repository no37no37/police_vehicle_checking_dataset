# police_vehicle_checking_dataset

This project involves examining and drawing insights from a dataset obtained from a police check post. This dataset, available in CSV format, is loaded and analyzed using the powerful Pandas Data Frame in Python.

**Data Cleaning:**
The initial step includes cleaning the data, where the column containing only missing values, in this case, 'country_name,' is removed. This ensures that the analysis focuses on relevant and complete information.

**Filtering and Value Counts:**
The analysis begins by exploring the frequency of stops related to speeding and identifying whether men or women were stopped more often. The Pandas Data Frame is used to filter the data based on the 'violation' column, specifically 'Speeding,' and then obtaining value counts for 'driver_gender.' The results provide insights into the distribution of speeding stops among men and women.

**Groupby:**
The project further investigates whether gender influences the likelihood of a search during a stop. Utilizing the 'groupby' function on the 'driver_gender' column, the sum of searches conducted is calculated for both male and female drivers. This analysis sheds light on potential gender-related patterns in search occurrences.

**Mapping and Data-Type Casting:**
An essential aspect of the analysis involves determining the mean stop duration. The 'stop_duration' column, initially containing categorical values, is mapped to corresponding numerical values. Subsequently, the mean stop duration is calculated, providing a quantitative understanding of the average duration of stops.

**Groupby and Describe:**
A comprehensive comparison of age distributions for each type of violation is conducted using the 'groupby' function on the 'violation' column. The 'describe' function helps summarize the statistics for driver ages associated with different violations, offering insights into potential age-related patterns in violations.

