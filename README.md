#Investigate-a-Dataset-No-Show-Appointment

This project investigates a dataset of medical appointments in Brazil, focusing on the characteristics of patients and their attendance or absence from scheduled appointments. The dataset, collected in May/June 2016, contains information about 110,000 appointments and consists of 14 unique variables.

Table of Contents
Introduction
Data Wrangling
Exploratory Data Analysis
Conclusion


Introduction
The dataset used for this project was collected from Kaggle and provides valuable insights into the factors influencing patient attendance at medical appointments. The variables in the dataset include:


PatientId: Identification of a patient

AppointmentID: Identification of each appointment

Gender: Male or Female

ScheduledDay: The day the patient set up their appointment

AppointmentDay: The day of the actual appointment

Age: Age of the patient

Neighbourhood: Location of the hospital

Scholarship: Medical scholarship (True or False)

Hypertension: Presence of hypertension (True or False)

Diabetes: Presence of diabetes (True or False)

Alcoholism: Presence of alcoholism (True or False)

Handicap: Presence of a handicap (True or False)

SMS_received: Number of messages sent to the patient

No-show: Attendance status of the patient (Yes or No)


Data Wrangling
In this section, the dataset was cleaned and prepared for analysis. Any missing values, duplicates, or inconsistencies were addressed to ensure the accuracy of the findings.


Exploratory Data Analysis
The exploratory data analysis aimed to uncover patterns and relationships within the dataset. The following key questions were investigated:

What is the ratio of patient attendance?

The dataset revealed that 22,316 patients were absent while 88,203 patients attended their appointments. This information provides insights into the overall attendance rate.
Is waiting time affecting patient attendance?

An analysis of waiting time showed that approximately 85% of patients had to wait between 0 and 29 days. Furthermore, it was observed that waiting time had a minor effect on patients waiting for more than 60 days.
Does age affect patient attendance?

The analysis indicated that patients aged between 40 and 60 had fewer absences compared to other age groups. This finding suggests that individuals in this age range, which represents the beginning of old age, may have higher health concerns.
Does gender affect patient attendance?

The dataset revealed that females accounted for 65% of appointments, while males accounted for 35%. Furthermore, it was observed that females had a higher attendance rate compared to males, indicating a correlation between gender and appointment attendance.
Does having a scholarship affect patient attendance?

The analysis showed no significant impact of scholarships on patient attendance.
Does receiving SMS messages affect patient attendance?

The analysis revealed no significant impact of SMS messages on patient attendance.


Conclusion
In conclusion, this project investigated a dataset of medical appointments in Brazil, exploring various factors that may influence patient attendance. The findings suggest that age, gender, and waiting time play a role in appointment attendance, while scholarships and SMS reminders showed no significant impact.

Please refer to the Jupyter Notebook or Python script in this

