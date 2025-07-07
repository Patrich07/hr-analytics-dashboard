
# HR Analytics Dashboard – Power BI Project

This HR Analytics project provides a comprehensive dashboard built with **Power BI**, designed to uncover insights about staff distribution, gender balance, salary structure, regional trends, and performance ratings.

The goal of this project is to help HR managers and decision-makers identify pay gaps, staff distribution imbalances, and opportunities for policy improvement using interactive visualizations.

---

## 📁 Project Files

- `HR_Analytics.pbix` – The Power BI dashboard file
- `HR_Raw_Dataset.xlsx` – The original (uncleaned) HR dataset
- `images/` – Folder containing dashboard screenshots for visual reference

> ⚠️ **Note**: Only the original dataset is included in this repository. All data cleaning and transformation were performed inside Power BI using Power Query.

---

## 🧹 Data Cleaning & Transformation

The dataset included is the **raw version** because Power BI does not support exporting transformed datasets directly. However, the following cleaning steps were performed inside **Power Query in Power BI**:

- ✅ **Removed duplicates** to avoid double-counting of employee records  
- ✅ **Removed null and blank values** to maintain data quality  
- ✅ **Standardized** column names and ensured correct data types  
- ✅ **Unpivoted** the second dataset to reshape it into a normalized, analysis-ready format  
- ✅ Verified consistency in categorical fields such as Gender, Department, and Rating

These transformations ensured the data was suitable for analysis and visualization within the Power BI environment.

---

## 📊 Dashboard Overview

The dashboard consists of three main pages:

### 🔹 1. Overview

- **Total Staff**: 874 employees
- **Departments**: 12
- **Regions**: 3 (Kaduna, Abuja, Lagos)
- **Gender Distribution**:  
  - Male: 49.2%  
  - Female: 46.5%  
  - Undisclosed: 4.3%

- **Staff by Department**: Legal, Product Management, and Service have the largest staff counts
- **Gender Distribution by Region & Department**: Kaduna has the highest gender balance, while Lagos has the lowest number of employees overall

### 🔹 2. Gender & Department Analysis

- **Average Salary**:  
  - Male: $74.51K  
  - Female: $72.61K  
  - Undisclosed: $79K

- **Total Salary by Region**:  
  - Kaduna leads with $24M in total pay (combined genders)  
  - Lagos pays the least

- **Top-Paying Departments**: Legal ($106K), Marketing ($102K), and Accounting ($85K for females)

- **Gender Ratings**: Male employees slightly outperform females in performance ratings

### 🔹 3. Salary Band

- **Total Pay**: $66.55M  
- **Total Bonus**: $2.02M  
- **Employees Earning Above $90K**: 275  
- **Employees Below $90K**: 599

- **Most Common Salary Band**: $100K+ (190 employees)
- **Salary Distribution by Region**: Kaduna has more high earners than Lagos and Abuja

---

## 💡 Key Insights

- There is a **slight gender pay gap** favoring male employees (~$1.9K difference)
- Kaduna region offers the highest salaries and has the most employees
- Some departments like **Support**, **Training**, and **Research** have significantly lower average salaries
- Performance ratings show male employees score higher on average
- Most employees fall within the **$100K+ salary band**, but there’s still a large group below $90K

---

## ✅ Recommendations

- **Review gender pay equity**: Although the gap is small, fairness should be enforced
- **Standardize salaries across regions** to ensure equity, especially for Lagos-based staff
- **Support underpaid departments** through training, development, and career progression pathways
- **Encourage gender disclosure** to improve diversity tracking and analysis
- **Refine bonus allocation** strategy based on transparent performance metrics

---

## 🛠 Tools Used

- **Microsoft Power BI** – For data modeling, visualization, and analysis
- **Power Query** – For data cleaning, shaping, and transformation
- **Excel** – Used for preliminary review of the raw data
- **DAX** – For creating calculated columns and measures in Power BI

---

## 📸 Dashboard Screenshots

| Overview Page | Gender & Department Analysis | Salary Band |
|---------------|------------------------------|-------------|
| | 
![PHR 01](https://github.com/user-attachments/assets/1b1cf085-c7e5-4bc4-bd9a-552e1d72c298)

---![PHR002](https://github.com/user-attachments/assets/27ff4d58-f493-447a-8f07-5203d1612e59)

![PHR003](https://github.com/user-attachments/assets/c4e83781-1536-4bdb-af39-c82b45d95f41)

## 👩‍💻 Author

**Patience Richard Bassey**  
Junior Data Analyst | Passionate about data-driven HR decision-making  
📍 Ajah, Lagos, Nigeria  
📧 patiencebassey@gmail.com  
🔗 [LinkedIn Profile](https://www.linkedin.com/in/pbassey1000)

---

## 📌 Contact / Feedback

If you have feedback or suggestions, feel free to open an issue or connect via LinkedIn.


