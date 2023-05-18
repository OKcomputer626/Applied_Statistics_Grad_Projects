# A clinical Trial in the Treatment of Carcinoma of the Oropharynx

![alt pic](https://www.aihr.com/wp-content/uploads/AdobeStock_106755650-Converted.png)

## Survival Analysis

In this collaborative project, my partner and I delved into a subset of data derived from an extensive clinical trial performed by the Radiation Therapy Oncology Group based in the United States. The complete study involved patients suffering from squamous carcinoma across 15 different oral and throat sites. It was a multi-institutional endeavor with 16 different medical research bodies contributing to the study.

However, for the purposes of our research project, we focused solely on the data pertaining to three oropharyngeal sites, specifically those reported by the six largest participating institutions. The patients involved in this clinical trial were assigned randomly to one of two distinct treatment groups. One group underwent radiation therapy in isolation, whereas the second group received a combination of radiation therapy and a chemotherapeutic agent.

The primary objective driving our analysis was to compare and contrast the efficacy of these two different treatment approaches in terms of patient survival rates. We analyzed the data provided in the 'Pharynx.xls' file with the intent to generate meaningful insights about the survival outcomes related to each treatment strategy.

### My Contributions to the project:

* R Programming:
  * ggplot (tidyverse)
  * gt table chart
  * Cox Proportional Hazard function (Survival)
* Report:
  * Abstract
  * Exploratory Analysis
  * Methods
  * Results
  * Conclusion

# Methodology and R Procedures Implemented

## Analysis

* Stepwise Regression and Compare -2logL for each model
* Anova table for full model and the null model
* Test Hypothesis

## Testing for Line Assumptions

* Proportional Hazards Assumption:
  * Check for Pattern on the Schoenfeld residuals
  * log-log survival curve for each variable to be parallel

# Results

The aim of this report is to delve into and contrast the effects of two treatments on patients with pharynx cancer: the first being radiation therapy alone (denoted as 1=standard in our data set), and the second, a combination treatment of radiation therapy with a chemotherapeutic agent (labelled as 2=test in our data set). Based on our analysis, we found that the type of treatment does not notably affect the survival rates of these patients.

It appears that survival outcomes may be more significantly influenced by other factors such as a family history of pharynx cancer or particular dietary habits. Yet, we must underscore the importance of acknowledging the inherent limitations of our model, as well as the constraints of the dataset used in our analysis.

We advocate for further research, using larger and potentially more varied datasets for validation, to enhance the accuracy and expand the applicability of our model in a broader clinical context. 
