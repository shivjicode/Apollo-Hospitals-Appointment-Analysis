# Apollo Hospitals Appointment Analysis

Python Exploratory Data Analysis of appointment no-shows,
patient engagement, financial performance and service quality.

## Project Objective

Identify patterns associated with missed appointments and
recommend practical ways to improve patient attendance and
appointment utilisation.

## Dataset

- 75,000 appointment records with 52 columns
- 320 doctor records with 15 columns
- Appointment period: January 2022–December 2024
- Join key: doctor_id
- Source: WsCube Tech Milestone Project 4 course dataset

This is a course project, not an official Apollo Hospitals report.

## Tools Used

Python, Pandas, NumPy, Matplotlib, Seaborn and Jupyter Notebook.

## Analysis Areas

- Business Overview
- No-Show Analysis
- Reminder and Engagement Effectiveness
- Patient and Demographic Segmentation
- Financial Performance
- Doctor Utilisation and Service Quality

## Key Findings

- The no-show rate is 15.94%, excluding Scheduled appointments.
- Psychiatry has the highest specialty no-show rate: 24.52%.
- Weekend appointments have a higher no-show rate than weekdays:
  18.68% versus 14.84%.
- Combined SMS, WhatsApp and call reminders are associated with
  an 11.41% no-show rate, compared with 30.16% without reminders.
- No-shows represent approximately ₹1.97 crore in potential
  revenue at listed fees, rather than confirmed net revenue lost.
- Insured patients pay approximately 45% less out of pocket
  per completed appointment on average.

## Analysis Rules

- No-show rate uses Completed + No-Show + Cancelled appointments
  as its denominator and excludes Scheduled appointments.
- Realized revenue and quality metrics use Completed rows only.
- The literal value "None" in the specified categorical fields
  means not applicable and is preserved.
- Findings describe associations and do not establish causation.
- Potential revenue estimates exclude replacement bookings,
  later rescheduling, discounts and insurance adjustments.

## Project Files

- apollo_hospitals_EDA.ipynb — analysis notebook
- Apollo_Hospitals_Charts_and_InsightsReport.pdf — report

## How to Run

1. Download the notebook and obtain both course CSV files.
2. Place the CSVs in the same folder as the notebook:
   apollo_appointments_fact.csv and apollo_doctors_dim.csv.
3. Install the required packages:

   pip install pandas numpy matplotlib seaborn jupyter

4. Open the notebook in Jupyter.
5. Restart the kernel and run all cells in order.

## Recommendations

Test targeted reminders and reconfirmation for higher-risk
bookings, simplify rescheduling and validate unusual patterns
before using them for operational decisions.

## Author

Shivji  
GitHub: https://github.com/shivjicode
