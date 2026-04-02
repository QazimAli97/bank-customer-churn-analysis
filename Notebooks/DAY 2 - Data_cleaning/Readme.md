## 🚀 Day 2: Data Cleaning & Preparation

### ✔ Tasks Performed
- Removed irrelevant columns: `RowNumber`, `CustomerId`, `Surname`
- Checked and handled duplicate records
- Verified data types for all features
- Explored categorical variables (`Geography`, `Gender`)

---

### 📊 Key Observations
- Dataset reduced from **14 columns to 11 columns**
- No duplicate records found
- Data is clean and ready for analysis
- Identified important categorical features for further analysis

---

### 📈 Sample Code

```python
# Drop unnecessary columns
df.drop(['RowNumber', 'CustomerId', 'Surname'], axis=1, inplace=True)

# Check duplicates
df.duplicated().sum()

# Check categorical variables
df['Geography'].value_counts()
df['Gender'].value_counts()
```
Mohammad Ali  
📊 Aspiring Data Analyst  

🔹 Skilled in: SQL | Excel | Power BI | Python  
🔹 Currently building real-world data analytics projects  
