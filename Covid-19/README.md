📊 COVID-19 Impact Analysis: A State-Level Study in India
Project Goal & Business Context
Briefly state the problem or question this analysis addressed: The primary goal was to analyze state-level COVID-19 transmission, recovery, and mortality rates across India to identify regional disparities and evaluate the
effectiveness of localized public health responses.

This project demonstrates an end-to-end analytical workflow, from data extraction to executive reporting, with a focus on Time-Series Analysis and Geographic Data Visualization.

---

🛠️ Technologies & Tools

| Component | Tool Used | File Location |
| :--- | :--- | :--- |
| **Data Storage/Processing** | Spreadsheets (Excel/Google Sheets) | 'data/cleaned_data.csv' |
| **Data Querying** | Basic Filtering/Calculations | Not applicable (Pre-cleaned data used) |
| **Visualization/BI** | Tableau Public Desktop, Visualization | `Covid-19 in India detailed Analysis.twb` |
| **Presentation** | Microsoft365 Powerpoint | **[Link to Explanatory Video/Presentation]** |

---

🔑 Key Insights & Deliverables
1) Insight 1 (Transmission): Identified a [Quantifiable Value, e.g., 30%] higher peak growth rate in new cases in top-tier metropolitan states compared to rural states, suggesting a correlation between population
   density and initial transmission speed.

2) Insight 2 (Impact/Mitigation): Comparative analysis showed that states with a [Quantifiable Value, e.g., 90%+] recovery rate achieved this by [Actionable Result, e.g., an average 15-day shorter case-to-recovery time], 
indicating superior medical resource management.

3) Deliverable: The final interactive Tableau Dashboard can be viewed here: [(https://public.tableau.com/views/Covid-19inIndiadetailedAnalysis/Dashboard1?:language=en-US&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)] 

---

**Project Structure**

| File | Description |
| :--- | :--- |
| `Data_Sources/covid_19_india.csv` | Initial dataset containing state-wise daily case/death/recovery counts. [Link: https://www.kaggle.com/datasets/sudalairajkumar/covid19-in-india] |
| `Data_Sources/StatewiseTestingDetails.csv` | Supplementary dataset used for long-term time-series trend analysis. [Link: https://www.kaggle.com/code/anshuls235/covid19-explained-through-visualizations/data] |
| `Data_Sources/Indian_States.shx` | ESRI Shapefiles for creating the geographic choropleth map visualization in Tableau. [Link: https://www.kaggle.com/datasets/greeshmagirish/indian-states-shapefiles] |
| `Covid-19 in India detailed Analysis.twb` | The Tableau Packaged Workbook file, including the final data model, calculated fields, and dashboard layout. |
| `Visualizations/Covid-19_Analysis_India.png` | A static image of the final dashboard for quick viewing embedded in this README. |





