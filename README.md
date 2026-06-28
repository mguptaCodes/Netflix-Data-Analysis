# Netflix Data Analysis Project

## Project Overview
This project focuses on analyzing Netflix movies and TV shows dataset to extract meaningful insights such as content trends, ratings, genres, and release patterns. The goal is to understand how Netflix content is distributed and how viewer preferences vary.


## Objectives
-> Analyze Netflix content distribution
-> Identify popular genres and trends
-> Study release patterns over the years
-> Compare ratings, popularity, and vote counts
-> Build an interactive Power BI dashboard for visualization


## Tools & Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Power BI
- Jupyter Notebook


## Dataset
This project uses the following datasets:

- **Original Dataset:** `mymoviedb.csv`  
  Contains raw Netflix movies and TV shows data.

- **Cleaned Dataset:** `movies_cleaned.csv`  
  Contains cleaned and processed data used for analysis and visualization.


## Project Structure
Netflix-Data-Analysis

notebooks/           # Jupyter notebooks for analysis
data/                # Raw and cleaned datasets
powerbi/             # Power BI dashboard file (.pbix)
screenshots/         # Visual outputs and charts
requirements.txt     # Project dependencies
README.md


## Key Insights
- Drama and Action genres dominate Netflix content distribution.
- Movies released after 2015 show a significant increase in production volume.
- High vote count does not always mean high rating — popularity and rating show weak correlation.
- Most Netflix content falls in the medium popularity range, indicating balanced engagement.
- A clear growth trend in content production is visible over the years, especially after Netflix expansion globally.


## How to Run This Project
1. Clone the repository  
git clone https://github.com/mguptaCodes/Netflix-Data-Analysis.git

2. Navigate to the project folder  
cd Netflix-Data-Analysis

3. Check Python version (recommended)
python --version

4. Create a virtual environment (optional but recommended)  
python -m venv env

5. Activate the virtual environment  
- Windows:
env\Scripts\activate  

- Mac/Linux:
source env/bin/activate  

7. Install required dependencies  
pip install -r requirements.txt

8. Install Jupyter Notebook (if not installed)
pip install jupyter

9. Open Jupyter Notebook  
jupyter notebook

10. Run the notebooks step by step inside the "notebooks/" folder

11. (Optional) Open Power BI dashboard  
Go to the "powerbi/" folder and open the .pbix file using Power BI Desktop


Author
Manaswi Gupta
