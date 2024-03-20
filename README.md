
# Uber Data Analysis Project

![](https://images.unsplash.com/photo-1482029255085-35a4a48b7084?q=80&w=1931&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D)

This project involves the analysis of Uber ride-sharing data using Pandas, seaborn, and matplotlib to extract insights and trends. The dataset used contains information about Uber trips, including timestamps, locations, trip distances, fares, and other relevant attributes.

## Dataset Description

The dataset used for this analysis can be found on [TLC](https://www.nyc.gov/site/tlc/about/tlc-trip-record-data.page). It consists of a CSV file containing the following columns:

- **VendorID:** ID of the vendor
- **tpep_pickup_datetime:** Pickup timestamp
- **tpep_dropoff_datetime:** Dropoff timestamp
- **passenger_count:** Number of passengers
- **trip_distance:** Distance of the trip
- **pickup_longitude:** Longitude of pickup location
- **pickup_latitude:** Latitude of pickup location
- **RatecodeID:** Rate code for the trip
- **store_and_fwd_flag:** Flag indicating if the trip was stored and forwarded
- **dropoff_longitude:** Longitude of dropoff location
- **dropoff_latitude:** Latitude of dropoff location
- **payment_type**: Payment method used
- **fare_amount:** Fare amount
- **extra:** Extra charges
- **mta_tax:** MTA tax
- **tip_amount:** Tip amount
- **tolls_amount:** Toll amount
- **improvement_surcharge:** Improvement surcharge
- **total_amount:** Total fare amount

## Analysis Steps

1. **Data Loading and Preprocessing**: The dataset is loaded into a Pandas DataFrame. Timestamp columns are converted to datetime objects.

2. **Exploratory Data Analysis (EDA)**: Descriptive statistics are calculated, and initial visualizations are created using Pandas methods, seaborn, and matplotlib to explore the dataset's characteristics.

3. **Feature Engineering**: Additional features such as pickup/dropoff hour, day, month, and weekday are extracted from datetime columns to facilitate further analysis.

4. **Dimension Creation**: Dimensions are created for categorical variables such as passenger count, trip distance, and rate code.

5. **Advanced Analysis**: Various Pandas methods are used for advanced analysis, including grouping, aggregation, and filtering, to gain deeper insights into the data.

6. **Visualization**: Informative visualizations are created using Pandas plotting functionalities, seaborn, and matplotlib to present key findings and trends effectively.

## Files Included

- `uber_data.csv`: The dataset used for analysis.
- `data.ipynb`: Jupyter Notebook containing the Python code for data analysis.

## Requirements

- Python 3
- Pandas
- seaborn
- matplotlib
- Jupyter Notebook

## Usage

1. Clone the repository:

   ```bash
   git clone https://github.com/yashvisharma1204/Uber_rides-data_analysis.git
   ```

2. Navigate to the project directory:

   ```bash
   cd uUber_rides-data_analysis
   ```

3. Install the required dependencies:

   ```bash
   pip install pandas seaborn matplotlib jupyter
   ```

4. Open and run the Jupyter Notebook:

   ```bash
   jupyter notebook data.ipynb
   ```
