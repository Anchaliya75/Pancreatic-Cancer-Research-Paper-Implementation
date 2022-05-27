# Pancreatic-Cancer
## What is Cancer?
A Disease in which cell grow out of control and continue to divide.Pancreatic Cancer(Pancreatic Adinocarcinoma) is one of the most lethal cancer with 5 year survival rate of only 11%. The main cause of poor survival is poor prognosis(early diagnosis),As in early stage most of the patients are asymptomatic hence it is very hard to detect.
To know more about cancer See this amazing video https://www.youtube.com/watch?v=WPgJafGz4fg
# Research Paper
## https://www.sciencedirect.com/science/article/pii/S0092867411015145
Pancreatic cancer is a leading cause of cancer-related death,Paper investigated pancreatic cancer survival with the comprehensive data of 101 patients which have autopsies(death).For my curiosity I tried to analyze survival rate of these patients using parametric and  non parametric survival analysis tests
and checked the results given in the literature.Secondly I tried to predict the survival of patients in days after diagnosis of these patients using certain characterstics of person and Cancer using Xgboost and Regression techniques
# Info regarding files
* pancreatic_cancer_survival.ipynb contains survival analysis
* Pancreatic_Cancer_Model_Prediction.ipynb contains prediction of various model
# Dataset Info 
Dataset contains 24 columns and 101 rows.Each row is a patient with all data regarding cancer from diagnosis to death
These 24 columns are as follows
Dx.Age -> Age of patient at the time of diagnosis
* Dx.Date -> Date Of Diagnosis
* Dx.SzPrim.cm->Size of primary tumor at diagnosis
* Dx.WasPrimExcis->Was primary surgically removed?
* Dx.SzMetsLargest.cm ->Size of Largest Measured Metastasis
* Dx.SzMetsRange.cm ->Size Range of Metastasis (cm)
* RPP.remark ->Recurrence within Remnant Pancreas (if has tumor removed) or documented increase in size of unresectable pancreatic mass before death?
* RPP.Date ->Date that recurrence/ progression in pancreas first documented
* RPP.SzPanc.cm->Size of Mass in Pancreas (cm)
* MR.remark ->Metastatic Recurrence (or new metastases) after Initial Diagnosis?
* MR.Date ->Date that metastases first documented
* MR.SzMetsLargest.cm->Size of Largest Measured Metastasis (cm)
* MP.remark ->Progression of Metastases previously documented (initial diagnosis or afterwards)?
* MP.Date ->Date of Documented Progression of Metastases after first found?
* MP.SzMetsLargest.cm ->Size of Largest Measured Metastasis (cm)
* Aut.DateDeath -> Date of Death
* Aut.Panc ->Findings in Pancreas at Autopsy
* Aut.SzReTumorPanc->Size of Recurrent Tumor in Pancreas
* Aut.SzPrim.cm ->Size of Primary at Autopsy (cm)
* Aut.MetsBurden ->Metastatic Burden at Autopsy
* Aut.MeanSzMets.cm ->Mean Size of Metastases (cm)
* Aut.SzMetsRange.cm ->Range of Metastases (cm)
* Aut.minSzMetsRange.cm ->Min Size Of Metastases(cm)
* Aut.maxSzMetsRange.cm ->max Size Of Metastases(cm)
* timeline ->Difference between Date Of Dignostic and date Of Death
* Result->Whether alive or dead as all are dead hence all are 1 useful in Survival Models
# Survival Analysis
Survival Analysis is used to estimate the lifespan of a particular population under study. It is also called ‘Time to Event’ Analysis as the goal is to estimate the time for an individual or a group of individuals to experience an event of interest. This time estimate is the duration between birth and death events[1]. Survival Analysis was originally developed and used by Medical Researchers and Data Analysts to measure the lifetimes of a certain population[1]. But, over the years, it has been used in various other applications such as predicting churning customers/employees, estimation of the lifetime of a Machine, etc. The birth event can be thought of as the time of a customer starts their membership with a company, and the death event can be considered as the customer leaving the company.
To know more about Survival Analysis Use this blog https://towardsdatascience.com/survival-analysis-part-a-70213df21c2e

#### If you have any doubts regarding this Project ,raise issues or mail me at yashanchaliya2000@gmail.com
