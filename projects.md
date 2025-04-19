---
layout: default
title: projects
---

# Technical Projects

<nav class="projects-nav">
  <a href="#python-ml">Python & Machine Learning</a>
  <a href="#r-ds">R & Machine Learning</a>
  <a href="#viz">Tableau Dashboards</a>
  <a href="#portfolio">Portfolio Website</a>
</nav>

---

## <a name="python-ml"></a>Python & Machine Learning





## <a name="r-ds"></a>Data Science Projects in R

### Brain Stroke Prediction

**Tools:** R, dplyr, ggplot2, ROSE, caret  
**Skills Demonstrated:** Data cleaning, class imbalance handling, model comparison, feature importance analysis, binary classification

<div class="justify-text">
  <p><strong>Summary:</strong><br>
  This R-based project focuses on predicting the likelihood of a stroke in patients using demographic and health-related data. The dataset contains 5,110 records and 12 features, including age, glucose levels, BMI, and smoking status. Preprocessing involved handling 210 missing values, encoding categorical variables, and normalizing continuous features. Multiple classification algorithms were used to assess model performance, including logistic regression, decision trees, and random forest classifiers.
  </p>

  <p><strong>Key Insights:</strong></p>
  <ul>
    <li>Initial model performance was hindered by class imbalance, prompting the use of ROSE and a combined under/over sampling strategy for rebalancing.</li>
    <li>Random Forest consistently outperformed Logistic Regression and Decision Tree classifiers under both sampling strategies.</li>
    <li>Feature importance plots from Random Forest highlighted age, glucose level, and hypertension as key predictors of stroke risk.</li>
  </ul>

  <p><strong>Model Performance Comparison:</strong></p>

  <table class="model-table">
    <thead>
      <tr>
        <th>Sampling Technique</th>
        <th>Model</th>
        <th>Accuracy</th>
        <th>Recall</th>
        <th>AUC Score</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>ROSE</td>
        <td>Random Forest (no feature selection)</td>
        <td>0.78</td>
        <td>0.79</td>
        <td>0.794</td>
      </tr>
      <tr>
        <td>Under + Over Sampling</td>
        <td>Random Forest (no feature selection)</td>
        <td>0.916</td>
        <td>0.94</td>
        <td>0.84</td>
      </tr>
    </tbody>
  </table>

  <p><strong>Impact:</strong><br>
  This project demonstrates how machine learning can support early detection of stroke risk factors using health and lifestyle data. It highlights the role of sampling techniques in improving model performance and reinforces the importance of data-driven tools in public health prediction and prevention efforts.
  </p>
</div>

📍 [View Code](https://github.com/sowmyamaddali/DATS6101_Project_Team_Sage)

<br>


## <a name="viz"></a>Data Visualization Projects

### Virginia Air Quality Dashboard

**Tools:**  Excel, Tableau

**Skills Demonstrated:** Data cleaning, visualization design, public health analysis, storytelling

![Virginia Air Quality Dashboard](assets/images/virginia-air-quality-dashboard.png)

<div class="justify-text">
  <p><strong>Summary:</strong><br>
  Built an interactive Tableau dashboard to analyze PM2.5 pollution levels across Virginia using data from the EPA. The dashboard visualizes daily, weekly, and county-level air quality trends, making it easier for policymakers and the public to identify pollution spikes and geographic hotspots.
  </p>

  <p><strong>Key Insights:</strong></p>
  <ul>
    <li>Identified consistent midweek spikes in PM2.5 pollution across multiple counties.</li>
    <li>Found higher pollution levels in urban counties compared to rural areas.</li>
    <li>Enabled interactive exploration of air quality trends by time period and location.</li>
  </ul>

  <p><strong>Impact:</strong><br>
  The dashboard improves public awareness and supports data-driven decisions in environmental planning and health policy.
  </p>
</div>

📍 [View interactive dashboard on Tableau Public](https://public.tableau.com/views/air_quality_workbook_dashboard/VirginiaAirQualityAnalysis2023?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)

<br>


### Measles & Rubella Immunization Activities

**Tools:** Excel, Tableau  
**Skills Demonstrated:** Data preprocessing, trend analysis, interactive dashboard design, public health visualization

![Immunization Dashboard](assets/images/measles-rubella-immunization.png)

<div class="justify-text">
  <p><strong>Summary:</strong><br>
  Built an interactive Tableau dashboard to explore global measles and rubella immunization efforts from 2000 to 2024. The dashboard visualizes coverage trends, regional disparities, and campaign timelines using various interactive charts.
  </p>

  <p><strong>Key Insights:</strong></p>
  <ul>
    <li>Highlighted regions with consistently suboptimal immunization coverage, guiding targeted public health interventions.</li>
    <li>Identified temporal trends in vaccination effectiveness across intervention types and WHO regions.</li>
    <li>Enabled dynamic data exploration through filters and visual drill-downs, improving accessibility and usability of global immunization data.</li>
  </ul>

  <p><strong>Impact:</strong><br>
  The dashboard empowers public health organizations and planners to make informed, data-driven decisions by identifying at-risk populations and optimizing future immunization strategies.
  </p>
</div>

📍 [View interactive dashboard on Tableau Public](https://public.tableau.com/views/Immunization-Activities/Dashboard1?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)

<br>


### Visualizing the History of Global Nuclear Tests (1945–1998)
**Tools:** R, ggplot2, dplyr, lubridate, sf  
**Skills Demonstrated:** Data wrangling, geospatial visualization, time series analysis, historical trend analysis, public data storytelling

![Nuclear Testing Graph](assets/images/nuclear-testing.png)

<div class="justify-text">
  <p><strong>Summary:</strong><br>
  This data visualization project explores the global history of nuclear testing from 1945 to 1998, focusing on tests conducted by the United States and the Soviet Union. Using R, the analysis covers detailed attributes such as geographic location, type, depth, and estimated yield of each test, along with its purpose and responsible organization. The visualizations highlight the escalation of nuclear activity during the Cold War and provide historical context to global arms development and policy shifts.
  </p>

  <p><strong>Key Insights:</strong></p>
  <ul>
    <li>Revealed a concentration of nuclear tests during peak Cold War periods, particularly by the U.S. and USSR between the 1950s and 1980s.</li>
    <li>Identified geographic clustering of test sites (e.g., Nevada and Semipalatinsk), shedding light on strategic testing zones.</li>
    <li>Showed changes in testing methods over time, with shifts from atmospheric to underground testing aligned with evolving international treaties.</li>
  </ul>

  <p><strong>Impact:</strong><br>
  The project provides a historical lens through which researchers, historians, and the public can explore the scale, timing, and geopolitical implications of nuclear weapons testing. It enhances understanding of 20th-century military history through accessible and data-driven visuals.
  </p>
</div>

<br>




## <a name="portfolio"></a>Portfolio Website




[Home](./)
