# Project Documentation: HR Workforce Analytics Dashboard

## 1. Project background

This project explores how workforce information can be summarized and presented through an interactive Excel dashboard. It was completed as a guided learning project to practise Excel reporting, chart selection, and dashboard design.

## 2. Objectives

- Summarize workforce information using KPI cards and charts.
- Present several workforce dimensions in a single dashboard.
- Allow users to explore the available metrics using filters/slicers.
- Practise dashboard layout, visual hierarchy, and report usability.

## 3. Dataset overview

- **Workbook source sheet:** `Data`
- **Records:** 100 employee records (one row per employee in the supplied workbook, subject to source definitions)
- **Fields:** 21 columns
- **Unique employee IDs:** 100 in the supplied data sheet
- **Source and license:** Not yet verified; add the original source URL and license information before public distribution.

Fields include employee ID, full name, gender, age, age range, region, job title, department, manager/supervisor, hire date, employment status, work location, salary, pay grade, bonus/allowances, insurance details, leave taken, performance rating, training programs attended, skills, and certifications.

## 4. Workbook structure

### Dashboard

The main presentation sheet. It combines KPI cards, charts, category summaries, and interactive filters. The supplied screenshot shows selected filters, so the visible figures represent a filtered subset rather than necessarily the full workforce.

### Data

The employee-level source records used by the workbook.

### Pivot

Supporting PivotTables and calculations that feed dashboard visuals and summaries.

## 5. Dashboard components

- **Employee overview:** Employee count and performance-rating summary.
- **Employment status:** Full-time, part-time, and contract categories.
- **Gender distribution:** Employee distribution by gender.
- **Salary by job role:** Salary values summarized by role; verify the aggregation in the workbook before describing them as averages or medians.
- **Work location and region:** Distribution across the available location categories.
- **Leave tracking:** Leave values summarized by the categories available in the source.
- **Age range and skills:** Distribution across the recorded groups.

## 6. KPI definitions and validation

The exact calculation should be verified in the workbook before publishing numerical claims.

| KPI | Intended meaning | Validation note |
|---|---|---|
| Total Employees | Count of employee records or distinct employee IDs | Confirm whether the KPI is filtered and whether distinct IDs are counted. |
| Average Performance Rating | Mean of valid performance ratings | Confirm blanks and non-numeric values are excluded appropriately. |
| Full-Time Employees | Count of records classified as full-time | Check that employment categories reconcile to the filtered employee total. |
| Part-Time Employees | Count of records classified as part-time | Check the filter context and category labels. |
| Contract Employees | Count of records classified as contract | Check the filter context and category labels. |
| Salary by Job Role | Salary summarized by role | Confirm whether the displayed values are average, median, or another aggregation. |

Do not treat the preview's displayed KPI values as overall dataset totals: the screenshot contains active filter selections.

## 7. Design choices

The dashboard uses a dark background with high-contrast yellow accents, KPI cards, and grouped visual sections. The design aims to provide a single-screen summary of workforce categories and allow users to explore filtered subsets.

Potential improvements for a future iteration include reducing decorative clutter, increasing the readability of small chart labels, clarifying chart titles and units, and validating KPI definitions and aggregations.

## 8. Observations and interpretation

This documentation describes the dashboard's components rather than asserting workforce findings. Before adding analytical conclusions, inspect the unfiltered data and validate each figure against the supporting PivotTables. For each finding, record:

1. the observed pattern;
2. the relevant metric and comparison;
3. the filter context and sample size;
4. limitations or alternative explanations; and
5. any follow-up question the data cannot answer.

## 9. Limitations

- The dashboard is descriptive and does not establish causal relationships.
- The dataset contains 100 employee records, so some subgroup comparisons may be based on small counts.
- The source provenance and redistribution license have not yet been verified.
- Some metric definitions and aggregations should be confirmed directly in the workbook before external use.
- The supplied dashboard screenshot shows active filters.

## 10. Learning outcomes

This guided project provided practice with Excel dashboard layout, PivotTables/PivotCharts, KPI presentation, interactive filters, chart formatting, and organizing a report for exploration.

## 11. Attribution and references

- **Dataset creator/source:** Add name and URL.
- **Dataset license/permission:** Verify and record before publishing the workbook publicly.
- **Tutorial/project guide:** Add title and URL.
