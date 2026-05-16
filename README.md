<div align="center">
  <h1>🍿 Netflix Content Analysis (EDA)</h1>
  <p><i>An Exploratory Data Analysis of Netflix Movies and TV Shows</i></p>

  ![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
  ![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
  ![Matplotlib](https://img.shields.io/badge/Matplotlib-11557c?style=for-the-badge)
  ![Seaborn](https://img.shields.io/badge/Seaborn-4EACB8?style=for-the-badge)
</div>

---

## 📖 Project Overview
This project focuses on **Exploratory Data Analysis (EDA)** of the Netflix content catalog. By analyzing a dataset of thousands of movies and TV shows, we aim to uncover trends, distribution patterns, and key characteristics of Netflix's offerings.

The analysis is performed using **Python** in a Jupyter/Google Colab Notebook environment, leveraging libraries like `pandas`, `matplotlib`, and `seaborn` for data manipulation and visualization.

### ✨ Key Objectives
- **Content Mix**: Analyze the proportion of Movies vs. TV Shows on the platform.
- **Missing Data Handling**: Identify and clean missing information to ensure data integrity.
- **Geographic Distribution**: Determine the top content-producing countries.
- **Release Trends**: Explore how content releases have evolved over time.
- **Content Ratings**: Understand the distribution of age and content ratings.
- **Genre Popularity**: Identify the most popular genres and categories (`listed_in`).

---

## 📂 Repository Structure

| File | Type | Description |
|------|------|-------------|
| 📓 `Netflix_EDA_Project.ipynb` | Jupyter Notebook (`.ipynb`) | The main interactive notebook containing the full Python code, step-by-step data cleaning, EDA, and visualizations. |
| 📄 `NETFLIX MOVIES AND TV SHOWS CLUSTERING.csv` | CSV Dataset (`.csv`) | The raw dataset used for the analysis containing 7,787 Netflix content records and 12 detailed features (like cast, director, country, release year). |
| 📖 `README.md` | Markdown (`.md`) | Comprehensive documentation for the project, outlining the overview, tech stack, and key insights. |

---

## 🛠️ Tech Stack & Libraries

- **Language:** Python 3
- **Data Manipulation:** `pandas`, `numpy`
- **Data Visualization:** `matplotlib`, `seaborn`
- **Environment:** Google Colab / Jupyter Notebook

---

## 📊 Key Insights & Analytics

<details>
<summary><b>1. Data Overview & Cleaning</b> (Click to expand)</summary>

- The dataset contains **7,787 entries** across **12 columns**.
- **Missing Values Analysis:** Identified missing data primarily in the `director` (30.6%), `cast` (9.2%), and `country` (6.5%) columns.
- **Data Imputation:** Missing categorical values were replaced with `"Unknown"` to prevent data loss and maintain analytical consistency.
</details>

<details>
<summary><b>2. Content Mix (Movies vs TV Shows)</b> (Click to expand)</summary>

- A significant majority of the content on Netflix consists of **Movies** compared to **TV Shows**.
- Visualized using a Pie Chart to clearly illustrate Netflix's focus and strategy in terms of media formats.
</details>

> *(Explore the `Netflix_EDA_Project.ipynb` notebook for the complete suite of EDA steps, including distribution plots, bar charts for top producing countries, and time-series analysis of content release years.)*

---

## 🚀 Quick Start

1. Clone this repository to your local machine.
2. Ensure you have the required Python libraries installed:
   ```bash
   pip install pandas numpy matplotlib seaborn
   ```
3. Open `Netflix_EDA_Project.ipynb` in **Jupyter Notebook** or upload it to **Google Colab**.
4. Run all cells to see the step-by-step data cleaning process and generated visualizations.

---

## 👨‍💻 Author

**Rahul Adhikari**
- GitHub: [@ursrahuladhikari](https://github.com/ursrahuladhikari)

<div align="center">
  <i>If you found this analysis insightful, please consider giving the repository a ⭐!</i>
</div>
