
# Al-Bate Bkame

The project determines the price of the house you want to buy


## used librarys  

Split data

```bash
  library(caTools)
```

Decision tree model

```bash
  library(rpart)
```

Random Forest model

```bash
  library(randomForest)
```

GPM model

```bash
 library(gbm)
```
SVM model

```bash
  library(e1071)
```
For drawing Histogram

```bash
  library(ggplot2)
```
For drawing the ui

```bash
  library(shiny)
```


## Data flow

- Get data from file and see summary about it

- Show if data have null Values
 
- Show if data have Outliers and remove it

- Split data to Training set and test set
## Choosing model

Now we need to choosing the Best model to work with our data

- linear regression 
- decision tree 
- random forest
- GPM model
- SVM model
## Predict price

After Know the best model we predict the home price 
by using 

```bash
  predict(bestModel, data.frame(lotsize = lotsize,
                                                    bedrooms = bedrooms,
                                                    bathrms = bathrms,
                                                    stories = stories,
                                                    driveway = driveway,
                                                    recroom = recroom,
                                                    fullbase = fullbase,
                                                    gashw = gashw,
                                                    airco = airco,
                                                    garagepl = garagepl,
                                                    prefarea = prefarea))

```


## ui

![App Screenshot](https://via.placeholder.com/468x300?text=App+Screenshot+Here)
