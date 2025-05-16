# fraud-detection-healthinsurance-claims
A data-driven approach using unsupervised ML techniques to flag suspicious claims.

## problem Statement
A rise in fraud in the health insurance sector and traditional fraud detection methods continuosly failing.

## Methodology
1. **Data cleaning and preprocesing**
- Handling null values: Imputing Null values and dropping columns missing more than 50% data
- Feature engineering: Using label encoding and one-hot enoding to convert text data type to text
- 

2. **Exploratory Data Analysis (EDA)**
- Chcking the distribution of some features in the data: e.g years
- Checking correlation of features in the data

3. **Unsupervised ML algorithms**
- Isolation Forest
- One calss SVM
- Local Outlier Factor

## Results
- Mission hospitals had the highest count of flagged cases
- Them month of June had the highest anomaly count
- Most flagged cases showed that patients were admitted for  atotal of 0 days

## Tools
- Python: Pandas and Numpy
- Sklearn
- Streamlit(for deployment)