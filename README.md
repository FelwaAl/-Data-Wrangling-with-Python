README.txt  
#Project Title: Real-World Data Wrangling: Movie Metadata and Ratings  
Author: Felwah Alarifi  
File: Project_Real_World_Data_Wrangling_with_Python.ipynb  

---

##Project Description  
This project demonstrates real-world data wrangling and analysis techniques using publicly available movie datasets (from IMDb and Kaggle). The goal is to assess and clean raw data, then integrate it to answer a key research question related to movie popularity and characteristics.

---

##Objectives  
1. Data Gathering  
   - Manual and programmatic acquisition of multiple movie-related datasets (e.g., ratings, metadata, and keywords).

2. Data Assessment  
   - Programmatic inspection using .info(), .isnull().sum(), and visualizations to detect missing or inconsistent data.

3. Data Cleaning  
   - Handling missing values, incorrect data types, malformed entries, and duplicates.  
   - Example: converting string-based numeric values into proper types, filtering corrupted rows.

4. Data Integration  
   - Merging datasets on shared keys like imdb_id and tconst.

5. Storage & Wrangling Output  
   - Final cleaned dataset stored in Pandas DataFrames for further analysis.

---

##Files Included  
- Project_Real_World_Data_Wrangling_with_Python.ipynb: The main Jupyter Notebook containing all code, cleaning logic, and analysis steps.  
- .csv: The dataset used (uploaded separately).  
- README.txt: This instruction file.

---

##Dependencies  
This project requires the following Python libraries (all available in Google Colab):

- pandas  
- numpy  
- matplotlib  
- seaborn  
- os  
- zipfile  
- ast  
- json  

To run this locally, install Kaggle if needed:

```bash
pip install kaggle==1.6.12
