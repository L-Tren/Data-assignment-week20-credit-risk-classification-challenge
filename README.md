# Data-assignment-week20-credit-risk-classification-challenge

## Credit Risk Analysis Report


### Overview of Analysis Purpose. 

The purpose of the analysis of is to use supervised machine learning for binary loan classification using a regression model. This model reads the csv data which is then trained and tested to be able to make predictions. There would be many real world applications of such a model, whereby lenders would be able to quickly and efficiently use historical borrower information to identify the creditworthiness of applications made by those borrowers.


### Describe the accuracy, precision, and recall scores of the machine learning model.
- **Accuracy**: The accuracy score is 99.18% (rounded). The loan status accuracy calculated by the model was therefore extremely strong.
- **Precision**: For loan status 0, the precision is 100%. The model is therefore extremely precise in determing if a loan is healthy as per the homework instructions. Alternatively for loan status 1 whereby there is a high risk of defaulting, the precision is less precise at only 85%. This indicates that the model's prediction is correct approximately in 85% of cases of this type of loan status. The macro average is 92% (across all classes) and weighted average is 99% (weighted by class number)
- **Recall**: For healthy loans (class 0), the recall is approximately 99%. This indicates the model correctly identifies 99% of instances where the loan was healthy. For high risk of loans defaulting, the recall is approximately 91%. This indicates that the model correctly identifies  91% of the instances where the loan was at high risk of defaulting. The macro average is 95% (across all classes) and weighted average is 99% (weighted by class number)


### Summarise the results from the machine learning model. Include your justification for recommending the model for use by the company. If you don’t recommend the model, justify your reasoning. 

The machine learning model had high levels of accuracy (99%), precision (99% weighted average), and recall (99% weighted average) as per the above analysis. I would recommend the model to the peer-to-peer lending services company quickly and efficiently identify the creditworthiness of borrowers.


## References

OpenAI. (2024). ChatGPT [Computer software]. Retrieved 12 May 2024 (https://chat.openai.com/)

University of Adelaide. (2024). Predicting Bank Customers - Solution. Retrieved May 12, 2024, from https://git.bootcampcontent.com/University-of-Adelaide/UADEL-VIRT-DATA-PT-12-2023-U-LOLC/-/blob/main/20-Supervised-Learning/2/Activities/08-Stu_Predicting_Bank_Customers/Solved/predicting_bank_customers_solution.ipynb?ref_type=heads

University of Adelaide. (2024). Predicting Default - Solution. Retrieved May 12, 2024, from https://git.bootcampcontent.com/University-of-Adelaide/UADEL-VIRT-DATA-PT-12-2023-U-LOLC/-/blob/main/20-Supervised-Learning/2/Activities/06-Stu_Predicting_Default/Solved/predict_default_solution.ipynb?ref_type=heads

University of Adelaide. (2024). Predicting Sales - Solved. Retrieved May 12, 2024, from https://git.bootcampcontent.com/University-of-Adelaide/UADEL-VIRT-DATA-PT-12-2023-U-LOLC/-/tree/main/20-Supervised-Learning/1/Activities/02-Stu_Predicting_Sales/Solved?ref_type=heads