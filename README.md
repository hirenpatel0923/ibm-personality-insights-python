# Enriching data with IBM Personality Insights
This dataset enriched in this project is taken from Kaggle:

https://www.kaggle.com/snap/amazon-fine-food-reviews

Every review is passed to an instance of IBM Watson Personlaity Insights at IBM Cloud (https://www.ibm.com/cloud/) which was
formerly known as Bluemix. The result of the API call is then parsed from JSON and appended as columns in the data frame which
is then written into another CSV. The output CSV is uploaded along with the Project to make it clear as how it's adding more 
meaning to the original data. However, the dataset can be downloaded from the link since it's more than 250MB.