# Call Centre Performance Analytics

Power BI project for exploring call handling, resolution, agent activity, and customer satisfaction using a 5,000-record call center dataset.

## Business questions

- How many calls are answered or missed?
- How do resolution outcomes vary by agent and topic?
- When is call demand highest?
- How do answer speed, talk duration, and satisfaction vary across calls?

## Tools and files

**Power BI · Excel · Business intelligence · Data visualization**

| File | Purpose |
| --- | --- |
| `01 Call-Center-Dataset.xlsx` | Call-level source data |
| `PWC Swizerland Dashboard (1).pbix` | Power BI report file |

## Dataset

The workbook contains call ID, agent, date, time, topic, answer status, resolution status, speed of answer in seconds, average talk duration, and satisfaction rating.

## Metric definitions for analysis

| Metric | Definition |
| --- | --- |
| Call volume | Number of call records |
| Answer rate | Answered calls divided by all calls |
| Resolution rate among answered calls | Answered calls marked resolved divided by answered calls |
| Average answer speed | Mean recorded answer speed for answered calls with a valid value |
| Average satisfaction | Mean of available satisfaction ratings; missing ratings are excluded |

These definitions document how to interpret the analysis; check the existing report measures before assuming they use the same denominators.

## Open the report

1. Download both project files.
2. Open the `.pbix` file in Power BI Desktop.
3. If the workbook path cannot be found, update the data source path to the downloaded Excel file.
4. Refresh the report and review its visuals and available filters.

## Interpretation

The dataset supports exploratory comparisons, not proof that staffing or answer speed causes a change in satisfaction. No operational improvements or business impact are claimed without measurement.
