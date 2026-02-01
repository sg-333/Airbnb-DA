### Airbnb Data Analysis: Bangkok Listings

This project performs a comprehensive data analysis on Airbnb listings in Bangkok. 
The goal is to explore patterns in pricing, location, availability, and clean the dataset, and extract insights. 
The analysis includes data cleaning, visualization, and feature exploration.

**Dataset:** Airbnb Listings Bangkok.csv  
**Source:** Kaggle (https://www.kaggle.com/datasets/samuelsemaya/airbnb-bangkok-samuelsemaya?select=cleaned_data_bangkok.csv)

**Rows:** 10,000+ listings  
**Columns include:** id, name, host_id, host_name, neighbourhood, latitude, longitude, room_type, price, minimum_nights, number_of_reviews, last_review, calculated_host_listings_count, number_of_reviews_ltm, availability_3365.  
Some columns required cleaning, missing value handling, and transformation.

### Methodology:
1. **Data Loading:** Loaded the CSV into a Pandas DataFrame.
2. **Exploration:** Examined dataset structure, summary statistics, missing values, and data types.
3. **Data Cleaning & Transformation:**
   - Handled missing values using mode or removal
   - Detected and treated outliers
   - Encoded categorical variables
   - Created new features where appropriate
4. **Exploratory Data Analysis (EDA):**
   - Visualized distributions, correlations, and relationships between variables
   - Identified key trends and patterns
5. **Insights & Conclusions:** Summarized findings in analysis.


**Key Insights:**
- Most listings are concentrated in entire home/apartments and private homes.
- Prices vary widely by room type and location.
- Number of reviews correlates with price and availability of listings.
- Outliers in price and minimum_nights were identified and treated.


### How to Run:
1. Clone the repository:
2. Install required packages:
3. Open the Jupyter Notebook `project.ipynb` and run the cells step by step.



