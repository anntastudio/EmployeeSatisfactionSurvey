# EmployeeSatisfactionSurvey
### Project background
The Human Resources team conducted a brief survey to understand what makes employees happy or unhappy at work. Data is collected on work hours, meeting time, sick days, training, and overall satisfaction levels. The goal is to find out what the company can do to make their workplace better for everyone.

### Methodology
* Data source: extract in txt file format
* Tools used: Power Query for data connection, Python in Excel for analysis and visualisation
* Data structure: 150 rows and 10 columns
<img width="300" height="398" alt="image" src="https://github.com/user-attachments/assets/9c8c07d4-24aa-4bd0-877b-09004851ab41" />

### Insights and Recommendation
<img width="2015" height="616" alt="image" src="https://github.com/user-attachments/assets/b8a15fd2-3d11-44eb-a777-544e7d22b60d" />

#### 1. Meeting Hours Negatively Impact Satisfaction:
The correlation heatmap shows a strong -0.77 correlation between meeting hours and employee satisfaction. The middle chart confirms this visually - satisfaction drops sharply as meetings increase. To maintain satisfaction above 9/10, companies should keep meetings under 6 hours per week.
#### 2. Training Drives Performance:
The 3rd chart demonstrates a strong positive relationship (0.78 correlation) between training hours and performance ratings. Employees who complete around 23 hours of training achieve the target performance rating of 9/10. This suggests that investing in employee development directly improves results.
#### 3. The Sick Day Warning Sign:
The heatmap reveals that sick days are strongly correlated with poor training (-0.53) and low performance (-0.73). Employees who receive less training and perform poorly tend to take more sick days, which could indicate disengagement or burnout.
#### 4. Work Hours vs. Meeting Hours:
Interestingly, total work hours show minimal impact on satisfaction (0.09 correlation), while meeting hours have a massive negative impact. This means it's not how much employees work that matters - it's how their time is spent. Too many meetings waste productive time and frustrate employees.
#### Recommendations:
Limit meetings to under 6 hours weekly, increase training opportunities to at least 23 hours, and monitor sick day patterns as an early warning system for employee issues.
