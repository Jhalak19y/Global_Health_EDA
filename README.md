
# 🌍 Global Health EDA – Life Expectancy Analysis

This project is an Exploratory Data Analysis (EDA) of the **Life Expectancy dataset** by WHO, focused on identifying the key factors that influence life expectancy across countries.

The analysis was performed using Python in Google Colab with libraries like Pandas, Seaborn, Matplotlib, and Plotly.

## 📌 Project Objective

To analyze global health indicators such as **GDP, schooling, disease rates, and status (Developed/Developing)** to understand their impact on **Life Expectancy** and identify patterns that can help inform public health strategies.

---

## 📁 Dataset

- **Source**: [Kaggle - Life Expectancy (WHO)](https://www.kaggle.com/datasets/kumarajarshi/life-expectancy-who)
- **Records**: 2,938 rows
- **Features**: 22 columns (e.g., Country, Year, Life Expectancy, GDP, Schooling, Diseases, Health Expenditure)

---

## 🔧 Tools & Libraries Used

- Python 🐍
- Pandas for data manipulation
- Matplotlib & Seaborn for visualization
- Plotly for interactive charts
- Google Colab as the development environment

---

## 📊 Key Visualizations & Insights

1. **Distribution of Life Expectancy**  
   - Most countries have life expectancy between 60–80 years.
2. **Box Plot: Developed vs Developing Countries**  
   - Developed countries show significantly higher life expectancy.
3. **Correlation Heatmap**  
   - Schooling, income composition, and immunization positively correlate with longer life.
4. **GDP vs Life Expectancy Scatter Plot**  
   - Higher GDP often links to better health outcomes.
5. **Schooling vs Life Expectancy**  
   - More education is associated with higher life expectancy.
6. **Line Chart for India**  
   - Shows how life expectancy in India has improved steadily over the years.

---

## 📈 Sample Code Snippet

```python
plt.figure(figsize=(10, 6))
sns.scatterplot(data=df, x='Schooling', y='Life_expectancy_', hue='Status')
plt.title("Schooling vs Life Expectancy")
plt.show()
