# 📊 Google Trends Data Analysis Project

This project uses the **Google Trends API via the `pytrends` Python library** to analyze and visualize keyword trends globally. It simulates the kind of real-time, automated insights a data analyst would extract for decision-making in a data-driven company.

---

## 📁 Data Source

This project pulls live data from [Google Trends](https://trends.google.com/) using the `pytrends` library. It supports dynamic keyword input, meaning you can analyze any term just by changing the keyword in the script.

---

## 💼 Business Objectives

You are working as a data analyst and have been asked to:

1. 🔁 Create a reusable script to fetch trend data for any keyword.
2. 🌍 Identify the **top 15 countries** where the keyword is most searched.
3. 🗺️ Generate a **world heatmap** to visualize geographic interest.
4. 📈 Analyze **time-wise trends** to see how interest has evolved over years.
5. 🔄 Compare **related keywords** and present their popularity using graphs.

---

## 📌 Key Insights

- The script allows for **dynamic keyword search** with a simple input change.
- **Top countries** and **related terms** are extracted using Google Trends’ regional and suggestion APIs.
- A **world map** highlights country-wise interest.
- **Time series data** shows seasonal or long-term interest shifts.
- **Related keyword comparisons** help identify alternative or co-searched terms.

---

## 🧰 Tools & Technologies

- `Python`, `Pandas`, `Matplotlib`, `Seaborn`
- `Pytrends` (Google Trends unofficial API)
- `Plotly` for interactive world map
- `Jupyter Notebook`, `GitHub`

---

## 📈 Visualizations

### 🔹 Top 15 Countries by Interest
![Top 15 Countries Bar Chart](top_countries_searching_for_cloudcomputing.png)

### 🔹 World Map of Keyword Interest
![World Map](newplot.png)

### 🔹 Related Keywords Comparison
![Related Keywords Graph](comparison.png)

> 💡 *All charts are automatically generated based on the keyword input.*

