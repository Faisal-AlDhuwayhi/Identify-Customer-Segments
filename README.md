# Identify Customer Segments
In this project, you will work with real-life data provided to us by our Bertelsmann partners AZ Direct and Arvato Finance Solution. The data here concerns a company that performs mail-order sales in Germany. Their main question of interest is to identify facets of the population that are most likely to be purchasers of their products for a mailout campaign. Your job as a data scientist will be to use unsupervised learning techniques to organize the general population into clusters, then use those clusters to see which of them comprise the main user base for the company. Prior to applying the machine learning methods, you will also need to assess and clean the data in order to convert the data into a usable form.

And the project is divided as follows:
- Step 0: Load The data
- Step 1: Preprocessing
  -  Assessment - Cleaning - Re-encoding
  -  Feature engineering
- Step 2: Feature Transformation
  - Feature scaling and Perform the PCA
  - Interpret Principal Components
- Step 3: Clustering
  - Apply clustring
  - Compare Customer Data to Demographics Data

## Requirements
This project uses Python 3 and is designed to be completed through the Jupyter Notebooks IDE.
The following libraries are expected to be used in this project:
- NumPy
- pandas
- Sklearn / scikit-learn
- Matplotlib (for data visualization)
- Seaborn (for data visualization)

## Data
The actual data was removed due to terms and conditions of AZ Direct GmbH which prohibits of using data in any other content rather than Udacity course.

## Results
Cluster 9 is **overrepresented** in the customers data compared to general population data, we can describe some segments of the population that are **relatively popular** with the mail-order company:

- People with age older than 60 years old is higher (ALTERSKATEGORIE_GROB = 3.608463)
- Females (ANREDE_KZ = 1.535703)
- People who are socially-minded (average affinity) (SEMIO_SOZ = 3.915283)
  
Cluster 8 is **underrepresented** in the customers data compared to general population data, we can illustrate some segments of the population that are **relatively unpopular** with the company:

- People with age of 30 - 45 years old is lower (ALTERSKATEGORIE_GROB = 1.805549)
- Females (ANREDE_KZ = 1.981174)
- People who are socially-minded (high affinity) (SEMIO_SOZ = 3.226965)



**Note:** There is [one iPython notebook](https://github.com/Faisal-AlDhuwayhi/Identify-Customer-Segments/blob/master/Identify_Customer_Segments.ipynb) to showcase work related to this project. The [html file](https://github.com/Faisal-AlDhuwayhi/Identify-Customer-Segments/blob/master/Identify_Customer_Segments.html) was generated from the iPython notebook.

