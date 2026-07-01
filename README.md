# Patterns of Hospital Admissions and Healthcare Utilisation: A Descriptive and Inferential Analysis of a Synthetic Electronic Health Record Dataset

## 📌 Project Overview
This repository contains the full research paper and analytical framework for a comprehensive study on healthcare resource utilization and financial billing patterns[cite: 1]. Using a synthetic Electronic Health Record (EHR) dataset comprising 10,000 patient records and 15 clinical, demographic, and financial variables, this study identifies key drivers of healthcare expenditure and disease prevalence[cite: 1].

The analytical approach demonstrates a robust integration of **Data Analysis** and **Public Health/Social Work Research**, providing actionable insights for hospital administration, insurance structuring, and healthcare resource allocation.

---

## 🔬 Research Questions Addressed
### Descriptive Analytics:
1. What are the most prevalent medical conditions within the operational database?[cite: 1]
2. Which specific age demographics account for the highest volume of hospital admissions?[cite: 1]
3. How does the financial burden (average billing amount) of chronic metabolic conditions like Diabetes compare to complex conditions like Cancer?[cite: 1]

### Inferential Statistical Testing:
4. Is there a statistically significant correlation between a patient's age and their total billing amount?[cite: 1]
5. Does the urgency or type of admission (Emergency, Urgent, Elective) significantly affect the final billing cost?[cite: 1]
6. Is there a statistically significant dependency between patient gender and their medical diagnosis?[cite: 1]

---

## 📊 Key Findings & Insights
* **Chronic Disease Prevalence:** Chronic non-communicable diseases (NCDs) dominate the facility profile[cite: 1]. **Arthritis** and **Cancer** emerged as the most prevalent conditions, each accounting for **16.87%** of total admissions, closely followed by **Hypertension (16.76%)**[cite: 1].
* **Demographic Hotspots:** Geriatric and adult medicine demand is critical[cite: 1]. The **60–79 age group** generated the highest admission volume (**29.42%**), while pediatric patients (0–19) represented only 3.04%[cite: 1].
* **Financial Parity:** The study challenged conventional assumptions regarding cost variation; **Cancer** treatments averaged **USD 25,348.84** per patient, showing extreme financial parity with **Diabetes** treatments at **USD 25,197.53**[cite: 1].
* **Statistical Independence (Inferential Results):** 
  * Patient age and billing amount share a near-zero linear relationship ($r = 0.003$), proving that demographic age does not drive cost[cite: 1].
  * A one-way ANOVA confirmed that the mode of admission does not impact expenditure ($P = 0.970$), with mean billing remaining uniform across emergency and elective entries[cite: 1].
  * A Chi-Square Test of Independence established that diagnoses are distributed independently of gender ($p = 0.958$), indicating equal systemic risk across the sample[cite: 1].

---

## 🛠️ Tools & Methodologies Used
* **Descriptive Statistics:** Grouped frequency distributions, cross-tabulations, and localized mean summaries[cite: 1].
* **Inferential Statistics:** Pearson Correlation Coefficient, One-Way Analysis of Variance (ANOVA), and Chi-Square Test of Independence ($\alpha = 0.05$)[cite: 1].
* **Data Context:** Modeled after international EHR structures and operational parameters applicable to developing healthcare infrastructures, such as clinical settings in Mogadishu, Somalia[cite: 1].

---

## 📂 Repository Structure
* 📄 `Healthcare_Research_Paper.pdf` - The complete, publication-ready research paper containing full methodology, academic background, and detailed strategic recommendations.
* 📋 `README.md` - Project documentation and executive summary.

---

## 🧑‍💻 About the Author
**Abdixalim Abdulahi**  
*Researcher, Data Analyst, and Social Worker*  
Focused on leveraging data-driven statistical frameworks to solve complex infrastructural, public health, and social challenges.
