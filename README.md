## Weather Data Analysis using python

![9O6x3o](https://github.com/Nikitasuryawanshi/Weather-Monitoring-using-python/assets/105000370/5fa21b26-1244-4cc3-b52f-08138ae9d0b2)

### About Dataset:
It is time series data set with per_hour information about wether condtion at perticuler location.it records Temparature,Dew point temperture,relative humidity,wind speed,visibilty,pressure and condtions.

### Title: Weather Data Analysis Using Python ☁️🌡️

#### Description:
This project involves the analysis of a time series dataset containing hourly weather conditions at a specific location. The dataset includes various weather parameters such as temperature, dew point temperature, relative humidity, wind speed, visibility, pressure, and weather conditions.

#### Key Python Functions and Techniques Used:

#### nunique() & unique(): 
To find unique values in the dataset. 🔍

value_counts(): To count occurrences of unique values in a column. 📊

Filtering: To extract specific data based on conditions. 🎯

groupby() & get_group(): To group data and retrieve specific groups. 📂

isnull(): To identify and handle null values. 🚫

rename(): To rename columns in the dataframe. ✏️

mean(): To calculate the average of data. ➗

std(): To calculate the standard deviation of data. 📐

str.contains(): To filter string data. 🔎

And/Or operator: To combine multiple conditions. ⚙️

Commands Used:

head(): Displays the first N rows of the data (default is 5). 👀

shape: Provides the dimensions of the dataframe (rows, columns). 📏

index: Gives the index of the dataframe. 📚

columns: Lists all column names. 🏷️

dtypes: Shows the data types of each column. 🧩

unique(): Lists unique values in a column. 🗂️

nunique(): Counts the number of unique values in columns. 🔢

count(): Counts non-null values in columns. 📈

value_counts(): Counts occurrences of unique values in a column. 🧮

info(): Provides a summary of the dataframe. 📜

Questions Addressed:

Find all unique 'Wind Speed' values in the data. 💨

Count occurrences of 'Weather is exactly Clear'. ☀️

Count occurrences of 'Wind Speed was exactly 4 km/h'. 🌬️

Identify all Null Values in the data. 🚫

Rename the column 'Weather' to 'Weather Condition'. 📝

Calculate the mean 'Visibility'. 👓

Determine the Standard Deviation of 'Pressure'. ⚖️

Find the Variance of 'Relative Humidity'. 💧

Identify instances when 'Snow' was recorded. ❄️

Find instances when 'Wind Speed is above 24' and 'Visibility is 25'. 🌪️

Calculate the Mean value of each column against each 'Weather Condition'. 📊

Determine the Minimum & Maximum value of each column against each 'Weather Condition'. 📈📉

Display records where 'Weather Condition is Fog'. 🌫️

This project showcases how Python can be effectively used for weather data analysis, including data manipulation, statistical calculations, and answering specific weather-related queries.
