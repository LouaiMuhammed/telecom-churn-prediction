# Telecom Customer Churn Analysis and Prediction

## Project Overview
This project was developed as part of the **DEPI Internship Program** and serves as a **graduation project**.  
The main objective is to perform a thorough **analysis** of customer churn behavior within a telecom company and build **predictive models** capable of identifying customers at risk of leaving the service.

---

## Dataset Information

- **Source**: Kaggle
- **Shape**: 7,043 rows × 21 columns

### Data Features

#### Demographics
- `customerID`: Unique customer identifier
- `gender`: Male or Female
- `SeniorCitizen`: Whether the customer is 65 or older
- `Partner`: Whether the customer is married
- `Dependents`: Whether the customer has dependents
- `tenure`: Number of months the customer has stayed with the company

#### Services Signed Up
- `PhoneService`, `MultipleLines`, `InternetService`
- `OnlineSecurity`, `OnlineBackup`, `DeviceProtection`
- `TechSupport`, `StreamingTV`, `StreamingMovies`

#### Account Information
- `Contract`: Contract type (Month-to-Month, One Year, Two Year)
- `PaperlessBilling`: Whether billing is paperless
- `PaymentMethod`: Method of payment
- `MonthlyCharges`: Monthly billing amount
- `TotalCharges`: Total billing amount to date

#### Target Variable
- `Churn`: Whether the customer left the company within the last month

---

## Project Structure

The project workflow is organized into the following stages:

1. **Data Inspection and Cleaning**  
   - Checking for missing values and inconsistencies
   - Cleaning and formatting the dataset for analysis

2. **Exploratory Data Analysis (EDA)**  
   - Visualizing churn distribution
   - Analyzing relationships between features and customer churn

3. **Data Preprocessing**  
   - Encoding categorical variables
   - Scaling numerical features if necessary
   - Splitting data into training and testing sets

4. **Modeling and Evaluation**  
   - Building classification models to predict churn
   - Evaluating models using appropriate metrics such as accuracy, precision, recall, F1-score, and ROC-AUC

*(Details on modeling and results will be updated as the project progresses.)*

---

## Repository Structure

```plaintext
├── data/
│   └── telecom_churn.csv  # Dataset file
├── notebooks/
│   └── churn_analysis_prediction.ipynb  # Main project notebook
├── README.md
```
*(Folder structure might be updated as the project evolves.)*

---

## Technologies Used

- **Programming Language**: Python 3.11.9
- **Libraries**:
  - NumPy
  - Pandas
  - Matplotlib
  - Seaborn
  - Scikit-learn

More to be found in `requirements.txt`
---



## Team Members

This project was developed by:  
- **Abdelfatah Ibrahim Abdelfatah** [Team Leader]
- **Ahmed Mohamed Ahmed**
- **Eslam Moheyeldeen Hassan**
- **Mohamed Ali Mostafa**
- **Louay Mohamed Abdelsalam**
- **Louai Muhammed Ibrahim**

---


### To run this project locally:
1. Clone the repository
2. Install the required libraries
3. Run the notebook `churn_analysis_prediction.ipynb`

---

# 📄 License

This project is intended for academic and educational purposes under the DEPI Internship Program.

