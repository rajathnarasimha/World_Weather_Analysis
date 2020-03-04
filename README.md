# World_Weather_Analysis

# Challenge Solution:

# How many cities have recorded rainfall or snow?
# Answer:
  # rain_cities = city_data_df.loc[(city_data_df["Rain inches(last 3hrs)"] > 0)]
  # snow_cities = city_data_df.loc[(city_data_df["Snow inches(last 3hrs)"] > 0)]
  # rain_or_snow_cities = city_data_df.loc[(city_data_df["Rain inches(last 3hrs)"] > 0) | (city_data_df["Snow inches(last 3hrs)"] > 0)]
  # rain_or_snow_cities.count() ----> 93
  # rain_cities.count() ---->69
  # snow_cities.count() ---->24
