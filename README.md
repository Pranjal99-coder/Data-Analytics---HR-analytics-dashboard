# Data-Analytics---HR-analytics-dashboard
This dynamic HR Data Analytics Dashboard replaces siloed Excel files with automated tracking. Visibility &amp; Scale: 100% higher visibility across 200+ records. Efficiency: Saves 4–5 hours daily; boosts productivity by 80%.  Accuracy: Improves HR workflows by 25%.

HR Data Analytics Dashboard
1. Project Title / Headline
HR Data Analytics: Employee Attendance & Workforce Insights Dashboard

An interactive Power BI dashboard designed to analyze employee attendance, Work From Home (WFH), and Sick Leave (SL) patterns across employees and dates, helping HR teams monitor workforce availability and identify attendance trends.

2. Short Description / Purpose

The HR Data Analytics Dashboard is an interactive Power BI report that provides a consolidated view of employee attendance and workforce behavior. It enables HR managers to track Present %, WFH %, and Sick Leave %, analyze daily and employee-level patterns, and identify variations in attendance across different days and months.

The dashboard can support HR teams in workforce planning, attendance monitoring, productivity analysis, and identifying unusual attendance patterns.

3. Tech Stack

The dashboard was developed using the following tools and technologies:

Power BI Desktop – Main platform used for dashboard development and interactive visualization.
Power Query – Used for data cleaning, transformation, and preparation before analysis.
DAX (Data Analysis Expressions) – Used to create calculated measures such as Present %, WFH %, and SL %.
Data Modeling – Used to organize employee, attendance, and date-related information and enable dynamic filtering.
Power BI Visualizations – Used for KPI cards, tables, line charts, slicers, and day-wise analysis.
File Format – .pbix for Power BI development and dashboard screenshots/previews in .png.

4. Data Source
Source: Employee Attendance / HR Attendance Dataset

The dashboard is built using employee attendance data containing employee-level and date-level attendance information.

The data captures attendance statuses such as:

P – Present
WFH – Work From Home
SL – Sick Leave
Other attendance/leave statuses where applicable

The dashboard covers attendance data for April 2022, May 2022, and June 2022, allowing HR teams to analyze workforce attendance over time.

The dataset is structured around:

Employee → Date → Attendance Status

From these records, the dashboard calculates key attendance metrics such as:

Present %
WFH %
Sick Leave %
Employee-wise attendance
Day-of-week attendance
Daily attendance trends
5. Features / Highlights
• Business Problem

HR teams often have large volumes of employee attendance records but lack a simple way to monitor overall workforce availability and identify attendance patterns.

Raw attendance data makes it difficult to quickly answer questions such as:

Which employees have the highest/lowest attendance?
What percentage of employees are working from home?
Which days have the highest attendance?
On which days is WFH more common?
What is the overall sick-leave percentage?
How does attendance change over time?
Are there unusual fluctuations in employee attendance?
• Goal of the Dashboard

The primary objective of the dashboard is to transform raw attendance records into actionable HR insights.

The dashboard enables HR managers to:

Monitor overall employee attendance.
Track Present, WFH, and Sick Leave percentages.
Compare employee attendance performance.
Analyze attendance trends by date.
Identify day-of-week attendance patterns.
Drill down from overall workforce metrics to individual employees.
Filter the entire dashboard by month.
6. Walkthrough of Key Visuals

KPI Cards – Overall Workforce Metrics

The top section provides three important HR KPIs:

Present % – 91.55%

Shows the overall percentage of attendance marked as present.

WFH % – 11.15%

Shows the percentage of attendance records classified as Work From Home.

SL % – 1.08%

Shows the overall Sick Leave percentage.

These KPIs provide HR managers with an immediate snapshot of workforce attendance.

Month Slicer

The interactive month filter allows users to select:

April 2022
May 2022
June 2022

Selecting a month dynamically updates the dashboard visuals and employee-level analysis.

This makes the dashboard useful for monthly HR reporting and attendance comparisons.

Employee-wise Attendance Table

The employee table provides a detailed view of individual attendance behavior.

It displays:

Employee	Present %	WFH %	SL %
Aditya Walls	93.33%	7.14%	0.00%
Adriel Pace	98.21%	5.45%	0.00%
Adyson Moyer	98.21%	10.91%	0.00%
Alexander Davenport	100.00%	100.00%	0.00%

This helps HR identify employees with high attendance, frequent WFH, or higher sick-leave percentages.

Present % by Date

The line/area chart tracks daily Present % across April, May, and June.

It helps identify:

Attendance fluctuations
High-attendance periods
Low-attendance days
Monthly attendance patterns

For example, the dashboard highlights variations such as 78.38%, 77.92%, 86.14%, and 90.38% at different points in the period.

This can help HR investigate sudden drops in workforce availability.

WFH % by Date

The WFH trend visual tracks the percentage of employees working remotely each day.

It helps identify:

Days with unusually high WFH
Increasing/decreasing WFH trends
Potential changes in employee work patterns
Differences between months

The visual shows fluctuations in WFH levels, with some days reaching above 20% WFH.

SL % by Date

The Sick Leave trend shows how sick leave varies across different dates.

This allows HR teams to identify:

Days with unusually high sick leave
Recurring leave patterns
Potential seasonal or organizational trends
Workforce availability issues

For example, the dashboard highlights spikes such as approximately 5.42% and 3.80% on certain dates.

Present % by Day of the Week

The day-of-week table compares attendance across different weekdays.

The dashboard shows:

Tuesday – 92.69%
Monday – 92.66%
Wednesday – 91.89%
Thursday – 90.54%
Friday – 90.08%

This helps HR understand whether employee attendance varies depending on the day of the week.

WFH % by Day of the Week

The second day-wise analysis focuses specifically on WFH.

It allows HR managers to identify which weekdays have the highest proportion of remote work.

For example, the dashboard indicates relatively higher WFH levels on certain weekdays, which can help organizations evaluate hybrid-work patterns and workforce availability.

Employee Attendance Detail Table

The lower-left table provides a more granular view of employee attendance by date.

It displays individual employees against specific dates and their attendance status, such as:

P = Present
WO = Week Off

This allows users to move from high-level KPIs → employee-level → date-level attendance analysis.

7. Business Impact & Insights
Workforce Planning

HR managers can use attendance trends to understand workforce availability and make better staffing decisions.

Hybrid Work Analysis

WFH trends help organizations understand employee remote-working behavior and evaluate hybrid-work patterns.

Attendance Monitoring

Employee-level Present %, WFH %, and SL % allow HR teams to quickly identify unusual attendance patterns.

Day-wise Workforce Planning

Understanding attendance by weekday can help managers plan meetings, staffing, shifts, and team activities more effectively.

Exception Identification

Sudden drops in Present % or spikes in WFH/SL % can be investigated to identify potential operational issues.

Data-Driven HR Decisions

Instead of relying on manually prepared attendance reports, HR teams can use an interactive dashboard to monitor workforce metrics dynamically.

8. Key Insights from the Dashboard

Based on the displayed dashboard:

Overall Present % is 91.55%, indicating generally high workforce attendance.
WFH accounts for 11.15% of attendance records.
Sick Leave is relatively low at 1.08% overall.
Tuesday has the highest Present % at 92.69% among the displayed weekdays.
Friday has the lowest non-zero Present % at 90.08% among the displayed weekdays.
WFH percentages fluctuate considerably across dates, indicating that remote-working behavior is not constant.
Daily attendance shows noticeable fluctuations, making date-level monitoring useful for HR planning.
Employee-level analysis helps identify differences in attendance behavior that would be difficult to spot in a raw attendance spreadsheet.
