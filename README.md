# PMML Files for TIBCO Statistica

Example analytic models as Predictive Model Markup Language (PMML) version 4.2 for use with TIBCO Statistica®.

## File Descriptions<a name="files"></a>

a. The datasets are in the [**csv**](https://github.com/kgunasek-projects/Statistica-PMML4/tree/master/csv) folder

1. **Audit.csv**

	The Audit dataset is an artificial dataset consisting of fictional clients who have been audited, perhaps for tax refund compliance. For each case an outcome is recorded (whether the taxpayer's claims had to be adjusted or not) and any amount of adjustment that resulted is also recorded.
	
	*Columns*: Age, Employment, Education, Marital, Occupation, Income, Gender, Deductions, Hours, Adjusted
	
	*Rows*: 1899
		
2. **Auto.csv**

	The Auto dataset consists of information about the fuel mileage, cylinders, horsepower, and other information for 392 vehicles.
	
	*Columns*: mpg, cylinders, displacement, horsepower, weight, acceleration, model_year, origin
	
	*Rows*: 392
	
3. **Iris.csv**

	Perhaps the best known database to be found in the pattern recognition literature, R. A. Fisher's 1936 paper is a classic in the field and is referenced frequently to this day. The data set contains 3 classes of 50 instances each, where each class refers to a type of iris plant. One class is linearly separable from the other 2; the latter are NOT linearly separable from each other.
	
	*Columns*: Sepal_Length, Sepal_Width, Petal_Length, Petal_Width, Species
	
	*Rows*: 150
		
b. Statistica® data mining models as Predictive Model Markup Language (PMML) are in the [**pmml**](https://github.com/kgunasek-projects/Statistica-PMML4/tree/master/pmml) folder

| Model file name												  | Description
| :---                                                            | :---: |
| 01_Classification_Trees_Iris.pmml                               | Classification model built using Statistica Classification and Regression Trees (CART) module on Iris dataset. |
| 02_Regression_Trees_Iris.pmml                                   | Regression model built using Statistica Classification and Regression Trees (CART) module on Iris dataset.|
| 03_Boosted_Classification_Trees_Iris.pmml                       | Classification model built using Statistica Boosted Trees module on Iris dataset. |
| 04_Boosted_Regression_Trees_Iris.pmml                           | Regression model built using Statistica Boosted Trees module on Iris dataset. |
| 05_RandomForest_Classification_Trees_Iris.pmml                  | Classification model built using Statistica Random Forests module on Iris dataset. |
| 06_RandomForest_Regression_Trees_Iris.pmml                      | Regression model built using Statistica Random Forests module on Iris dataset. |
| 07_NeuralNetworks_MLP_Classification_Audit.pmml                 | Classification (Multilayer Perceptron) model built using Statistica Neural Networks module on Audit dataset. |
| 08_NeuralNetworks_MLP_Regression_Audit.pmml                     | Regression (Multilayer Perceptron) model built using Statistica Neural Networks module on Audit dataset. |
| 09_NeuralNetworks_SOFM_Cluster_Analysis_Audit.pmml              | Cluster model based on the Kohonen algorithm, built using Statistica Neural Networks module on Audit dataset. |
| 10_Support_Vector_Machine_Classification_Iris.pmml              | Classification model built using Statistica Support Vector Machines (SVM) module on Iris dataset. |
| 11_Support_Vector_Machine_Regression_Iris.pmml                  | Regression model built using Statistica Support Vector Machines (SVM) module on Iris dataset. |
| 12_KMeans_Clustering_Audit.pmml                                 | Cluster model built using Statistica k-Means Cluster module on Audit dataset. |
| 13_Hierarchical_Clustering_Audit.pmml                           | Cluster model built using Statistica Tree Clustering module on Audit dataset. |
| 14_General_Regression_Iris.pmml                                 | Regression model built using Statistica General Linear Models (GLM) module on Iris dataset. |
| 15_General_Regression_Auto.pmml                                 | Regression model built using Statistica General Linear Models (GLM) module on Auto dataset. |
| 16_Generalized_Linear_Regression_Normal_Log_Auto.pmml           | Regression model built using Statistica Generalized Linear/Nonlinear models (GLZ) module on Auto dataset. |
| 17_Generalized_Linear_Regression_Multinomial_Logistic_Iris.pmml | Classification model built using Statistica Generalized Linear/Nonlinear models (GLZ) module on Iris dataset. |
| 18_Generalized_Linear_Regression_Tweedie_Log_Iris.pmml          | Regression model built using Statistica Generalized Linear/Nonlinear models (GLZ) module on Iris dataset. |
	
## License<a name="license"></a>

The PMML code in this repository is under a BSD-style licensel; refer to [LICENSE](https://github.com/kgunasek-projects/Statistica-PMML4/blob/master/LICENSE).