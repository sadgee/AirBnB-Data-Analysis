# AirBnB-Data-Analysis
Your README is very well structured and informative — great job! 🎯

Here’s a lightly polished version of your content for improved clarity, formatting consistency, and grammar. It also includes a proper title format and some minor enhancements:

---

````markdown
# 🏙️ Airbnb Listings EDA Project: New York 2024

---

## 📌 Project Overview
This project performs **Exploratory Data Analysis (EDA)** on New York Airbnb data to uncover trends and patterns in rental listings. Libraries such as **Pandas**, **NumPy**, **Matplotlib**, and **Seaborn** are used for data cleaning, visualization, and analysis.

![NYC Skyline](https://github.com/najirh/Python-Project-P2-New-York-AirBnb-Listing-2024/blob/main/New-York-City-Brooklyn-Bridge-Panorama-Juergen-Roth-2.jpg)

---

## 🎯 Objectives

- Analyze **room types, prices, and availability** across neighborhoods.
- Understand **host behavior** and listing patterns.
- Detect **price outliers**.
- Provide recommendations for **guests** and **hosts** based on data insights.

---

## 📊 Dataset

- **Entries**: 20,765
- **Features**: 22

Key Columns:
- `id`: Unique listing ID  
- `name`: Listing title  
- `host_name`: Name of the host  
- `neighborhood_group`: Borough (e.g., Manhattan, Brooklyn)  
- `latitude` / `longitude`: Geolocation  
- `price`: Nightly rate  
- `room_type`: Type of stay (Entire home, Private room, etc.)  
- `reviews_per_month`: Monthly average reviews  
- `availability_365`: Days available in the year  

---

## 🔄 Workflow

### 1. 🧹 Data Cleaning

- Handled null values in `price`, `neighborhood`, and `beds`.
- Converted `last_review` to `datetime` format.
- Capped extreme prices above $1,000 to avoid skewing plots.

### 2. 🔍 Exploratory Data Analysis

- **Room Types**: Counted and visualized room type frequencies.
- **Borough Comparison**: Manhattan had the highest average prices.
- **Availability**: Correlated availability with price and reviews using heatmaps.
- **Price Distribution**: Most listings fell within the $50–$300 range.
- **Host Analysis**: Found hosts with multiple listings using boxplots.
- **Review Trends**: Used pair plots to study relationships among reviews, availability, and price.

### 3. 📈 Data Visualizations

- **Bar Charts**: Room type and borough breakdown
- **Histograms**: Price distributions and outliers
- **Boxplots**: Price ranges across hosts
- **Heatmaps**: Feature correlations
- **Pairplots**: Relationships between reviews, availability, and price

---

## 🔑 Key Insights

1. **Pricing**:  
   - Manhattan is the priciest borough.
   - Entire homes cost more, but private rooms offer budget options.

2. **Room Types**:  
   - Entire homes/apartments dominate the listings.

3. **Outliers**:  
   - Listings over $10,000 exist and were flagged as outliers.

4. **Availability**:  
   - High-availability listings often receive more reviews.

5. **Host Behavior**:  
   - Some hosts manage 10+ properties — indicating professional hosting.

---

## ⚙️ How to Run This Project

1. Clone the repository:
   ```bash
   git clone https://github.com/najirh/Python-Project-P2-New-York-AirBnb-Listing-2024.git
   cd Python-Project-P2-New-York-AirBnb-Listing-2024
````

2. Install required libraries:

   ```bash
   pip install pandas numpy matplotlib seaborn
   ```

3. Open the Jupyter notebook:

   ```bash
   jupyter notebook day23_airbnb_eda.ipynb
   ```

Or run it in **Google Colab** by uploading the notebook and dataset.

---

## 💡 Recommendations

### For Guests:

* Look for listings with **high availability** and **positive reviews**.
* Consider **private rooms in Brooklyn** for affordable options.

### For Hosts:

* Maintain high availability and fast response rates.
* Monitor neighborhood pricing to stay competitive.
* Professional hosts with multiple listings should optimize for guest experience.

---

## ✅ Conclusion

This EDA project provides valuable insights into New York City's 2024 Airbnb market. By analyzing pricing, availability, and host behavior, the findings help both **guests** and **hosts** make more informed decisions. Future work may involve **predictive modeling** or **clustering** to expand the analysis.

---

## 📄 License

This project is open-source and licensed under the [MIT License](https://opensource.org/licenses/MIT).

---

```

---

Would you also like a `requirements.txt` file or a badge section (e.g., `Python version`, `Status`, etc.) added to this README?
```
