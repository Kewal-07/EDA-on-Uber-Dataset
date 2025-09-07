# NCR Ride Bookings – Exploratory Data Analysis

This project contains an **EDA (Exploratory Data Analysis)** of ride booking data.  
The analysis was performed in the Jupyter Notebook: `eda.ipynb`.

---

## 📂 Files in this Repo
- **ncr_ride_bookings.csv** → Raw dataset of bookings.
- **eda.ipynb** → Notebook with step-by-step EDA.

---

## 🔑 Steps in the Notebook

1. **Importing Libraries**  
   Loaded Python libraries such as pandas, numpy, matplotlib, seaborn for data handling and visualization.

2. **Loading Dataset**  
   Read the CSV file into a pandas DataFrame.

3. **Initial Exploration**  
   - Checked shape of the dataset.  
   - Viewed first few rows (`head()`), columns, and data types.  
   - Looked at missing values per column.

4. **Data Cleaning**  
   - Converted `Date` and `Time` into datetime objects.  
   - Created a `Day` column to capture weekdays (Monday–Sunday).  

5. **Univariate Analysis**  
   - Booking status counts (Completed, Cancelled, etc.).  
   - Distribution of vehicle types.  
   - Value counts for payment method.  

6. **Time-based Analysis**  
   - **Booking Distribution by Days**: Average number of bookings for each weekday (Mon–Sun).  
   - Bookings by hour of day.  
   - Bookings by month/season.  

7. **Other Plots**  
   - Ride distance distribution.  
   - Booking value distribution.  
   - Ratings (driver vs customer).  

