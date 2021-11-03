# Machine Learning Foundations:Supervised Machine Learning: Regression course
## Part of IBM Machine Learning certificate

## Project title: 
'How does the vehicle’s engine size influence CO2 emissions?' - By Zahra Adahman, BSc/MBS.
#### June 30th, 2021.

## Background and Problem

Greenhouse gas emissions are released to the environment due to a variety of human activities. These gases trap heat in the atmosphere leading to climate change. The top four greenhouse gases are Carbon Dioxide (CO2), Methane (CH4), Nitrous oxide (N2O) and Fluorinated Gases (HFCs, PFCs, SF6). However, Carbon Dioxide (CO2) is the largest greenhouse gas released. According to the US EPA (United States Environmental Protection Agency), transportation accounts for 29 percent of 2019 greenhouse gas emissions) – The transportation sector generates the largest share of greenhouse gas emissions of which is mostly CO2. CO2 gas emissions from transportation primarily comes from burning fossil fuels (gas, diesel and so on). About 4.6 metric tons of CO2 gas is emitted from a typical passenger vehicle every year. This project aims to develop a regression model to interpret the relationship between engine size and CO2 emissions. The main (first) objective of this model will help describe the relationship between engine size and CO2 emissions. In addition, the second objective of this model will be to prescribe what engine size is best to regulate the amount of CO2 gas emissions. This model can help government and environmental experts in climate change decide on policies for vehicle manufactures to follow when building fossil fuel automobiles to promote less CO2 gas emissions. 

## Methodology 

* Python
* Jupyter Notebook
* Pandas Library
* Numpy Library 
* Seaborn Library
* ScikitLearn Library

## Data

The data fuelcomsumption.csv was used for the study were gotten from a previous IBM Data Science course material. The data was imported using pandas. 


## Visualization 

![image](https://user-images.githubusercontent.com/59964869/140084263-6d8708b6-f4fc-4c71-bc65-0402617d7c3b.png)

![image](https://user-images.githubusercontent.com/59964869/140084332-95bdf705-eab2-4d53-84eb-56dcfba868e7.png)

![image](https://user-images.githubusercontent.com/59964869/140084158-aac4372d-1ab8-4411-9675-63d76f292512.png)


## Conclusion
These results do show a positive linear relationship between of engine size to the CO2 emissions. The R2 score of the linear regression was 0.76 showing that there is a positive correlation between the two variables. The Cross-validation analysis show that an alpha of 101 is just as good as 109. Lasso and Ridge analysis was done. The R2 score was for Lasso regression was 0.70 and ridge regression 0.70.
     There is no significant difference in the lasso and ridge regression analysis. Either analysis will be good to build the model. The larger engine size correlated with more the CO2 emissions.
Next Steps: The dataset is not very large and the data set was from a previous course. It would be best to test this model on a more diverse dataset. 
Reducing CO2 emissions is not only from controlling fossil-fuels burning vehicles. Hence, tackling the release of CO2 and other greenhouse gases is not only from using a model for this variables. Other factors are important to consider as it is a multifaceted issue leading to climate change.

