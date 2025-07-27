Dataset Description:

Hours_Studied:  Number of hours spent studying per week.

Attendance:     Percentage of classes attended.

Parental_Involvement;	Level of parental involvement in the student's education (Low, Medium, High).

Access_to_Resources:	Availability of educational resources (Low, Medium, High).

Extracurricular_Activities:	Participation in extracurricular activities (Yes, No).

Sleep_Hours:	Average number of hours of sleep per night.

Previous_Scores:	Scores from previous exams.

Motivation_Level:	Student's level of motivation (Low, Medium, High).

Internet_Access:	Availability of internet access (Yes, No).

Tutoring_Sessions:	Number of tutoring sessions attended per month.

Family_Income:	Family income level (Low, Medium, High).

Teacher_Quality:	Quality of the teachers (Low, Medium, High).

School_Type:	Type of school attended (Public, Private).

Peer_Influence:	Influence of peers on academic performance (Positive, Neutral, Negative).

Physical_Activity:	Average number of hours of physical activity per week.

Learning_Disabilities:	Presence of learning disabilities (Yes, No).

Parental_Education_Level:	Highest education level of parents (High School, College, Postgraduate).

Distance_from_Home:	Distance from home to school (Near, Moderate, Far).

Gender:	Gender of the student (Male, Female).

Exam_Score:	Final exam score.

Overview on what i do to build this model:
1- import suitable libraries
2- check if data contain null values or duplicates 
3- drop null values
4- checking about outliers then removing them
5- changing categorical data to numerical data type by using LabelEncoder
6- Using Linear Regression Algorithm because the target column is contiunes not binary[0 or 1]
7- build system prediction only to test my model response
8- Try Polynomial Regression
