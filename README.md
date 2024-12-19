# **Healthcare Data Analysis**

## **Project Overview**
This project demonstrates comprehensive data cleaning, exploratory analysis, and visualization of a synthetic healthcare dataset. The goal is to extract insights about patient demographics, medical conditions, admission patterns, and billing trends while showcasing data analysis and visualization skills for healthcare applications.

---

## **Dataset Description**
- **Source:** Synthetic dataset containing 55,500 records.
- **Attributes:** Includes patient demographics, medical conditions, admission details, billing information, and test results.
- **Key Columns:**
  - `Age`, `Gender`, `Blood Type`
  - `Medical Condition`, `Admission Type`, `Length of Stay`
  - `Billing Amount`, `Insurance Provider`, `Test Results`

---

## **Key Steps**
### 1. Data Cleaning
- **Handled Missing Values:** Replaced missing or invalid values with appropriate defaults.
- **Standardized Data:** Capitalized names, removed extra whitespaces, and converted dates to `datetime` format.
- **Derived New Features:** Calculated `Length of Stay` from admission and discharge dates.
- **Removed Duplicates:** Dropped 534 duplicate rows to ensure data integrity.

### 2. Exploratory Data Analysis (EDA)
#### **Demographics**
- Gender distribution is balanced: 50% Male, 50% Female.
- Most patients are aged between 35 and 68, with an average age of ~51.5 years.

#### **Medical Insights**
- Top conditions: Arthritis, Diabetes, Hypertension, Obesity.
- Longer average stays observed for conditions like Cancer.

#### **Admission Trends**
- Admission types: Emergency (33%), Urgent (34%), Elective (33%).
- Admission type influences billing and length of stay.

#### **Billing Analysis**
- Billing ranges from -2,008 (outlier) to 52,764, with an average of ~25,539.
- Admission type impacts median billing amount.

#### **Correlation Analysis**
- Strong correlation between `Billing Amount` and `Length of Stay`.

---

## **Visualizations**
1. **Demographics:**
   - Gender distribution (Bar Chart).
   - Age distribution (Histogram).
2. **Medical Conditions:**
   - Condition frequency (Horizontal Bar Chart).
3. **Admission Patterns:**
   - Admission type distribution (Pie Chart).
   - Average length of stay by condition (Bar Chart).
4. **Billing Insights:**
   - Billing amount distribution (Boxplot).
   - Billing by admission type (Boxplot).
5. **Correlation Analysis:**
   - Heatmap showing relationships between numerical features.

---

## **Results**
- Cleaned dataset with no missing values and duplicates removed.
- Insights on patient demographics, medical conditions, and billing patterns.
- Visualizations highlight key trends for easy understanding.

---

## **Future Work**
- Integrate advanced models to predict test results based on features like age, length of stay, and billing.
- Perform anomaly detection for outlier billing values.
- Explore clustering techniques for patient segmentation.

---

## **How to Use**
1. Clone the repository:
   ```bash
   git clone https://github.com/Mewz1k/healthcare-data-analysis.git
