# Heart-Disease-MLP

The Overview file will provide a good overview as to how we cleaned the data, explored it, did feature selection using Random Forests, built a basic MLP and then our improved MLP (with data scaling, PCA, bias reduction, grid search).


Our final MLP model has an accuracy of: 77.37% and a recall of 85.69%

Here is how the MLP was built: 
1) Feature Engineering (identifying relevant features).
2) Adding hidden layers.
3) Oversampling of positive cases to improve recall.
4) Training callbacks and early stopping
 * callbacks were used to stop training after the precision-recall curve on the validation set stopped improving
5) Grid Search hyper-parameter tuning

### Final MLP Model: 
2 dense layers  (RELU), 1 dropout layer (0.5), 1 final output layer (Sigmoid)
Optimizer = Adam, Learning Rate = 0.001

**Our final MLP model has an accuracy of: 77.37% and a recall of 85.69%**

--
The remaining files include our rough work. If you want to gain a better understanding of our thought process, follow the files as ordered:
1. DataCleaning 
2. Data_Exploration
3. RandomForestClassifier+Recall Improvement -> The basic Random Forest Classifier + 
4. SHAP_Analysis -> the SHAP analysis was built but couldn't be executed completely due to technological constraints
5. Basic_MLP_Models -> the basic MLP models we started with and hyper-parameter tuning
6. Balancing_MLP_Models -> MLP models with bias reduction techniques
7. MLP(with Scaling, PCA and improved recall) -> Final Model with Scaling, PCA and improved recall implemented!


