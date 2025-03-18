# DSA 210 Term Project – Survivorship Bias in Data Science

## Overview
This project focuses on **Survivorship Bias** in data science by first analyzing the classic **WWII Bomber Study**. In that study, lead statistician **Abraham Wald** analyzed damage on returning bombers to determine which areas should be armored. While other statisticians suggested reinforcing the most-damaged areas, Wald argued that the areas showing little or no damage on surviving bombers were actually the critical spots—since bombers hit in these areas likely did not return.  

This counterintuitive insight not only saved lives but also serves as a foundational example of how evaluating only successful cases (i.e., the surviving bombers) can lead to catastrophic misinterpretations.

By extending this analysis to modern datasets, such as those in **business and education**, the project aims to illustrate how **survivorship bias** can distort our understanding of success. For instance, when colleges highlight the achievements of successful graduates or when media celebrates notable **college dropouts**, they may be ignoring a vast number of failures. Such selective reporting can create a misleading narrative that suggests dropping out is a viable path to success, when in reality it might simply be a case of **survivorship bias**.

---

## Research Questions
This project aims to answer the following key research questions:

1. **How does survivorship bias influence decision-making in historical and modern datasets?**
2. **What key patterns emerge when comparing the bomber study with modern business and education datasets?**
3. **How does the exclusion of failure cases lead to skewed conclusions in areas such as career success and business survival?**
4. **Can identifying survivorship bias improve the accuracy of predictive models and policy-making?**

---

## Data Collection

### **Historical Data**
- **Archived Documents on the Bomber Study**: Primary documents and archival records detailing the damage analysis of returning bombers by **Abraham Wald**.  
- These sources provide insights into how the study was conducted and the rationale behind the conclusions drawn.

### **Modern Data**
- **US Bureau of Labor Statistics**:  
  - Datasets related to **education outcomes**, **employment rates**, and other relevant statistics that offer a comprehensive view of **success and failure rates**.
- **Supplementary Datasets**:  
  - Additional datasets from sectors such as **education and the finance market** to enrich the analysis and draw broader comparisons.  
  - These may include **dropout rates, career trajectories, and financial performance metrics**.

### **Qualitative Data**
To add context, qualitative data such as **case studies, interviews, or reports** may be collected. Some key sources include:
- **Personal Accounts of College Dropouts**:  
  - Narratives and case studies from students who struggled after dropping out.
- **Startup Failure Reports**:  
  - Case studies and statistics on business failures vs. successful entrepreneurs.

---

## Data Features

### **Bomber Study Data**
- `Aircraft Type` – Unique name for each aircraft.  
- `Damage Location` – Areas where damage was recorded.  
- `Operator` – Whether the aircraft was **civilian or military**.  
- `Summary` – Description of how the aircraft was **damaged, shot down, or survived**.

### **Modern Business & Education Data**
- `Education Level` – High school, college dropout, bachelor’s, master’s, etc.  
- `Employment Status` – Employed, unemployed, entrepreneur.  
- `Annual Income` – Salary or business revenue.  
- `Years in Industry` – Experience level in the chosen career.  
- `Company Survival Rate` – Whether the business survived past a certain number of years.  
- `Funding & Investment Data` – Initial capital for startups, investor backing.  

These features will be analyzed to detect **patterns of survivorship bias** and assess its impact on **decision-making**.

---

## Data Usage
The collected data will be used to:

- **Analyze Survivorship Bias**:  
  Compare the historical data from the **bomber study** with modern datasets to demonstrate how focusing **solely on survivors** (successful outcomes) can skew results.  

- **Conduct Comparative Analysis**:  
  Evaluate similar patterns in **modern sectors** such as **education and business**.  
  For example, by comparing the **success metrics of college graduates with those of dropouts**, **hidden biases** in commonly reported statistics can be revealed.  

- **Develop Actionable Insights**:  
  Identify the **critical factors** that contribute to both **success and failure**, thereby offering a **more balanced view** of performance.  
  This analysis aims to guide **better decision-making** in **resource allocation and policy design**.

---

## Tools for Data Manipulation

To effectively handle data collection, processing, and analysis, the following tools will be utilized:

### **Programming & Analysis**
- **Python**  
  - `pandas` & `NumPy` – For data manipulation and cleaning.  
  - `scikit-learn` – For implementing **statistical tests and machine learning models** to analyze and predict outcomes.

### **Data Visualization**
- `Matplotlib` & `Seaborn` – For creating **insightful visualizations** that reveal trends and patterns in the data.

### **Version Control & Documentation**
- **Git & GitHub**  
  - To maintain **version control**, track **project progress**, and ensure **regular commits**.  
  - All code will be **well-documented**, and a comprehensive `README.md` will be provided to facilitate **reproducibility**.

### **Additional Tools**
- **Jupyter Notebooks**  
  - For **interactive data analysis and visualization**, enabling an **iterative exploration** of data and methodologies.

---

## Conclusion
This project seeks to bridge a classic historical example with modern data challenges. By revisiting Abraham Wald’s bomber study and comparing it with modern datasets from education and business, the aim is to uncover how survivorship bias affects data interpretation. The insights gained from this project will not only deepen our understanding of survivorship bias but also highlight the importance of including all data—both successes and failures—in our analyses to drive better decision-making.


