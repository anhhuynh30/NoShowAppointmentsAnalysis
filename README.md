# NoShowAppointmentsProject
The aim of the project is to find the meaningful insights of the crucial factors that have strong impact on the patient's decisions on whether to present or absent for their medical appointments.

The dataset no_show_appointments_2016 includes information from 110 527 medical appointments in Brazil in 2016 with 14 associated variables (characteristics). With these characteristics, we can generate useful insights to predict if a patient will show up for their scheduled appointment, and also to understand the common reasons why the patients decided to not show up.

The followings are the details of 14 variables in the dataset [No-show Appointments](https://www.kaggle.com/joniarroba/noshowappointments):

01 - PatientID: Identification of a patient

02 - AppointmentID: Identification of each appointment

03 - Gender: Male or Female

04 - ScheduledDay: The day the patient called or registered the appointment (happens before the appointment)

05 - AppointmentDay: The day of the actual appointment, when the patient has to visit the doctor

06 - Age: How old the patent is

07 - Neighbourhood: The location of the hospital

08 - Scholarship: True or False. Indicating whether or not the patient is enrolled in Brasilian welfare program [Bolsa Família](https://en.wikipedia.org/wiki/Bolsa_Fam%C3%ADlia)

09 - Hipertension: True or False. Indicating whether or not the patient has high blood pressure [Hypertension](https://www.cdc.gov/bloodpressure/about.htm#:~:text=High%20blood%20pressure%2C%20also%20called,blood%20pressure%20(or%20hypertension))

10 - Diabetes: True or False. Indicating whether or not the patient has high blood sugar/glucose [Diabetes](https://www.niddk.nih.gov/health-information/diabetes/overview/what-is-diabetes#:~:text=Diabetes%20is%20a%20disease%20that,to%20be%20used%20for%20energy.)

11 - Alcoholism: True or False. Indicating whther or not the patient has the addiction to alcohol [Alcoholism](https://en.wikipedia.org/wiki/Alcoholism)

12 - Handcap: True or False. Indicating whether or not the patient is handicap

13 - SMS_received: 1 or more messages sent to the patient

14 - No-show: Yes or No. 'Yes' if the patient did NOT show up. 'No' if the patient showed up for the appointment


### To generate meaniful insights into the dataset, I will apply my data analysis skills and knowledge that I have learned so far to find answers for these following questions:
- **Q1:** Which gender (M/F) accounts for more absent appointments?
- **Q2:** How long in average does it take between the ScheduledDay and AppointmentDay? Does the length of the waiting period affect the patient's decisions of being absent for their medical appointments?
- **Q3:** Which age range has the highest percentage for absent appointments?
- **Q4:** How does the distribution of absent appointments in different neighbourhood look like? Which are the top 3 neighbourhood with absent appointments?
- **Q5:** How do other factors (scholarship, hypertension, diabetes, alcoholism, handicap) affect to the present/absent rate of the patients?
- **Q6:** Would sending SMS messages to the patients influence the present/absent rate of the patients?
