# Project 1 - Investigate a Dataset:

This project explores medical appointment no-shows, in an attempt to identify the variables that may help in predicting future no-shows. Medical appointment no-shows affect the delivery, cost of care and resource planning for medical professionals globally. In this notebook, will attempt to gather insights into the data surrounding no-shows for medical appointments and explore the question: which factors are important to take note of when trying to predict a no-show?

## Dateset
The project explores approximately 110,000 and its 14 associated variables, gathered from Brazil's Bolsa Família welfare program, which can be found [here](https://www.kaggle.com/joniarroba/noshowappointments).

The variables provided in the dataset are as follows:
- AppointmentID: Identification of each appointment
- Gender: Male or Female
- ScheduledDay: The day the appointment was was made
- AppointmentDay: The actual appointment day
- Age: patient age
- Neighbourhood: Neighbourhood where of the appointment
- Scholarship: True or False; refers to a patient’s enrolment in the Brazilian Government healthcare programme; Bolsa Família
- Hipertension: True or False
- Diabetes: True or False
- Alcoholism: True or False
- Handcap: True or False
- SMS_received: True or False, if one or more messages has been sent to the patient
- No-show: True or False

## Summary of findings 
The analysis found that the variables: age, neighbourhood, hypertension, handicap, diabetes, handicap, SMS received, and number of days wait may be more useful to in predicting patient no-shows. Other variables such as gender, alcoholism and the day of the medical appointment do not seem to be as important when trying to predict no-shows in the medical appointments
