# 🔋 Electric Vehicle Data Analysis 📊

This project showcases data analysis and visualization on Electric Vehicle (EV) registrations across the United States using Python. It was completed as part of a task from **Innomatics Research Labs**.

---

## 📁 Dataset Information

- **Records**: 112,634
- **Features**: VIN, Make, Model, Model Year, Electric Range, Base MSRP, State, Electric Utility, etc.
- **Source**: Provided CSV dataset (Electric Vehicle Registration)

---

## 🧪 Tasks Completed

### 📌 Task 1: Exploratory Data Analysis (EDA)

#### 🔹 Univariate Analysis
- Count of Electric Vehicle Types (BEV, PHEV)
- Top 5 EV Manufacturers
- Model Year Distribution

#### 🔹 Bivariate Analysis
- Electric Range vs Base MSRP (Scatterplot)
- Electric Range by Make (Boxplot)

---

### 📌 Task 2: Choropleth Visualization

Using `plotly.express`, interactive maps were created:
- **EV Distribution by State**
- **Animated Choropleth**: Year-wise EV growth from 2016 to 2023

---

### 📌 Task 3: Racing Bar Chart

Using `bar_chart_race`, an animated bar chart video was generated:
- **Top 10 EV Makes** over the years (Model Year-wise growth)

---

## 🔍 Key Insights

- ✅ BEVs are more common than PHEVs.
- 🚗 Top EV brands: **Tesla, Chevrolet, Nissan, Ford**
- 🗺️ States like **California, Washington, Florida** show the highest EV penetration.
- 📈 Steep increase in EV adoption post-2017.

---

## 📦 Libraries Used

- `pandas`
- `numpy`
- `seaborn`
- `matplotlib`
- `plotly.express`
