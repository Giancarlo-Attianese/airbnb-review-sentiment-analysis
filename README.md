# Airbnb Review Sentiment Analysis 🏠📊

This project analyzes Airbnb reviews to identify the most discussed themes and understand customer sentiment over time.

The analysis is based on a sample of 5,000 reviews and combines text preprocessing, keyword-based topic detection, sentiment analysis, and data visualization.

---

## 📌 Project Objectives

- Identify the most frequent themes in Airbnb reviews (e.g. Location, Cleanliness, Host, Value)
- Analyze sentiment (positive, neutral, negative) for each theme
- Study how sentiment evolves over time (monthly, seasonal, yearly)
- Create clear and informative visualizations to support insights

---

## 🧠 Methodology

1. **Data Cleaning**
   - Removal of missing and empty reviews
   - Text normalization (lowercasing)

2. **Theme Detection**
   - Keyword-based matching for predefined themes:
     - Location
     - Cleanliness
     - Host
     - Value
     - Check-in
     - Amenities
     - Accuracy

3. **Sentiment Analysis**
   - Performed using `TextBlob`
   - Sentiment polarity classified as:
     - Positive
     - Neutral
     - Negative

4. **Temporal Analysis**
   - Monthly sentiment trends
   - Seasonal comparison (Winter, Spring, Summer, Fall)
   - Yearly sentiment evolution

---

## 📊 Visualizations

The notebook includes:
- Theme frequency bar charts
- Sentiment distribution by theme
- Monthly, seasonal, and yearly sentiment trends
- Advanced dashboards combining sentiment and review volume

---

## 🛠️ Technologies Used

- Python
- Pandas
- Matplotlib
- Seaborn
- TextBlob
- Google Colab

---

## 📁 Repository Structure

- `*.ipynb` → Main analysis notebook
- `README.md` → Project description

---

## 🚀 How to Run the Project

1.
