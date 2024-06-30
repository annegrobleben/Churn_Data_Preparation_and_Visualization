This notebook is based on two assignments done as part of a Master in Data Science & AI at Nuclio Digital School, it shows how to prepare a churn dataset for model building and to perform exploratory data analysis. This data preparation includes
*   General duplicate removal
*   Removal of customer ID duplicates
*   Dealing with errors in the data, such as negative age values and float values that should really be integers
*   Data visualization: univariate and bivariate plots
*   Outlier identification and treatment
*   Dealing with missing values
*   Encoding categorical variables
*   Scaling continuous variables
*   Correlations between the different variables and customer churn

This notebook was created in Google Colab. In order to run it in Google Colab the attached csv-file "churn_data_before_processing.csv" needs to added to "MyDrive" in Google drive in a folder named "DataPreparation" 
so that the second and third code cell can be run properly. In case that this notebook is run in an application that is different from Google Colab the second and third code need to be adjusted beforehand. 
