🏥 Medical Appointments No-Show Analysis
📘 Overview

This project analyzes a dataset of medical appointments to understand why some patients don’t show up for their appointments.
The analysis focuses on identifying key factors that affect patient attendance using Python and pandas.

📂 Dataset

Source: Kaggle – Medical Appointment No Shows
File Used: noshowappointments.csv

Key Columns:

PatientId – Unique patient identifier

AppointmentID – Appointment reference number

Gender – Male/Female

ScheduledDay – When the appointment was booked

AppointmentDay – When the appointment actually happened

Age – Age of the patient

Neighbourhood – Location of the appointment

Scholarship – Whether patient has a scholarship (0 = No, 1 = Yes)

Hipertension, Diabetes, Alcoholism – Health indicators

No-show – Target column (Yes = Did not show up, No = Showed up)



🧰 Tools & Libraries

Python 🐍

Pandas 🧾

Matplotlib 📊

Seaborn 🎨

NumPy 🔢



📊 Project Steps

Data Loading – Import CSV into pandas DataFrame.

Data Cleaning – Handle nulls, convert date columns, fix formats.

Feature Engineering – Extract date parts, calculate waiting days, etc.

Exploratory Data Analysis (EDA) – Visualize trends, outliers, and patterns.

Insights – Identify which factors influence patient attendance.



📈 Key Insights

Age and waiting days play a major role in attendance.

Patients with chronic diseases (like hypertension) tend to attend more regularly.

SMS reminders alone don’t always guarantee attendance.


📦 Medical_Appointments_No_Show
 ┣ 📜 Medical_Appointments_no_show(Task1).ipynb
 ┣ 📜 noshowappointments.csv
 ┗ 📜 README.md
