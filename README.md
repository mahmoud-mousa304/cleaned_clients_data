
### 📊 Overview
This project showcases my data wrangling and cleaning skills using a sample dataset that includes information about customer names, ages, salaries, joining dates, and departments. The goal is to clean the messy, inconsistent data and prepare it for analysis.

---

### 🛠 Tools & Libraries
- Python  
- Pandas  
- NumPy  
- Jupyter Notebook (or any IDE)

---

### 🧹 Data Cleaning Steps
1. **Name Cleaning**  
   - Removed whitespace  
   - Standardized case (e.g., `bob` → `Bob`)  
   - Replaced invalid characters (e.g., `D@niel` → `Daniel`)  

2. **Age Conversion**  
   - Converted strings like `"thirty"` to numbers  
   - Filled missing or invalid values with the column's mean

3. **Salary Processing**  
   - Removed currency symbols (`$`)  
   - Converted to numeric values  
   - Handled missing values using the mean

4. **Join Date Standardization**  
   - Handled inconsistent formats (`2021/01/
