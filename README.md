# eda-on-airbnb-data-analysis

## Data Preparation
  In this dataset, there are 48895 entries and 16 features (Columns )

  10 out of 16 are numeric: ['id', 'host_id', 'latitude', 'longitude', price, 'number_of_reviews' 'reviews_per_month', 'calculated_host_listings_count', 'availability_365' ]

  6 out of 16 are categorical: [ 'name', 'host_name', 'neighbourhood_group' 'neighbourhood','room_type','minimum_nights', 'last_review']
  
  ## Handling Null values:
Columns like reviews_per_month has 10052 missing value or can say that null values. It is very important feature for data analysis. On other hand columns like name, last review also has missing values but we can drop it from dataset

