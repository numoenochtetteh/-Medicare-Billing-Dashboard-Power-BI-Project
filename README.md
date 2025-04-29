🏥 Medicare Billing Dashboard – Power BI Project
This project demonstrates a comprehensive healthcare billing dashboard built using Power BI. It provides key financial and operational insights for a hospital or medical billing unit using Medicare-related data.

📌 Objective
The aim of this dashboard is to help healthcare organizations transition from Excel-based reporting to interactive Power BI dashboards. It provides real-time visibility into costs, coverage, procedures, provider performance, and city/state-wise billing trends – enabling faster, data-driven decisions.

📊 Key Dashboard Features
✅ Financial KPIs: Total Billing Amount, Medication Cost, Treatment Cost, Insurance Coverage, Out-of-Pocket Expenses.
🩺 Diagnosis vs Service Type Analysis: Billing split across Emergency, Inpatient, and Outpatient services by diagnosis.
🏥 Department Performance: Compare total billing across departments like Cardiology, Neurology, Pediatrics, etc.
🔬 Procedure Costs: X-Ray, CT Scan, MRI, Blood Tests, and more.
🌍 Geo Analysis: City and State-based billing contribution via interactive maps.
📈 DAX Measures: Custom calculations like Avg Billing per Visit, Avg Out-of-Pocket, Avg Insurance Coverage, and more.
🧩 Dataset Structure
This project uses fictionalized Medicare billing data split into multiple relational tables:

Patients: Demographics, race, age, city
Visits: Treatment details, charges, provider info, service type
Providers: Doctor details
Insurance: Provider info for billing coverage
Procedures: Medical procedures mapped to visits
Diagnoses: Diagnoses per visit
Departments: Department assignment for each case
Cities: Geographical dimension for mapping
🛠 Tools & Technologies
Microsoft Power BI
Power Query (ETL)
DAX for calculated fields and KPIs
Excel (initial data formatting)
📌 Use Case
This dashboard can be used by:

Hospital administrators
Medical billing teams
Revenue cycle managers
Business analysts in healthcare
It helps answer:

Where is most of our billing revenue coming from?
Which procedures are the most expensive?
Which departments are generating the most revenue?
How much are patients paying out-of-pocket?
🧠 Learnings
Built custom DAX measures for cost KPIs
Created data model with 1:M & M:1 relationships
Used maps, bar charts, slicers, and tooltips for insights
Simulated real healthcare reporting needs in a visual format
