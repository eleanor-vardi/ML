# ML

## Overview
The objective of this project is to predict whether a restaurant will succeed based on a dataset obtained from TripAdvisor.
For the purpose of this analysis, a restaurant is considered successful if it receives more than 100 votes with an average score higher than 4.
This prediction can assist in understanding the factors that contribute to the success of restaurants and can be leveraged by restaurant owners or stakeholders to improve their services or strategies.

## Dataset

The dataset is taken from https://www.kaggle.com/datasets/thedevastator/berlin-airbnb-ratings-how-hosts-measure-up

The original dataset contains one table.
'restaurant_link', 'restaurant_name', 'original_location', 'country',
'region', 'province', 'city', 'address', 'latitude', 'longitude',
'claimed', 'awards', 'popularity_detailed', 'popularity_generic',
'top_tags', 'price_level', 'price_range', 'meals', 'cuisines',
'special_diets', 'features', 'vegetarian_friendly', 'vegan_options',
'gluten_free', 'original_open_hours', 'open_days_per_week',
'open_hours_per_week', 'working_shifts_per_week', 'avg_rating',
'total_reviews_count', 'default_language',
'reviews_count_in_default_language', 'excellent', 'very_good',
'average', 'poor', 'terrible', 'food', 'service', 'value', 'atmosphere',
'keywords'

## Notebooks
#### 1. Data Preparation: creating a flat file with category data. Output: flat_file3.csv
#### 2. ML Project EDA: contains data expolration and visualization
#### 3. Data Cleansing: this notbook handle the missing values
#### 4. MAP: an appendix notebook to display the restaurants in a map
#### 5. Model_Selection: train different machine learning models