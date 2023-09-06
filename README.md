## GMLOS
This work intend to answering the question “How well do DRG-predicted LOS values match actual values? Do any factors explain significant variability in the closeness of these values?”   
We investigated how DRG-predicted Length of Stay (LOS) compares with actual LOS. Findings show certain DRGs, particularly those with shorter expected stays, align better with predicted GMLOS. Key influencers include MDC codes, age, and recent hospital visits. Older patients are less likely to meet the GMLOS. Newborns often meet GMLOS, but mental health patients don't. Without complications, patients might overstay, possibly because GMLOS considers complications. We used visualizations, logistic regression, decision trees, and random forest models for insights.

### Exploratory Data Analysis
Analysis began with database exploration, using Python for data transformation. Calculations included actual LOS, patient age, and previous hospital visits. We analyzed encounter length distribution, focusing on the binary metric of meeting Medicare GMLOS. Using PowerBI, we created a dashboard, noting that return visitors and those aged 20+ have decreasing GMLOS alignment.

### Statistical and Machine Learning Modelling
We used various models to predict GMLOS adherence. Our logistic regression showed 59.1% accuracy. A decision tree model reached 59.26% accuracy, a gradient boosted classifier was at 59.48%, and our best-performing random forest model achieved 59.5%.

### Concluding Remarks
Our tools help identify patients likely to exceed GMLOS, aiding healthcare professionals in improving patient care and hospital outcomes.
