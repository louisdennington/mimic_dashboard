# mimic_dashboard







UMAP projection of diagnosis categories
- Map ICD chapters to 2D space using UMAP, possibly based on co-occurrence or outcome patterns.

Diagnosis vs. Outcomes Heatmap
- Rows = ICD-10 chapters
- Columns = Outcomes (e.g. death, ICU, length of stay, etc.)
- Color = Strength of association (e.g. standardized rate, effect size, or odds ratio)

Stratification Plots
- Bar/violin/histogram plots stratified by:
Gender
Race
Age group
Insurance / SES indicators if available

Vitalsign Time Series (Interactive Line Chart)
- x-axis = Time
- y-axis = Standardized vital signs
- Lines = Colour-coded by diagnosis supercategory
- Tooltip to show values per time-point


Risk statistics for adverse outcomes by diagnostic group
- above average hospital stay
- mortality
- admission