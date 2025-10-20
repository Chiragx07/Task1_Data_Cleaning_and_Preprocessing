# 🧹 Task 1 – Data Cleaning and Preprocessing

### 🎯 Objective
Clean and prepare a raw dataset containing missing values, duplicates, and inconsistent formats using **Python (Pandas)**.

---

### 📊 Dataset
**Name:** Medical Appointment No Shows  
**Source:** Kaggle  
**File:** `Medical.csv` → cleaned as `Medical_Cleaned.csv`

---

### ⚙️ Tools Used
- Python 3  
- Pandas, NumPy  
- Google Colab  
- GitHub (for submission)

---

### 🧠 Steps Performed
1. **Loaded dataset** using `pandas.read_csv()`  
2. **Identified missing values** with `.isnull()` and filled numeric columns with median and categorical columns with mode  
3. **Removed duplicate rows** using `.drop_duplicates()`  
4. **Standardized text fields** (e.g., gender → male/female)  
5. **Converted date columns** to consistent `dd-mm-yyyy` format  
6. **Renamed column headers** (lowercase, no spaces)  
7. **Checked and fixed data types** (e.g., `age` as integer)  
8. **Exported cleaned dataset** as `Medical_Cleaned.csv`

---

### 📸 Screenshots
- Raw dataset view  
- Code execution in Colab  
- Cleaned dataset preview  

*(Screenshots are uploaded in this repository.)*

---

### 📄 Key Learnings
- Handling missing data and duplicates using Pandas  
- Standardizing and formatting real-world data  
- Preparing data for analysis and modelling  
- Understanding the importance of data preprocessing  

