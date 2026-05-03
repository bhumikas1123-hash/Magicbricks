# MagicBricks Real Estate EDA

## Project Overview

This project presents an in-depth **Exploratory Data Analysis (EDA)** of a real estate dataset sourced from MagicBricks. The dataset consists of residential property listings across Delhi, capturing key attributes such as price, area, BHK, location, furnishing status, and property type.

The analysis focuses on understanding dataset structure, handling inconsistencies, and uncovering meaningful patterns through statistical techniques and data visualizations. It provides a structured view of how different property features are distributed and represented in the real estate market. 

---

## Dataset Summary

* **Source:** Kaggle
* **Size:** 1214 rows × 13 columns 
* **Domain:** Delhi Residential Real Estate

### Key Features:

* Price & Price per Sq. Ft.
* Area (sq. ft.)
* BHK, Bathrooms
* Location, District, Locality
* Property Type & Status
* Furnishing & Parking

---

## Data Cleaning & Preparation

* Removed **79 duplicate entries**
* Handled missing values using:

  * Median (Parking)
  * Dropping minimal null rows
  * Derived values (Price/Area for Per Sqft)
* Corrected unrealistic entries (e.g., 114 parking spots → 1)
* Converted data types and standardized categorical values
* Treated outliers in Area, BHK, Bathrooms, and Parking 

---

## Exploratory Data Analysis

### Univariate Analysis

* Price distribution is **right-skewed**
* Most properties lie below **₹5 Crore**
* Majority area range: **1200–1800 sq. ft.** 

### Bivariate Analysis

* Strong relationship between **Area and Price (~0.84 correlation)**
* Clear price differences across locations
* Semi-furnished properties show higher median prices 

### Multivariate Insights

* BHK, Area, and Bathrooms show **multicollinearity**
* Parking and Price per Sq. Ft. act as independent variables
* Larger properties show higher price variability 

---

## Key Insights

* **Area is the strongest price determinant**
* **3 BHK is the market “sweet spot”** (highest demand)
* Market is segmented into **Budget, Mid-range, and Luxury**
* **South Delhi dominates** with highest listings (~37%)
* Semi-furnished homes have highest median pricing
* Presence of extreme outliers (luxury segment) 

---

## Market Insights (Delhi Focus)

* **Premium Zones:** South Delhi, South-West Delhi
* **Affordable Zones:** East Delhi, Shahdara
* **Low Inventory:** Central Delhi (high value, low supply) 

---

## Tools & Technologies

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook

---

## Conclusion

The analysis highlights that **property size and location are the primary drivers of price**, while features like furnishing and amenities play a secondary role. The dataset clearly reflects structured segmentation in the Delhi real estate market, enabling better strategic and investment decisions. 

---

## Acknowledgment
I sincerely thank my mentors, faculty, and peers for their constant support and valuable guidance throughout this project. I also appreciate the open-source community for offering resources that helped deepen my knowledge of data analysis and visualization.
