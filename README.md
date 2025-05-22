# Healthcare Analysis Using Tableau

---

## Project Objective

This project aims to harness Tableau's powerful visualization and analytical capabilities to transform raw healthcare datasets into meaningful insights. Through calculated fields, data modeling, and advanced visual storytelling, the goal is to:

- Optimize healthcare operations
- Enhance decision-making
- Uncover trends in treatment, cost, and patient recovery

---

## Data Sources

| Dataset | Description |
|---------|-------------|
| **HealthcareDataset1** | Patient-level information including ID, demographics, medical history, billing, and prescriptions. |
| **HealthcareDataset2** | Hospital and treatment-specific data including doctor name, room assignment, treatment cost, and recovery ratings. |

### HealthcareDataset1 Fields
- **PatientID**: Unique patient identifier *(Primary Key)*  
- **PatientName**: Full name of the patient  
- **Age**: Age in years  
- **Gender**: Gender identity  
- **BloodType**: Blood group (e.g., A+, O-)  
- **Diagnosis**: Diagnosed condition  
- **Treatment**: Treatment provided  
- **AdmissionDate**: Date of hospital admission  
- **DischargeDate**: Date of hospital discharge  
- **TotalBill**: Total billed amount  
- **Full Prescription Details**: Includes medications, dosages, frequency, and duration  

### HealthcareDataset2 Fields
- **PatientID**: Foreign Key linking to HealthcareDataset1  
- **Hospital**: Name of treating hospital  
- **DoctorName**: Attending physician  
- **RoomNumber**: Room assigned during stay  
- **DailyCost**: Cost per day of treatment  
- **TreatmentType**: Category/type of treatment  
- **RecoveryRating**: Outcome score (out of 10)  


---

## Key Analyses & Features

- **Stay Duration vs Recovery Rating**  
Explored correlation to measure treatment success.

- **Patient Clustering**  
Grouped patients by treatment and recovery patterns.

- **Prescription Intelligence**  
Identified most prescribed medications by diagnosis.

- **Hospital Efficiency Metrics**  
Analyzed stay duration, recovery rating, and costs.

- **Admission Trends**  
Custom date parsing to reveal busiest times.

- **Dynamic Filtering**  
Filter patients by gender, age, and blood type.

- **Time-Series Forecasting**  
Projected diagnosis-wise admissions for next 6 months.

---

## Dashboards Developed

1. **Comprehensive Healthcare Overview**  
   _TB Healthcare Dashboard_

2. **Hospital Performance Comparison**  
   _TB Hospital Comparison Performance Dashboard_

3. **Time-Based Admission Analysis**  
   _TB Health Care Trend Dashboard_

4. **Treatment Effectiveness Dashboard**  
   _TB Treatment Effectiveness Dashboard_

---

## Key Insights

- **Patient Gender Distribution**:  
  337 females, 329 males, 334 others over 3 years.

- **Diabetes Recovery**:  
  Notable improvements in recovery ratings.

- **Admission Forecast**:  
  Time-series models predict diagnosis trends.

- **Top Doctor**:  
  Dr. David Moore treated the highest number of patients.

- **Costliest Hospital**:  
  Cedar Senai Clinic, followed by Green Valley Medical Center.

- **Best Recovery Facility**:  
  Maple Groove Health Facility ranks #1.

- **Specialist Highlight**:  
  Dr. Elizabeth Davis (Cedar Senai) excels in diabetes treatment.

- **Mental Therapy Trends**:  
  Increasing patient preference over the years.

---

## Conclusion

This project demonstrates the impact of data visualization in the healthcare sector. From understanding patient behavior to evaluating hospital performance, Tableau dashboards offer a user-friendly interface to draw actionable insights for healthcare stakeholders.

---

## Links

- ** View Dashboard**: [Tableau Public](https://public.tableau.com/views/Sahil_Kishor_Tableau_Project_Healthcare_Analysis/Dashboard2?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)
- ** LinkedIn**: https://www.linkedin.com/in/akash-singh-979745147
- ** Email**: akash.singh@georgebrown.ca

---
