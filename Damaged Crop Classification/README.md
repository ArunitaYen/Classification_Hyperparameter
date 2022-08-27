# Crop Damaged

The data contains 9 attributes all in numerical form  
where the attributes are as follows  
ID: UniqueID  
Estimated_Insects_Count: Estimated insects count per square meter  
Crop_Type: Category of Crop(0,1)  
Soil_Type: Category of Soil (0,1)  
Pesticide_Use_Category: Type of pesticides uses (1- Never, 2-Previously Used, 3-Currently Using)  
Number_Doses_Week: Number of doses per week  
Number_Weeks_Used: Number of weeks used  
Number_Weeks_Quit: Number of weeks quit  
Season: Season Category (1,2,3)  
Crop_Damage: Crop Damage Category (0=alive, 1=Damage due to other causes, 2=Damage due to Pesticides)  


## Insights

![Line Plot](https://github.com/ArunitaYen/Classification_Hyperparameter/blob/main/Damaged%20Crop%20Classification/img/plot1.PNG)

![Scatter Plot](https://github.com/ArunitaYen/Classification_Hyperparameter/blob/main/Damaged%20Crop%20Classification/img/plot2.PNG)

![Box Plot](https://github.com/ArunitaYen/Classification_Hyperparameter/blob/main/Damaged%20Crop%20Classification/img/plot3.PNG)

![Bar Plot](https://github.com/ArunitaYen/Classification_Hyperparameter/blob/main/Damaged%20Crop%20Classification/img/plot4.PNG)

### Structure in data

![Parallel Coordinate Plot](https://github.com/ArunitaYen/Classification_Hyperparameter/blob/main/Damaged%20Crop%20Classification/img/Parallel%20plot.PNG)

![Andrews Plot](https://github.com/ArunitaYen/Classification_Hyperparameter/blob/main/Damaged%20Crop%20Classification/img/AndrewsPlot.PNG)

![Radviz Plot](https://github.com/ArunitaYen/Classification_Hyperparameter/blob/main/Damaged%20Crop%20Classification/img/RadvizPlot.PNG)

## Hyperparameter tuning and cross validation results
### Random Forest scores for GridearchCV
--Few predictions--

array([1, 0, 0, 0])

Accuracy Score : 68.02835921674544

--Confusion Matrix--

array([[11065,  2167,  1623],
       [  824,   775,   868],
       [   91,   109,   250]])

F1 Score : 0.7322726999126774

### Decision Tree Scores for GridSearchCV
--Few predictions--  
  
array([1, 0, 0, 0])  
  
Accuracy Score : 64.78730587440918  
  
--Confusion Matrix--  
  
array([[10458,  2399,  1998],  
       [  730,   800,   937],  
       [   84,   110,   256]])  
  
F1 Score : 0.7111662284833571  
  
### Random Forest Scores for RandomSearchCV  
  
Best score: 0.6813296245275972  
Accuracy: 68.02835921674544  
f1 score: 0.7319591218626418  
  
### Decision Tree Scores for RandomSearchCV  
  
Best score: 0.6626057685759401  
Accuracy: 66.21089354040063  
f1 score: 0.7182499927132402  
