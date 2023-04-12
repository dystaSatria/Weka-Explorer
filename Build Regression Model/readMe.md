# Build Regression Model 

* We can start from the WEKA's template data. Click Open file and choose one of data from ```WEKA\data```.
* After that we can see the each mean,mod are something information about the data.
* For the next step, We must scale the data. Click Filter and choose the ```Normalize```.We can find it in the ```filter\unsupervised\Normalize```.
  
  > Data scaling is a technique in data analysis that is used to change the value range of each data variable, so that the data has a uniform and standardized range of values.The main  the porpuse of data scaling is to ensure each data has a balanced influence in data analysis ,so no single data is dominate the final analysis result.
* After that, we click the ```classify```. and choose the Classifier to regression the data in the ```functions\LinearRegression```.
* Set Cross-validation's Folds to 10.
  
  > This will divide the data into 10 equal parts, train the model on 9 parts and test it on the remaining 1 part, and repeat the process 10 times until all 10 parts have been used for testing.
 
 * You will see the equation the data. If you want to see prediction model choose ```use training set```. If you want to see the data split we can choose in ```Percentage split % 80 ```. The all data information we need is contained in the ```Correlation coefficient```.

-------------------------------------------------------------------------------------------------------------------------------------------------------------------------
<br>
<br>
<br>
<br>

# Build Regression Model from the .csv data

Change the csv syntax to the .aiff syntax data.

```
@relation `delaney`

@attribute MolLogP numeric
@attribute MolWt numeric
@attribute NumRotatableBonds numeric
@attribute AromaticProportion numeric
@attribute logS numeric


@data
2.5954000000000006,167.85,0.0,0.0,-2.18
2.376500000000001,133.405,0.0,0.0,-2.0
2.5938,167.85,1.0,0.0,-1.74
2.0289,133.405,1.0,0.0,-1.48
2.9189,187.37500000000003,1.0,0.0,-3.04
1.81,98.96000000000001,0.0,0.0,-1.29
1.9352,96.94399999999999,0.0,0.0,-1.64
1.4054,118.176,4.0,0.0,-0.43
4.3002,215.894,0.0,0.6,-4.57
2.5654000000000003,132.20599999999996,0.0,0.6,-4.37
....................................................

```


