# Regresión
Este proyecto utiliza la base de datos "student dropout" con el objetivo de aplicar la resolución de problemas, selección de características, regresión lineal, regresión no lineal, así como métricas de error. En este caso se busca tratar de predecir la calificación final de estudiantes de un curso, a partir de su información demográfica y sus calificaciones de los primeros dos periodos. En la base de datos donde podrás encontrar información para 649 estudiantes, con 34 variables en total. Los datos se descargaron de [Kaggle](https://www.kaggle.com/datasets/abdullah0a/student-dropout-analysis-and-prediction-dataset/data).

La base de datos cuenta con la siguiente información:
- School: Name of the school attended (e.g., MS).
- Gender: Gender of the student (e.g., M for Male, F for Female).
- Age: Age of the student.
- Address: Type of residence (U for urban, R for rural).
- Family_Size: Size of the family (GT3 for greater than 3, LE3 for less than or equal to 3).
- Parental_Status: Living arrangement of parents (A for living together, T for living apart).
- Mother_Education: Education level of the mother (0 to 4).
- Father_Education: Education level of the father (0 to 4).
- Mother_Job: Type of job held by the mother.
- Father_Job: Type of job held by the father.
- Reason_for_Choosing_School: Reason for selecting the school (e.g., course).
- Guardian: Guardian of the student (e.g., mother).
- Travel_Time: Time taken to travel to school (in minutes).
- Study_Time: Weekly study hours (1 to 4).
- Number_of_Failures: Number of past class failures.
- School_Support: Whether the student receives extra educational support (yes/no).
- Family_Support: Family provided educational support (yes/no).
- Extra_Paid_Class: Participation in extra paid classes (yes/no).
- Extra_Curricular_Activities: Involvement in extracurricular activities (yes/no).
- Attended_Nursery: Attendance in nursery school (yes/no).
- Wants_Higher_Education: Desire to pursue higher education (yes/no).
- Internet_Access: Availability of internet at home (yes/no).
- In_Relationship: Romantic relationship status (yes/no).
- Family_Relationship: Quality of family relationships (scale 1 to 5).
- Free_Time: Amount of free time after school (scale 1 to 5).
- Going_Out: Frequency of going out with friends (scale 1 to 5).
- Weekend_Alcohol_Consumption: Alcohol consumption on weekends (scale 1 to 5).
- Weekday_Alcohol_Consumption: Alcohol consumption on weekdays (scale 1 to 5).
- Health_Status: Health rating of the student (scale 1 to 5).
- Number_of_Absences: Total number of absences from school.
- Grade_1: Grade received in the first assessment.
- Grade_2: Grade received in the second assessment.
- Final_Grade: Final grade received (G3).
- Dropped_Out: Indicator of whether the student has dropped out (True/False).

Este proyecto incluye los siguientes documentos:
- [Reporte en formato ipynb](./Regresion.ipynb)
- [Reporte en formato html](./Regresion.html)
- [Base de datos](./student.csv)
