**Project description**

Sepsis is a life-threatening condition caused by an exaggerated reaction of the body to an infection, that leads to organ failure or even death. Since sepsis can kill a patient even in just one hour, survival prediction is an urgent priority among the medical community: even if laboratory tests and hospital analyses can provide insightful information about the patient, in fact, they might not come in time to allow medical doctors to recognize an immediate death risk and treat it properly.

The project aims to understand whether sepsis has some correlation with the variable considered in the project, such as: sex, age and septic episode number. Find all the results in the attached files.

The primary goal of this project is to analyze a dataset containing information on sepsis illness to identify key attributes that contribute to the development and progression of the disease. Additionally, the project aims to uncover trends and survival patterns over time using advanced statistical methods.

I used Logistic Regression to identify the most significant attributes that contribute to the occurrence of sepsis.
Then, I used survivaò analysis to analyze the survival patterns and trends of patients with sepsis over time. Here the two models that I used : Kaplan-Meyer and Cox Model:
- Kaplan-Meier Estimator: This non-parametric statistic was used to estimate the survival function from the lifetime data. It helps in understanding the proportion of patients surviving for a certain amount of time after diagnosis.
- Cox Proportional-Hazards Model: This semi-parametric model was utilized to explore the relationship between the survival time of patients and one or more predictor variables. It allows for the assessment of how different factors impact 
survival rates.
