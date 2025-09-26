# Netflix Dataset Pandas Practice

This repository contains a Jupyter notebook where I explored the **Netflix Movies & TV Shows dataset** using **Python and Pandas**.  

The goal of this project was to practice **data manipulation, cleaning, and analysis** with real-world tabular data.

---

## 📂 Project Structure

project/
│
├─ notebook/ # Jupyter notebook(s) with analysis
├─ data/ # CSV dataset
│ └─ netflix_titles.csv
├─ .gitignore # ignores venv and checkpoints

## 📝 Notebook Highlights

- Loaded and explored the dataset (`netflix_titles.csv`)  
- Checked for missing values and basic info  
- Created a **genre column** from `listed_in`  
- Filtered movies released after 2015  
- Counted movies/TV shows by type, year, and country  
- Worked with string operations to analyze genres and directors  
- Performed groupby and aggregation to summarize data

## 🚀 Skills Practiced

- Python & Pandas basics: `.head()`, `.info()`, `.describe()`  
- Filtering, selecting, and subsetting data  
- String operations (`.str.split()`, `.explode()`)  
- Grouping and aggregation (`groupby`, `value_counts`)  
- Sorting and ranking  
- Handling missing data

## 📈 Dataset

The dataset used in this project can be found on [Kaggle](https://www.kaggle.com/datasets/shivamb/netflix-shows).

## 📌 How to Run

1. Clone the repository:

```bash
git clone https://github.com/yourusername/pandas-practice-netflix.git
cd pandas-practice-netflix
