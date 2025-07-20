Project Overview :
This Excel-based dashboard project provides a comprehensive Hospital Emergency Room Analysis to enhance decision-making, patient tracking, and operational efficiency. Designed using Microsoft Excel's advanced visualization and data-handling capabilities, the dashboard helps hospital stakeholders monitor key performance indicators (KPIs) and identify trends to improve emergency room services.

Objective :
To build an interactive and insightful Excel dashboard that allows for quick analysis of:

 1. Patient inflow

 2. Wait times

3. Satisfaction levels

4. Gender and age distribution

5. Admission status

6. Department referrals

📊 Key Features & KPIs
Total Number of Patients – Shows overall footfall (e.g., 488 in July 2024).

Average Wait Time (in minutes) – Automatically calculated (e.g., 35.20 minutes).

Patient Satisfaction Score – Based on collected ratings (e.g., 4.79).

Admission Status – Breakdown of admitted vs. non-admitted patients.

Timeliness – Proportion of patients attended on time (within 30 minutes).

Gender-wise Analysis – Distribution of patients by gender.

Age Group Distribution – Categorized patient data by age range.

Department Referrals – Insight into which departments received most referrals.

🧮 Backend Calculations
Age Grouping Logic:
=IF([Patient Age]>=70,"70-79",
    IF([Patient Age]>=60,"60-69",
    IF([Patient Age]>=45,"45-59",
    IF([Patient Age]>=30,"30-44",
    IF([Patient Age]>=15,"15-29",
    IF([Patient Age]>=5,"05-14","0-4"))))))

    
Patient Attendance Status:

=IF([Patient Waittime]<30, "On Time", "Delay")


Included Files:
Hospital_Dashboard_Excel.xlsx – Main dashboard built in Excel

Hospital Emergency Room Data.csv – Raw data source used in the dashboard

Final_Dashboard_Image.png – Final visual preview of the dashboard

Hospital_logo


Data Context:
Time Period: 2023–2024

Calendar Table: Created using:
=List.Dates(#date(2023,01,01),731,#duration(1,0,0,0))


Tools Used : 
Microsoft Excel (Pivot Tables, Charts, Slicers)

Data Cleaning and Transformation

Custom Formula-Based Logic


