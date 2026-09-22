# Real Estate Price Prediction

Predicts house price per unit area using **Linear Regression** on the Real Estate dataset (Taiwan).

## Dataset
**Real estate.csv** — 414 rows, 8 columns

| Feature | Description |
|---|---|
| Transaction Date | Date of house transaction |
| House Age | Age of the house (years) |
| Distance to MRT | Distance to nearest MRT station (meters) |
| Stores | Number of nearby convenience stores |
| Latitude | Geographic latitude |
| Longitude | Geographic longitude |
| House Price (target) | Price per unit area |

## What the notebook does
1. Load and explore the dataset
2. Rename columns for readability
3. Drop irrelevant column (`No`)
4. Split data — 80% train / 20% test
5. Apply StandardScaler for feature scaling
6. Train Linear Regression model
7. Evaluate with MSE and R² Score
8. Visualize Actual vs Predicted prices

## Results
| Metric | Score |
|---|---|
| MSE | 53.50 |
| R² Score | 0.68 |

## How to run
1. Install dependencies: `pip install -r requirements.txt`
2. Place `Real estate.csv` in the same folder
3. Open `REAL_ESTATE.ipynb` in Jupyter or Google Colab
4. Run all cells

