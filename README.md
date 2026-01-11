# 📊 Monitoring Inefficient Operators — CallMeMaybe

## 📌 Project Description
This project focuses on identifying **inefficient operators** in a virtual telephony service (CallMeMaybe) using data analysis and statistical methods. The goal is to support supervisors and managers in making **data-driven decisions** by highlighting operational inefficiencies related to call handling quality and performance.

The analysis combines exploratory data analysis, KPI definition, statistical hypothesis testing, and data visualization to deliver actionable insights and a practical monitoring solution through an interactive dashboard.

---

## 🎯 Project Objective
The main objective of this project is to **identify operators with inefficient performance** based on objective and measurable criteria, avoiding subjective judgments. An operator is considered inefficient when poor performance is observed across multiple indicators related to call handling quality.

---

## 🧪 Methodology
The project followed a structured analytical workflow:

1. **Data Understanding and Exploration**
   - Analyzed the structure and quality of the datasets
   - Identified missing values, data types, and outliers

2. **Data Preparation**
   - Cleaned and transformed data for analysis
   - Created derived variables such as waiting time
   - Aggregated data at the operator level

3. **KPI Definition**
   - Missed call rate
   - Average waiting time
   - Number of outgoing calls

4. **Business Rule Definition**
   - Operators classified as inefficient when performing poorly in at least two KPIs
   - Percentile-based thresholds used to ensure robustness against outliers

5. **Statistical Analysis**
   - Formulated hypotheses comparing efficient vs. inefficient operators
   - Applied Levene’s test to assess equality of variances
   - Used Student’s t-test or Welch’s t-test as appropriate

6. **Visualization and Communication**
   - Created boxplots and ranking charts for visual validation
   - Developed an interactive dashboard for stakeholder consumption

---

## 📈 Results
The analysis revealed statistically significant differences between efficient and inefficient operators in terms of **call handling quality**:

- Inefficient operators exhibit a **higher missed call rate**
- Inefficient operators have a **significantly higher average waiting time**
- No statistically significant difference was found in the number of outgoing calls

These findings indicate that operator inefficiency is primarily associated with **quality of received calls**, rather than productivity in outbound calls.

---

## 🛠️ Tools Used
- **Python**
  - Pandas
  - NumPy
  - Matplotlib
  - Seaborn
  - SciPy
- **Jupyter Notebook**
- **Tableau Public** (interactive dashboard)
- **GitHub** (version control and project sharing)

---

## 📚 What I Learned (Skills & Competencies)
Through this project, I developed and strengthened the following skills:

- Translating business problems into analytical questions
- Exploratory Data Analysis (EDA)
- Data cleaning and feature engineering
- KPI definition and performance measurement
- Statistical hypothesis testing and interpretation
- Visual validation of analytical findings
- Dashboard development for decision support
- Clear communication of technical results to non-technical stakeholders

---

## 🚀 Potential Improvements
While the project achieved its objectives, possible future improvements include:

- Incorporating **time-based analysis** to track operator performance trends
- Applying **non-parametric statistical tests** for additional robustness
- Expanding the dashboard with filtering by client or time period
- Automating the pipeline for real-time monitoring

---

Dashboard (Tableau Public): https://public.tableau.com/app/profile/rosana.barbosa.dos.santos/viz/MonitoramentodeOperadoresIneficientesCallMeMaybe/Painel1#1
