# IT Ticket Analysis (Excel Dashboard)

Excel dashboard analyzing ~97,000 IT support tickets to identify drivers of resolution time, satisfaction, and severity trends.

## Objective
Understand what actually drives customer satisfaction and resolution efficiency in IT support operations, and identify priority areas for investment.

## Approach
- Built a dynamic dashboard using PivotTables and PivotCharts, with slicers connected across all report views
- Analyzed resolution time trends by Request Category (quarter-wise) and by Agent Age Group vs Satisfaction Rate
- Used AVERAGEIFS and TREND functions for subjective analysis on tech investment and employee demographics vs outcomes
- Corrected a distorted agent average age calculation caused by ticket-level weighting

## Key Findings
- Satisfaction scores stay essentially flat (~4.10) across all request categories regardless of resolution time — suggesting **agent communication quality**, not tech investment, is the primary satisfaction driver
- **Hardware** and **System** categories are the top priority areas for resolution efficiency investment

## Files
- `Template (IT Tickets).xlsx` — full dashboard and underlying data
- `IT TICKET ANALYSIS.pptx` — presentation summary of findings

## Tools Used
Excel (PivotTables, PivotCharts, slicers, AVERAGEIFS, TREND)
