# Chapter 1

* We can start from the WEKA's template data. Click Open file and choose one of data from ```WEKA\data```.
* After that we can see the each mean,mod are something information about the data.
* For the next step, We must scale the data. Click Filter and choose the ```Normalize```.We can find it in the ```filter\unsupervised\Normalize```.
  
  > Data scaling is a technique in data analysis that is used to change the value range of each data variable, so that the data has a uniform and standardized range of values.The main  the porpuse of data scaling is to ensure each data has a balanced influence in data analysis ,so no single data is dominate the final analysis result.
* After that, we click the ```classify```. and choose the Classifier to regression the data in the ```functions\LinearRegression```.
* Set Cross-validation's Folds to 10.
  
  > This will divide the data into 10 equal parts, train the model on 9 parts and test it on the remaining 1 part, and repeat the process 10 times until all 10 parts have been used for testing.
 
 * You will see the equation the data. If you want to see prediction model choose ```use training set```. If you want to see the data split we can choose in ```Percentage split % 80 ```.
 
  

