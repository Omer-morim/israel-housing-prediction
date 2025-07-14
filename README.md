# Real Estate Price Prediction using AI and Web Scraping

This project is a Jupyter notebook that analyzes and predicts apartment prices in Israel using web scraping, data cleaning, and basic machine learning techniques.  
Developed as part of an academic project in the Computer Science degree at HIT.

---

## Project Goals

- Collect apartment listing data through web scraping
- Clean and normalize the raw textual data
- Engineer features such as floor level, price trends, and apartment attributes
- Build a prediction model for estimating prices based on location and features
- Explore data trends and visualizations

---

## Tools and Technologies

- Python
- Jupyter Notebook
- Selenium (for scraping)
- Pandas, NumPy (for data manipulation)
- Matplotlib, Seaborn (for visualization)
- Scikit-learn (for modeling)

---

## Main Steps

1. **Data Collection**  
   Apartment data scraped from local real estate sites using Selenium

2. **Data Cleaning**  
   - Removing duplicates  
   - Extracting numerical values from text fields  
   - Standardizing columns (e.g., floor levels, trend percentages)

3. **Feature Engineering**  
   - Calculating total floors, lowest/highest floor  
   - Converting trends into numerical values  
   - Deriving useful indicators from messy input

4. **Exploratory Data Analysis (EDA)**  
   - Understanding patterns, correlations, and visual trends

5. **Model Building**  
   - Applying simple regression or prediction methods 

---

## File Structure

project_data_science/
└── Automated Real Estate Price Prediction using Web Scraping and AI.ipynb

---

## How to Run

1. Make sure you have Jupyter and the required packages:

   pip install jupyter pandas numpy selenium matplotlib seaborn scikit-learn

2. Launch the notebook:

   jupyter notebook

3. Open the `.ipynb` file and run cell by cell.

---

## Authors

Developed by Bar Tal & Omer Morim
B.Sc. in Computer Science, HIT
