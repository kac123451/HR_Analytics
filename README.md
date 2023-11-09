# HR_Analytics

In which year of work do people resign most often

Why is that ?
What corelations are between them ?

How can this be changed should we ?

Dataset Source: https://www.kaggle.com/datasets/anshika2301/hr-analytics-dataset

Data lookup
Data has 38 columns
1481 rows (56221 total records)

1. Apply filters, so we can look for any errors or blank rows
2. Sort data for verification (Duplicates)

EmpID                  - (RM001-RM1470)                -  1481 rows so we probably contain some duplicates as this column should has unique EmpID
Age                    - (From 18 to 60)
Age Group              - (5 groups - 18-25, 26-35, 36-45, 46-55, 55+)
Attrition              - (Yes, No)
BusinnessTravel        - (Non-Travel, Travel_Frequently, Travel_Rarely, TravelRarely)       - One of categories names need correction
DailyRate              - (102-1499)
Department             - (3 total - Research & Development, Sales, Human Resources)
DistanceFromHome       - (1-29km)
Education              - (1-5)                                          - We need to make it more understandeble
EducationField         - (6 total - Life Sciences, Medical, Marketing, Technical Degree, Human Resources ,Other)
EmployeeCount          - (all fields has value 1) - To be removed we can count employees using different methods.
EmployeeNumber         - (1-2068)             - This column doesnt tells us much expect EmployeeNumber which wont be much important, we use EmpID for identify
EnviromentSatisfaction - (Scale From 1 to 4) 
Gender                 - (Male, Female)
HourlyRate             - (30 - 100 ($))
JobInvolvement         - (Scale From 1 to 4)
JobLevel               - (1-5)
JobRole                - (9 - Manager, Sales Executive, Laboratory Technician, Healthcare Representative, Manufacturing Director, Research Scientist, Research Director, Sales Representative, Human Resources
JobSatisfaction        - (Scale From 1 to 4)
MartialStatus
MonhtlyIncome
SalarySlab
MonthlyRate
NumCompaniesWorkekd
Over18
OverTime
PercertSalaryHike
PerformaceRating
RelationshipSatisfaction -
StandardHours - 
StockOptionLevel
TotalWorkingYears
TrainingTimesLastYear
WorkLifeBalance
YearsAtCompany
YearsInCurrentRole
YearsSincePromotion
YearsWithCurrManager

Import data into Excel 
