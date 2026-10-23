# IT Ticket Analysis – Excel Dashboard

## Problem Statement
Analyze the IT support ticket management system to understand the performance of IT agents, the efficiency of ticket resolution, and the satisfaction levels of employees. The analysis aims to identify high and low performers among IT agents, assess the overall effectiveness of the team, and find areas for improvement in the ticket resolution process. The ultimate goal is to support informed staffing decisions, including hiring, firing and training, to improve service quality and team performance.

## Dataset
97,498 support tickets with these fields: Request Category, Issue Type, Severity, Priority, Resolution Time (Days), Satisfaction Rate, Agent Age, Age Group.

## Tools & Techniques
- Excel PivotTables and PivotCharts
- Slicers connected to all pivots for dynamic filtering
- AVERAGEIFS and TREND formulas
- Data cleaning and dashboard design

## Dashboard
<img width="1548" height="724" alt="image" src="https://github.com/user-attachments/assets/7fe1c9fe-bc11-4400-95be-2bec1fdfd8ce" />


## Key Insights
- The team handled 97,498 tickets with a satisfaction score of 4.1 out of 5.
- Ticket volume rises year over year, with a sharp jump in 2019–2020.
- Hardware and System issues take 6–8 days to resolve, while Login Access is fixed in under a day.
- Resolution times are consistent across all four quarters: stable, but with no improvement over time.
- Employees aged 41–50 are the most satisfied (4.22). The 31–40 group is the least satisfied (4.03).
- Most tickets are Normal to Major severity, with very few urgent ones.
- Satisfaction drops as priority level rises, so the team struggles more with urgent tickets.

## Conclusion
The team is performing well overall. To support future growth, it should scale resources, reduce Hardware resolution time, and improve how it handles high-priority tickets.

## Files
- `IT_Tickets_Analysis.xlsx` – data cleaning, aggregations, pivot tables, dashboard
- `IT_Tickets_QnA.docx` – answers to the subjective and objective questions
- `IT_TICKET_Presentation.pptx` – summary of insights and recommendations
