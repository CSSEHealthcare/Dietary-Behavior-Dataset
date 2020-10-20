# An Open-Source Dataset on Dietary Behaviors and DASH Eating Plan Optimization Constraints
We consider the diet recommendations problem for prediabetes and hypertension patients to control their blood pressure and their illness progression. The recommendations are provided based on a set of given observations from the food choices of the patients. The observations may be feasible or infeasible for the forward problem with nutritional constraints, which is a common occurrence in a diet application. The goal is to recommend diets to these patients that not only are rich in nutrients but are also palatable to their individual taste and hence, encourage long-term adherence. We emphasize that, depending on the original observations, richness of diets and their palatablility to the individual's taste may be competing objectives, as such, we show how the Inverse Learning methodology can provide reasonable ranges of potentially optimal solutions to handle such a setting. Long-term adherence is one of the main challenges in dieting as healthy diets are often far from the dieter's daily habits and it often proves challenging to change life-style. This challenge is especially costly for chronic patients who may be able to control their condition through dieting, e.g., type II diabetes, prediabetes, and hypertension patients. Providing a diet that is healthy and that considers the life-style, individual preferences, and needs will increase the chances of adherence. 

This repository includes all the data necessary to perform inference analysis for providing personalized diets for patients with different demographics and needs. A set of initial observations of the daily dietary habits of individuals are gathered and curated from the National Health and Nutrition Examination Survey (NHANES) Dietary data [National Health and Nutrition Examination Survey (NHANES) Dietary data](https://wwwn.cdc.gov/nchs/nhanes/Search/DataPage.aspx?Component=Dietary). Additionally, in order to make the inferred diets more tractable, the more than 5000 food groups are bundled into 49 broad food types for ease of interpretations. We also gather and provide food codes fro the [United States Department of Agriculture](https://fdc.nal.usda.gov/) website. 

## Structure of the Repository
Different folders in this repository provide the following data:

[Raw Data](https://github.com/CSSEHealthcare/InverseLearning/tree/master/Raw%20Data): This folder contains Raw data from the NHANES and USDA websites for individual food intakes of patients.

[Samples](https://github.com/CSSEHealthcare/InverseLearning/tree/master/Samples): Samples with specific purposes are gathered in this folder. Samples are generated with consideration to the demographics and previous conditions of the patients.

[Optimization Model Parameters](https://github.com/CSSEHealthcare/InverseLearning/tree/master/Optimization%20Model%20Parameters) : In order to construct a linear optimization problem with the aim of providing optimal diets, the necessary parameters are gathered.

[Code](https://github.com/CSSEHealthcare/InverseLearning/tree/master/code) : Code for a data-driven model for inference of contrained linear programs will be added here.

## Inferrence of Linear Optimization problems
Thew data provided here create a perfect example for constrained inference models. The diet recommendation probem is tangible yet fairly complicated issue because of the presence of many constraints and behavioral factors. However, the results of any inference models on such a problem are relatively easy to interpret. 

## How to Cite This Work
This dataset is intended for educational and research purposes only. Commercial uses are prohibited. If you use our data, please cite:

[An Open-Source Dataset on Dietary Behaviors and DASH Eating Plan Optimization Constraints](https://arxiv.org/pdf/2010.07531.pdf)

@misc{ahmadi2020opensource,
      title={An Open-Source Dataset on Dietary Behaviors and DASH Eating Plan Optimization Constraints}, 
      author={Farzin Ahmadi and Fardin Ganjkhanloo and Kimia Ghobadi},
      year={2020},
      eprint={2010.07531},
      archivePrefix={arXiv},
      primaryClass={math.OC}
}


