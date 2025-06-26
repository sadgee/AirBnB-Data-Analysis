
#  Airbnb Listings EDA Project: New York 2024

---

## Project Overview

This project involves **Exploratory Data Analysis (EDA)** on Airbnb listings in New York City to uncover trends in pricing, availability, and host behavior. Tools used include **Pandas**, **NumPy**, **Matplotlib**, and **Seaborn** for data cleaning, analysis, and visualization.


---

##  Objective

* Explore **room types, pricing, and availability** across neighborhoods
* Analyze **host behavior** and listing frequency
* Detect **price outliers**
* Offer actionable **recommendations** for both guests and hosts

---

##  Dataset Details

The dataset contains **20,765 records** with **22 features**, such as:

* `id`: Listing ID
* `name`: Listing title
* `host_name`: Host's name
* `neighborhood_group`: Borough name
* `latitude`, `longitude`: Geolocation
* `price`: Nightly cost
* `room_type`: Entire home, private or shared room
* `availability_365`: Days available in a year
* `reviews_per_month`: Monthly review average

---

##  Workflow

### 1. Data Cleaning

* Handled nulls in `price`, `neighborhood`, and `beds`
* Converted `last_review` to **datetime**
* Capped extreme prices (>\$1,000) for better visualization

### 2. Exploratory Data Analysis

* **Room Type Distribution**:

  * Bar plots show most listings are **Entire home/apt**
* **Neighborhood Group Insights**:

  * **Manhattan** has the **highest average price**
* **Availability Trends**:

  * Correlation heatmaps for features like `price`, `beds`, and `reviews`
* **Price Distribution**:

  * Histogram shows most listings between **\$50–\$300**
* **Host Listings**:

  * Boxplots highlight hosts with multiple properties
* **Review Behavior**:

  * Pair plots show link between reviews, availability, and price

### 3. Data Visualization Tools

* **Histograms**: Price distribution
* **Boxplots**: Outlier detection
* **Pair Plots**: Relationship insights
* **Heatmaps**: Correlation between numerical features
* **Bar Charts**: Room types and borough distributions

---

##  Key Insights

1. **Price Trends**

   * **Manhattan** is the most expensive borough
   * Entire homes command significantly higher prices

2. **Room Type Patterns**

   * Entire homes dominate, but **private rooms** offer more budget options

3. **Outlier Detection**

   * Some listings priced above **\$10,000**—skewing data

4. **Availability Patterns**

   * Listings with higher availability tend to have more reviews and lower prices

5. **Host Activity**

   * Some hosts manage several listings—suggesting **professional hosting**

---

##  Recommendations

**For Guests:**

* Look for listings with good availability and reviews for a smoother stay
* Consider **private rooms in Brooklyn** for affordability

**For Hosts:**

* Increase **availability** and respond to reviews promptly
* Stay competitive with borough-specific pricing strategies

---

##  Future Scope

* Apply **machine learning** for price prediction
* Use **sentiment analysis** on guest reviews
* Build an **interactive dashboard** using Plotly or Tableau

---

##  Conclusion

This project uncovers meaningful patterns in the NYC Airbnb market. By leveraging EDA techniques, it offers useful takeaways for both guests and hosts. Future enhancements could include ML and advanced visual analytics to build on these findings.

---

##  License

This project is licensed under the [MIT License](https://opensource.org/licenses/MIT). Free to use and adapt!

---

##  Contact

* **GitHub**: [sadgee](https://github.com/sadgee)
* **LinkedIn**: [Sadgee Pandey](https://linkedin.com/in/sadgee-pandey-7aa36988)

