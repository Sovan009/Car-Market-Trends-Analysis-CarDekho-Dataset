# Car-Market-Trends-Analysis-CarDekho-Dataset
An exploratory data analysis (EDA) project on used-car listings from "CarDekho", uncovering pricing trends, depreciation patterns, and the factors that most influence resale value.
## 📌 Project Overview

This project analyzes a dataset of used car listings to understand:
- How selling price relates to a car's age, mileage, fuel type, and transmission
- How much value cars lose from their original showroom price (depreciation)
- Which car models are most commonly listed and how their prices compare
- The impact of ownership history and seller type (dealer vs. individual) on price

The analysis is built as a ready-to-run Google Colab script, making it easy to reproduce or extend.

## 📂 Dataset

**File:** `Car_Market_Trends_Analysis_with_Car_Dekho_Data.csv`

| Column | Description |
|---|---|
| `Car_Name` | Model name of the car |
| `Year` | Year of manufacture |
| `Selling_Price` | Price the car was sold/listed for (in Lakhs) |
| `Present_Price` | Current ex-showroom price of the car when new (in Lakhs) |
| `Kms_Driven` | Total kilometers driven |
| `Fuel_Type` | Petrol / Diesel / CNG |
| `Seller_Type` | Dealer / Individual |
| `Transmission` | Manual / Automatic |
| `Owner` | Number of previous owners |

**Size:** 301 listings, 9 columns, no missing values.

## 🛠️ Tools & Libraries

- Python 3
- pandas, numpy — data manipulation
- matplotlib, seaborn — visualization
- Google Colab (recommended environment)

## 🚀 How to Run

1. Open [Google Colab](https://colab.research.google.com/)
2. Create a new notebook
3. Copy the code from [cardekho_car_amrket_trend_analysis](https://colab.research.google.com/drive/1-vxwtoK7g-Mes-UTJo-ltTKHfNhVnHfG?usp=sharing) into cells (the script is pre-split into 11 labeled cells — `# --- CELL 1`, `# --- CELL 2`, etc.)
4. Run each cell in order and upload the CSV file when prompted in Cell 1

## 📊 Analysis Covered

1. **Data cleaning** — duplicate removal, feature engineering (car age, depreciation %)
2. **Categorical breakdown** — fuel type, seller type, transmission distributions
3. **Price & mileage distributions** — histograms of selling price, present price, kms driven
4. **Top car models** — most-listed models and their average prices
5. **Price vs. age/mileage/fuel type** — scatter and box plots
6. **Depreciation analysis** — average value loss by car age and fuel type
7. **Correlation heatmap** — relationships between numeric features
8. **Ownership & seller impact** — price by number of owners and seller type
9. **Outlier detection** — IQR-based flagging on price and mileage
10. **Auto-generated summary report** — key stats compiled into a text report

## 📈 Output

Running the full script produces:
- Multiple visualizations (distribution plots, box plots, scatter plots, heatmap)
- A printed and saved **summary report** with headline statistics on pricing, fuel type mix, most-listed model, average mileage, ownership, and correlations

## 📁 Repository Structure

```
.
├── P3-Car_Market_Trends_Analysis_with_Car_Dekho_Data.csv   # Dataset
├── cardekho_market_trends_analysis.py                      # Analysis script (Colab-ready)
└── README.md                                                # Project documentation
```

## ✍️ Author

Madhav — B.Tech, Computer Science & Data Science

## 📄 License

This project is for educational and portfolio purposes.
