# Discriminant Analysis (DA)
We have a dataset in which there are 143 observations, 6 independent variables and 1 dependent variables. \
Variables are as follows:\
Independent Variables:
- X1 = the availability of information about the city services 
- X2 = the cost of housing 
- X3 = the overall quality of public schools 
- X4 = your trust in the local police 
- X5 = the maintenance of streets and sidewalks 
- X6 = the availability of social community events 

Attributes X1 to X6 have values 1 to 5.

Dependent Variable: 
- D = decision attribute (D) with values 0 (unhappy) and 1 (happy).

Now we would like to create LDA and QDA Models for this dataset in order to forecast if the person is unhappy or happy. <br>
So, In order to forecast if the person is unhappy or happy we’ll be creating both models and according to that we can give insights for the same. <br>
Here, SMOTE will be used to fix any discrepancies in the dataset. We assume that the input variables should all have the same variance and that both the LDA and QDA classification models should have normal variance distributions. <br>
Also we’ll be giving the key insights for Pandas Profile Report and then we can compare both Optimized model and can identify which one is better. <br>
We’ll be recommending the ways for the next steps of the model in the end.
