# Climate and Agriculture in Pakistan

## Project overview

This project explores climate trends and their relevance to agriculture in Pakistan using publicly available climate data. It documents the data sources, analytical methods, findings, and limitations in a transparent and reproducible way.

The initial analysis examines historical annual average surface air temperature in Pakistan. Future work may explore the relationship between climate trends and agricultural indicators.

## Research question

How have annual average surface air temperatures in Pakistan changed between 1901 and 2025?

## Data source

* **Provider:** World Bank Climate Change Knowledge Portal
* **Dataset:** CRU TS 4.10
* **Geographical coverage:** Pakistan
* **Variable:** `tas` — average surface air temperature
* **Unit:** Degrees Celsius (°C)
* **Temporal resolution:** Annual
* **Period covered:** 1901–2025, as shown in the downloaded file

The data were downloaded through the portal's spatially aggregated data interface. The original downloaded data are preserved in the Excel workbook.

## Methodology

The analysis was conducted in Microsoft Excel.

1. Downloaded the annual temperature time series for Pakistan.
2. Preserved the original data in a separate worksheet.
3. Reshaped the data from wide format into a table with separate date and temperature fields.
4. Created a line chart to visualize year-to-year temperature variation.
5. Calculated and compared the mean annual temperature values for two 30-year periods: 1901–1930 and 1996–2025.

## Preliminary findings
![Annual average surface air temperature in Pakistan, 1901–2025](pakistan_temperature_trend.png)

| Period     | Mean annual temperature |
| ---------- | ----------------------: |
| 1901–1930  |                20.631°C |
| 1996–2025  |                21.621°C |
| Difference |                +0.990°C |

The mean of the annual temperature values in 1996–2025 was approximately 0.99°C higher than in 1901–1930. The time series also displays year-to-year variability alongside an overall upward pattern.

This is a descriptive comparison of two periods. It does not, by itself, establish statistical significance or attribute the difference to a specific cause.

### Long-term temperature trend

A linear regression of annual average surface air temperature for Pakistan over 1901–2025 estimated a warming trend of approximately **0.094°C per decade**. This estimate summarises the linear trend across the study period; it does not establish statistical significance or attribute the observed change to specific causes.

The analysis compares the average temperature in 1901–1930 (20.631°C) with that in 1996–2025 (21.621°C), a difference of approximately **0.990°C** between the two 30-year periods.


## Limitations

* The analysis is based on country-level spatially aggregated data and does not show regional differences within Pakistan.
* The meaning of the `-07` suffix in the downloaded date labels (`YYYY-07`) has not yet been independently verified.
* No statistical trend test or causal attribution analysis has been conducted.
* The analysis does not yet assess agricultural outcomes or establish links between temperature changes and crop yields.

## Files

* `pakistan_temperature_analysis.xlsx` — Excel workbook containing the original data, cleaned data, and temperature chart.

## Next steps

* Verify the date-label convention and document the dataset metadata.
* Assess the long-term temperature trend using a statistical method.
* Explore suitable public agricultural data to investigate potential relationships between climate and agriculture.

## Tools

Microsoft Excel · Data cleaning · Descriptive analysis · Data visualization · Climate research
verified. This analysis is descriptive and does not test statistical significance or attribute the temperature difference to a particular cause.

Tools
Microsoft Excel for data cleaning, descriptive analysis, and visualization.
GitHub for project documentation and version tracking.
Expected Outputs
Documented public data sources.
A structured dataset and analysis workbook.
Charts summarizing selected climate indicators.
A concise research brief discussing findings and limitations.
Limitations

This project is intended as a descriptive analysis. Observed climate trends alone cannot establish their effects on agricultural productivity or farmers' adaptation decisions. Such conclusions would require additional agricultural data and an appropriate analytical design.
