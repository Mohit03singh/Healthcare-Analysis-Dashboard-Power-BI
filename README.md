# Healthcare-Analysis-dashboard-Power-BI
### Background:-
You are a data analyst at HealthStat Solutions, a company specializing in healthcare analytics. You have been given two datasets: 'Patient Medical Records' and 'Hospital Treatment Details'. The 'Patient Medical Records' dataset contains detailed information on patients, including their age, gender, blood type, diagnosis, treatments, admission and discharge dates, and total bills. The 'Hospital Treatment Details' dataset provides insights into the hospitals treating these patients, including the treating doctor, room number, daily costs, treatment types, and recovery ratings.
![image](https://github.com/user-attachments/assets/ce7aaeee-233f-4cc5-8467-140286d8527c)

### Objective;-
As an analyst at HealthStat Solutions, your objective is to leverage Power BI for a deep dive into the provided healthcare datasets. This task encompasses meticulous data cleaning and sophisticated data modeling, utilizing DAX for advanced analytics. Your goal is to create a comprehensive, interactive dashboard in Power BI that presents a cohesive narrative of the healthcare data. This dashboard should serve as a tool to uncover and visualize important trends, such as the interplay between patient demographics and treatment outcomes, cost implications of various medical procedures, and overall hospital performance metrics. Your analysis will provide invaluable insights, aiding healthcare providers in enhancing patient care and operational efficiency, and positioning HealthStat Solutions at the forefront of healthcare analytics.

![image](https://github.com/user-attachments/assets/6291a45d-6cc7-433a-a5d4-7ea0a70b9d14)

### **Data Source:**
The "HealthcareDataset1.xlsx" file contains the following columns:

1. **PatientID**: A unique identifier for each patient. (Primary Key)
2. **PatientName**: Name of the patient.
3. **Age**: Age of the patient.
4. **Gender**: Gender of the patient.
5. **BloodType**: Blood type of the patient.
6. **Diagnosis**: The diagnosis given to the patient.
7. **Treatment**: The treatment provided to the patient.
8. **AdmissionDate**: Date when the patient was admitted.
9. **DischargeDate**: Date when the patient was discharged.
10. **TotalBill**: The total bill amount for the patient's treatment.
11. **Full Prescription Details**: Detailed prescription information including medication names, dosages, frequency, and duration.


The "HealthcareDataset2.xlsx" file contains the following columns:

1. **PatientID**: A unique identifier for each patient, corresponding to 'PatientID' in "HealthcareDataset1.xlsx". (Foreign Key)
2. **Hospital**: The name of the hospital where the patient was treated.
3. **DoctorName**: Name of the doctor who treated the patient.
4. **RoomNumber**: The room number assigned to the patient.
5. **DailyCost**: The daily cost of the patient's treatment.
6. **TreatmentType**: Type of treatment provided.
7. **RecoveryRating**: A rating of the patient's recovery (out of 10).

**Welcome to the Healthcare Analysis Dashboard!**

![Screenshot (258)](https://github.com/user-attachments/assets/29ba943c-100c-42f9-ab3d-3b2df3a7da9e)

![Screenshot (257)](https://github.com/user-attachments/assets/5e67d8ab-8198-428a-b808-5052a78c8585)

![Screenshot (259)](https://github.com/user-attachments/assets/278b0d12-a5c8-48ce-bab7-27dea4790b51)

![image](https://github.com/user-attachments/assets/5a00e4d3-bd78-45b6-a466-e9aabe218e96)



<h1>Overview</h1>

**Key Metrics**: Get a snapshot of patient demographics, diagnosis distribution, treatment costs, and recovery ratings.

**Filters**: Use filters to narrow down data by hospitals, diagnosis, and treatment types for more targeted analysis.


![image](https://github.com/user-attachments/assets/1055c8b3-bdd8-4ab4-b14e-54db9e2bee3d)



<h1>Interactive Hospital Performance Comparison</h1>
                                
**Performance Comparison**: Compare hospitals based on patient load, treatment costs, and recovery ratings through interactive visualizations.

**Drill-Down Capabilities**: Drill down into specific hospital performance metrics for detailed analysis.

 <h1>Treatment Effectiveness Visualization</h1>
                               
**Treatment Evaluation**: Visualize the effectiveness of different treatments based on length of stay and recovery ratings, aiding in treatment optimization and outcome improvement.

![image](https://github.com/user-attachments/assets/b8badbc2-b596-419b-af93-a720294bb719)

 <h1>Key Insights and Data Storytelling</h1>
 
![Screenshot (286)](https://github.com/user-attachments/assets/e1a368b1-1cf1-4244-a406-fad6a1dd2e78)
.
![image](https://github.com/user-attachments/assets/0ac81a64-90df-4c79-bbfb-2bef31616260)

<h1>Tool </h1>
                                         
**Power BI**: Leveraged for data visualization, analysis, and dashboard creation.

**DAX (Data Analysis Expressions)**: Utilized for advanced analytics and calculations within Power BI.

![image](https://github.com/user-attachments/assets/6383262a-c245-4ef5-8664-bf1ae6d6a655)

<h1>Data Cleaning and Preprocessing</h1>

- **Data Importing and Initial Examination:** Import the datasets into Power BI and perform a preliminary examination to identify data quality issues or inconsistencies.
- **Merging Datasets:** Merge the 'Patient Medical Records' and 'Hospital Treatment Details' datasets using a suitable key column, ensuring accuracy and retention of all necessary information.

- **Handling Missing and Irrelevant Data:** Identify and address missing data, duplicates, and irrelevant data points to ensure data quality.

- **Data Type Conversion:** Convert 'AdmissionDate' and 'DischargeDate' to appropriate date formats and calculate the length of stay for each patient.

- **Categorizing Age Groups:** Create a new column categorizing patients into age groups (e.g., Child, Adult, Senior) for more granular analysis.
- 
![image](https://github.com/user-attachments/assets/e717c1c2-88ef-456d-bad1-013e3717e18a)

<h1>Conclusion</h1>
This healthcare analytics project has demonstrated the transformative power of data in improving patient care and optimizing hospital operations. By meticulously cleaning and analyzing datasets from patient medical records and hospital treatment details, we've uncovered invaluable insights that can drive significant advancements in healthcare.

From identifying the most effective treatments and their cost implications to understanding the impact of demographics on patient outcomes, our comprehensive Power BI dashboard equips healthcare providers with the knowledge they need to make informed, data-driven decisions. The interactive features and advanced analytics enable stakeholders to explore trends, compare performance metrics, and implement strategies that enhance both patient care and operational efficiency.

The findings highlight the critical role of doctors, the importance of efficient hospital utilization, and the potential for predictive modeling to anticipate patient recovery outcomes. By harnessing these insights, HealthStat Solutions is positioned at the forefront of healthcare analytics, ready to revolutionize how healthcare providers approach patient care and management.

In an industry where every decision can impact lives, this project underscores the necessity of leveraging data to its fullest potential. Together, we are paving the way for a healthier, more efficient future in healthcare.

![image](https://github.com/user-attachments/assets/77b7fb1e-bd57-4792-8ffa-35fbd8042a1b)
![image](https://github.com/user-attachments/assets/0e1d8802-80af-4883-aaf0-ef838d7019ac)

