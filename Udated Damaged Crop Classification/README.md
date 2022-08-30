# Damaged Crop Classification

## Observations

## ***Grid Search CV*** 


*with oversapmling*

> **Random Forest**  
 Accuracy: 67.9045689849201  
 F1 Score: 0.731365248874125  

 

>**Decision Tree**  
 Accuracy: 63.23992797659239  
 F1 Score: 0.7001263141291102   



*Without oversampling and feature generation*   


> **Random Forest**  
 Accuracy: 84.28989421562008  
 f1 score: 0.7880623936672897  


> **Decision Tree**  
 Accuracy: 84.05919423812739  
 F1 Score: 0.7934636286673246  
 
 
 
 ## ***Random Search CV***  
 
 
*with oversapmling*

> **Random Forest**  
Accuracy: 68.02835921674544  
f1 score: 0.7319591218626418   

>**Decision Tree**  
Accuracy: 66.21089354040063  
f1 score: 0.7182499927132402  



*Without oversampling and feature generation*   


> **Random Forest**  
Accuracy: 84.28989421562008  
f1 score: 0.7880623936672897    


> **Decision Tree**  
Accuracy: 84.2111186135494  
f1 score: 0.7944785090782224


## Analysis
The models are giving better results without oversampling, so it can be suggested not to use any oversampling technique, also there is no overfitting occuring without oversampling, as it is being taken care by hyper parameter.
