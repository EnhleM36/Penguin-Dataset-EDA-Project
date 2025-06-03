# Penguin-Dataset-EDA-Project
# 🐧 Penguin Dataset Exploratory Data Analysis (EDA)

This project performs an exploratory data analysis (EDA) on the [Palmer Penguins dataset](https://allisonhorst.github.io/palmerpenguins/), a popular alternative to the Iris dataset for data visualization and classification tasks.

The analysis focuses on understanding physical differences among penguin species, exploring the relationships between body measurements, and building basic regression models to predict body mass.

---

## 📊 Dataset Overview

The dataset includes measurements for three species of penguins (Adelie, Chinstrap, and Gentoo) collected from three islands in the Palmer Archipelago, Antarctica. Variables include:

- **Species**
- **Island**
- **Bill length (mm)**
- **Bill depth (mm)**
- **Flipper length (mm)**
- **Body mass (g)**
- **Sex**

---

## 🎯 Objectives

- Perform basic data exploration and cleaning  
- Visualize feature distributions by species and sex  
- Analyze correlations among physical characteristics  
- Use linear regression to model predictors of body mass  
- Interpret and summarize meaningful biological patterns

---

## 🛠 Tools & Libraries

- **Python**
- **Pandas**
- **Seaborn**
- **Matplotlib**
- **Plotly**
- **Statsmodels**

---

## 📌 Key Findings

- **Gentoo penguins** tend to have the highest body mass and longest flippers.
- **Bill length** is positively correlated with body mass, while **bill depth** shows a negative relationship.
- Penguins are clearly grouped by species and island, with no overlap for some species (e.g., Gentoo only on Biscoe).
- Sex and island location are significant predictors of body mass when included in a regression model.

---
 ## 🧠 Learning Reflection
This project helped me strengthen foundational data analysis skills, including data cleaning, visualization, correlation analysis, and regression modeling. 
It also reinforced good practices like commenting code and presenting findings clearly.

---
## 🚀 How to Run the Project

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/penguin-eda.git
   cd penguin-eda

---
## 📎 Credits
Dataset: Palmer Penguins – Allison Horst

Inspired by the R community's shift from the Iris dataset to more diverse, ethical examples.
