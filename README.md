# Diet Recommendation Problem Data Samples for Constrained Optimization
This repository includes all the data necessary to perform inference analysis for providing personalized diets for patients with different demographics and needs. A set of initial observations of the daily dietary habits of individuals are gathered and curated from the National Health and Nutrition Examination Survey (NHANES) Dietary data [National Health and Nutrition Examination Survey (NHANES) Dietary data](https://wwwn.cdc.gov/nchs/nhanes/Search/DataPage.aspx?Component=Dietary). Additionally, in order to make the inferred diets more tractable, the more than 5000 food groups are bundled into 49 broad food types for ease of interpretations. We also gather and provide food codes fro the [United States Department of Agriculture](https://fdc.nal.usda.gov/) website. 

## Structure of the Repository
Different folders in this repository provide the following data:

[Raw Data](https://github.com/CSSEHealthcare/InverseLearning/tree/master/Raw%20Data): This folder contains Raw data from the NHANES and USDA websites for individual food intakes of patients.

[Samples](https://github.com/CSSEHealthcare/InverseLearning/tree/master/Samples): Samples with specific purposes are gathered in this folder. Samples are generated with consideration to the demographics and previous conditions of the patients.

[Optimization Model Parameters](https://github.com/CSSEHealthcare/InverseLearning/tree/master/Optimization%20Model%20Parameters) : In order to construct a linear optimization problem with the aim of providing optimal diets, the necessary parameters are gathered.

[Code](https://github.com/CSSEHealthcare/InverseLearning/tree/master/code) : Code for a data-driven model for inference of contrained linear programs will be added here.

## Inferrence of Linear Optimization problems
Thew data provided here create a perfect example for constrained inference models. The diet recommendation probem is tangible yet fairly complicated issue because of the presence of many constraints and behavioral factors. However, the results of any inference models on such a problem are relatively easy to interpret. 



