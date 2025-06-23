Project Title: Real-World Data Wrangling: Movie Metadata and Ratings
Author: Felwah Alarifi
File: Project_Real_World_Data_Wrangling_with_Python.ipynb

 Project Description
This project demonstrates real-world data wrangling and analysis techniques using publicly available movie datasets (from IMDb and Kaggle). The goal is to assess and clean raw data, then integrate it to answer a key research question related to movie popularity and characteristics.

 Objectives
Data Gathering

Manual and programmatic acquisition of multiple movie-related datasets (e.g., ratings, metadata, and keywords).

Data Assessment

Programmatic inspection using .info(), .isnull().sum(), and visualizations to detect missing or inconsistent data.

Data Cleaning

Handling missing values, incorrect data types, malformed entries, and duplicates.

Example: converting string-based numeric values into proper types, filtering corrupted rows.

Data Integration

Merging datasets on shared keys like imdb_id and tconst.

Storage & Wrangling Output

Final cleaned dataset stored in Pandas DataFrames for further analysis.

 Files Included
Project_Real_World_Data_Wrangling_with_Python.ipynb: The main Jupyter Notebook containing all code, cleaning logic, and analysis steps.

.csv: The dataset used (uploaded separately).

README.txt: This instruction file.

 Dependencies
This project requires the following Python libraries (all installed in Google Colab by default):

python
نسخ
تحرير
pandas
numpy
matplotlib
seaborn
os
zipfile
ast
json
To run this project locally, you may also need:

bash
نسخ
تحرير
pip install kaggle==1.6.12
 Notes
The first cell force-installs Kaggle and restarts the kernel. It's designed for Google Colab usage.

Ensure all dataset files are correctly uploaded or linked before running the notebook.
