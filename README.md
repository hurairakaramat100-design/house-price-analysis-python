# House Price Analysis using Python

This beginner-level project analyzes the factors that may affect house prices using Python.

The analysis focuses on **area size, number of rooms, location, rating, and age of the house**. The goal is to understand the data before building a Machine Learning regression model.

## Dataset

The project uses 40 synthetic house records.

### Features

- `House_ID` – Unique house identifier
- `Area_SqFt` – House area in square feet
- `Rooms` – Number of rooms
- `Location` – House location
- `Rating` – House rating from 3.0 to 5.0
- `Age_Years` – Age of the house
- `House_Price_Lakhs` – House price in lakhs

> **Note:** The dataset is synthetic and created only for educational purposes.

## Tools Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn

## Analysis Performed

1. Loaded and inspected the dataset
2. Checked data types
3. Checked missing values
4. Checked duplicate records
5. Calculated basic statistics
6. Analyzed area vs price
7. Analyzed rooms vs price
8. Compared average prices by location
9. Analyzed house age vs price
10. Created a correlation matrix
11. Prepared categorical data for future Machine Learning

## Project Structure

```text
house-price-analysis-python/
│
├── house_prices.csv
├── House_Price_Analysis.ipynb
├── README.md
├── CONCLUSION.md
│
└── graphs/
    ├── area_vs_price.png
    ├── rooms_vs_price.png
    ├── location_vs_average_price.png
    ├── age_vs_price.png
    └── correlation_matrix.png
```

## Key Results

- Average house price: **313.73 lakhs**
- Lowest house price: **175 lakhs**
- Highest house price: **429 lakhs**
- Average area: **2111.07 sq ft**
- Average rooms: **3.78**
- Average rating: **3.89**
- Average house age: **15.15 years**
- Strongest numerical relationship with price: **Area_SqFt** (correlation ≈ **0.78**)

## How to Run

1. Download or clone this repository.
2. Open `House_Price_Analysis.ipynb` in Jupyter Notebook or Google Colab.
3. Keep `house_prices.csv` in the same folder.
4. Run the notebook cells from top to bottom.

## Conclusion

The analysis shows that house price is related to multiple factors. In this sample, area size, rooms, location, rating, and house age all provide useful information for understanding price differences.

The cleaned and encoded dataset can be used as the starting point for a Machine Learning regression model.

## Project Level

**ML Python Basic – Beginner Level**
