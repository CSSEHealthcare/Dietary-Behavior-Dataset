# Diet Recommendation Problem Data Samples for Constrained Optimization
This repository includes all the data necessary to perform inference analysis for providing personalized diets for patients with different demographics and needs. A set of initial observations of the daily dietary habits of individuals are gathered and curated from the National Health and Nutrition Examination Survey (NHANES) Dietary data [National Health and Nutrition Examination Survey (NHANES) Dietary data](https://wwwn.cdc.gov/nchs/nhanes/Search/DataPage.aspx?Component=Dietary). Additionally, in order to make the inferred diets more tractable, the more than 5000 food groups are bundled into 49 broad food types for ease of interpretations. We also gather and provide food codes fro the [United States Department of Agriculture](https://fdc.nal.usda.gov/) website. 

## Structure of the Repository
Different folders in this repository provide the following data:

[Raw Data](https://github.com/CSSEHealthcare/InverseLearning/tree/master/Raw%20Data): 
This repository contains Raw data from the NHANES and USDA websites for individual food intakes of patients 
## Inferrence of Linear Optimization problems

In order for the input food data to be tractable, a new categorization of foods was provided based on the first two digits of each item's USDA food code. This new categorization greatly reduced the dimension of the problem. The same data bank was used to set up nutrient constraints by selecting a representative food for each category (for example branded milk for category 11) and recording the per serving nutrients of that representative.
