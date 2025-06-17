

# 🍽️ Restaurant Report: Identifying Star Restaurants

## 📋 Executive Summary

This report provides a comprehensive analysis of a multi-national restaurant dataset to identify high-performing “star” restaurants and derive strategic insights. Using data with 19 attributes and a country-code mapping file, we performed Exploratory Data Analysis (EDA), evaluated operational metrics, and examined key factors impacting ratings and reach. These findings will guide the development of a B2C portal leveraging intelligent automation and recommendation systems.

---

## 📊 Data Understanding and Inspection

### Structure and Integrity

* ✅ No missing values across all attributes.
* ✅ No duplicate entries — ensuring clean, reliable data.
* 📌 Data includes both categorical (e.g., `City`, `Cuisines`, `Online Delivery`) and numerical (e.g., `Votes`, `Cost for Two`) attributes.

---

## 🔍 Exploratory Data Analysis (EDA)

### 🌍 Geographical Distribution

* **Most restaurants:** New Delhi (4,688)
* **Least restaurants:** Victor Harbor (1)
* **Insight:** Strong concentration in metropolitan areas, sparse in smaller towns — ideal for expansion planning.

### 🏪 Franchise Reach

* Assessed the **number of countries** each brand operates in to determine franchise scale.

### 📅 Table Booking Availability

* **Available:** 4.44%
* **Not Available:** 95.56%
* 💡 *Opportunity:* Integrate with reservation platforms to drive user convenience.

### 🚚 Online Delivery Presence

* **Available:** 25.09%
* **Not Available:** 74.91%
* 💡 *Opportunity:* Promote delivery adoption in offline-heavy regions.

---

## 👍 Votes Analysis: Delivery vs. Non-Delivery

| Type           | Total Votes |
| -------------- | ----------- |
| Delivery       | 148,354     |
| Non-Delivery   | 214,226     |
| **Difference** | **-65,872** |

➡️ Despite growth in delivery, dine-in restaurants receive significantly more user engagement.

---

## 🍽️ Cuisine Insights

### Top 10 Cuisines

1. North Indian (3,179)
2. Chinese (2,186)
3. Fast Food (1,862)
4. Mughlai (809)
5. Bakery (700)
6. South Indian (569)
7. Desserts (559)
8. Street Food (528)
9. Cafe (518)
10. Mithai (366)

### Cuisine Diversity

* **Max per restaurant:** 8
* **Min per restaurant:** 1

### City-Level Preferences

* **New Delhi:** North Indian
* **Mumbai:** Chinese
* **Bangalore:** Continental

---

## 💰 Cost and Ratings Analysis

### 💸 Cost for Two

* Wide cost range; includes luxury and fine dining outliers.
* ⚠️ *Normalization needed* for cross-country comparisons.

### ⭐ Rating Distribution

* Ratings cluster between **3.0 and 4.5**
* Categorized as: `Excellent`, `Good`, `Poor`, etc.

### 🔎 Influencing Factors

* **Cuisines:** More variety = potentially higher appeal.
* **Cost:** Slight positive trend with better ratings.
* **Online Delivery & Booking:** No direct rating impact but influences votes and user access.

---

## 🎯 Optimization Opportunities

1. **Promote restaurants** with online delivery.
2. **Encourage table booking** integrations.
3. **Scale successful franchises** into smaller cities.

---

## 📈 Dashboarding and Visualization

### Dynamic Cards Created

* Total Restaurants
* Franchise Count
* Highly Rated Restaurants
* Cuisine Count

### Filters Implemented

* `City`
* `Country`
* `Cuisine`
* **Custom Filter:** `Star Restaurant` (with categories):

  * `Normal`
  * `Customer Favourite`
  * `Franchise Leader`
  * `Budget Pick`

---

## 🚀 Next Steps

* Develop B2C portal UI based on filters and visual insights.
* Implement AI-driven recommendation engine using star restaurant metrics.
* Monitor key metrics (votes, delivery presence, rating trends) for continual performance evaluation.


