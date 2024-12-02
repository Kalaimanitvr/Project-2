# 🏢 Employee Absenteeism Analysis: A Data-Driven Approach to Workforce Management

## 🌟 Quick Access Links
Explore the project details using these resources:
- 📓 **[Jupyter Notebook 1](./c9_project1.ipynb)**: Core analysis and model development.
- 📓 **[Jupyter Notebook 2](./c9_project2.ipynb)**: Extended analysis and clustering exploration.
- 📊 **[Presentation Slides](./c9_projectppt.pdf)**: High-level insights and strategic recommendations.

---

## 📜 Project Introduction
Employee absenteeism is a significant challenge for organizations, affecting productivity and resource allocation. This project uses **data analysis and machine learning** to identify patterns in absenteeism, predict high-risk employees, and suggest actionable strategies to improve workforce management.

The dataset, covering employee absenteeism from **July 2007 to July 2010**, includes:
- Employee demographics and service details.
- Reasons for absence categorized into 21 groups.
- Workload, education level, and other social factors.

As a **data analyst**, the aim of this project is to:
- Provide actionable insights into the causes and patterns of absenteeism.
- Build predictive models to identify at-risk employees.
- Develop clustering techniques to segment employees for targeted interventions.

---

## 🎯 Objectives
### Key Goals
1. **Understanding Absenteeism**:
   - Analyze key drivers behind employee absenteeism.
   - Identify patterns in absence frequency and duration.

2. **Predictive Modeling**:
   - Use machine learning to predict the likelihood of employee absenteeism.
   - Focus on precision and recall to minimize false negatives.

3. **Clustering Employees**:
   - Group employees based on absenteeism behavior and underlying factors.
   - Use clustering results to recommend personalized interventions.

4. **Workforce Optimization**:
   - Assess workload distribution and its relationship with absenteeism.
   - Provide actionable recommendations for resource planning.

---

## 🛠️ Methodology
### Data Preparation
- **Dataset Overview**:
  - The dataset contains **no missing values** and covers employee absenteeism for 3 years.
  - Key columns: Employee ID, reason for absence, age, service time, education level, workload/day, and more.

- **Outlier Treatment**:
  - Outliers in workload and absence frequency were identified and treated to ensure model reliability.

- **Data Cleaning**:
  - Standardized columns for analysis and ensured consistency across the dataset.

### Machine Learning Techniques
1. **Classification Models**:
   - **K-Nearest Neighbors (KNN)**:
     - Achieved an accuracy of **91.9%**.
     - Optimal K value determined using the elbow method (**K=5**).
     - High precision (0.93) and recall (1.00) for identifying employees **not at risk**.
   - **Evaluation Metrics**:
     - Accuracy: 92%
     - ROC Score: 0.741 (fair distinction between risk levels).

2. **Clustering Analysis**:
   - **K-Means Clustering**:
     - Determined optimal clusters using the elbow method and silhouette analysis.
     - Optimal cluster count: **6**.
     - Silhouette score: 0.178, indicating moderate separation and cohesion among clusters.

3. **Visualization**:
   - Created charts showing absenteeism distribution by reason, workload/day, and work characteristics.
   - Highlighted the top reasons for absenteeism:
     - **Medical Consultation (23)**.
     - **Physiotherapy (27)**.
     - **Dental Consultation (28)**.

---

## 📈 Key Insights and Findings
### 🔍 Patterns in Absenteeism
- **Top Reasons for Absence**:
  - Medical consultation, dental consultation, and physiotherapy are the leading causes.
- **Seasonality**:
  - Certain months show spikes in absenteeism, likely influenced by seasonal illnesses or personal factors.
- **Employee Demographics**:
  - Younger employees and those with lower education levels showed higher absence rates.

### 🧑‍💻 Predictive Model Insights
- The **KNN model** effectively identifies employees **not at risk** with **high precision (0.93)** and **perfect recall (1.00)**, minimizing false negatives and ensuring resource allocation efficiency.

### 🧬 Employee Clustering
- **K-Means Clustering** identified **6 distinct groups** based on absenteeism patterns and associated factors.
- Clusters revealed differences in workload tolerance, absence frequency, and underlying reasons, enabling targeted interventions.

### 🏋️ Workload Analysis
- Employees with consistently high workloads showed higher absenteeism rates, emphasizing the need for balanced resource distribution.

---

## 🏁 Conclusion
This project highlights the critical role of **data analysis in workforce management**. By identifying key drivers of absenteeism, predicting at-risk employees, and clustering individuals based on absenteeism behavior, it provides organizations with a clear roadmap to optimize their workforce. 

### Key Takeaways:
- **Actionable Insights**: Identifying major absenteeism causes (e.g., medical consultations) allows organizations to target support and reduce absences.
- **Predictive Modeling**: The KNN model achieves high precision and recall, making it a reliable tool for proactive workforce management.
- **Clustering Benefits**: Clustering employees provides actionable segmentation for personalized strategies.

This project demonstrates my ability to:
1. Analyze complex datasets to extract meaningful insights.
2. Apply machine learning techniques for real-world applications.
3. Effectively communicate results through visualizations and reporting.

### Business Impact:
Organizations can use the findings to:
- Implement preventive health programs for employees at risk.
- Distribute workloads more evenly to improve productivity.
- Use predictive models to make informed staffing decisions.

---
