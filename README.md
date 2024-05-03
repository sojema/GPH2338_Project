# GPH2338_Project 
Predicting Death and Complications after Myocardial Infarction: A Classification Problem
Mykel Miller and Sophie Madjarova

For this project, we used a dataset from the UC Irvine Machine Learning Repository titled “Myocardial infarction complications.” The dataset was collected from 1992 to 1995 in the Krasnoyarsk Interdistrict Clinical Hospital, a hospital in Russia and contains 124 variables and 1700 observations. We will examine a wide range of data, including both continuous variables (such as blood pressure), and categorical variables (such as type of infarction). (UC Irvine Machine Learning Repository https://doi.org/10.24432/C53P5M)

We had two targets for our predictions, myocardial infarction complications and death. To make the MI complications outcome, we grouped the 11 complications into 5 levels of relative severity in terms of mortality associated with each complication. We also consulted with a physician to have an expert opinion and concluded that due to the possibility that a patient may experience several different complications, what mattered most was the most severe complication they experienced. Our final complication groups were, in terms of increasing severity (1 to 5): Post infarction Angina/Dressler Syndrome < AFib/SVT < 3rd degree AV block/Vtach/Vfib/chronic heart failure < PE/relapse MI < Myocardial rupture. For our target variable of death, we also simplified a categorical variable that noted conditions which people died from to a binary variable of if they died or not.

