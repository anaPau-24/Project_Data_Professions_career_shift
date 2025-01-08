# Project_Data_Professions:career_shift
This repository contains the files used for analysis of the data set "global AI, ML, Data salaries" downloaded from aijobs.net. The analysed data formed part of the final project form the bootcamp for Data Analyst from GreenBootcamps (Oct 2024-Jan 2025).

The steps followed for the exploratory data analysis (EDA) were:

### Understanding the Data
- Load the data file "salaries.csv" into Panda's DataFrame.
- Examine the descriptive statistics of the dataset.
- Check for missing values. Are they concentrated in some column or in some observations?
- Check for non null values (NaN)
- Check which features are continuous or categorical.

### Hypotheses Generation
- Some potential hypotheses were determined based on a stakeholder that wants a career change to Data sector (see Information_Stakeholder_and_hypotheses.md).
   
### Exploring the data
- Delete unnecessary data for answering the hypotheses.
- Check distributions of the continuous variables(eg.with histograms for each of them).
- Check the distributions for the categorical variables (eg.with plots/tables of counts).
- Look at the histograms and check for clues or patterns: can you identify groups, are the distributions skewed, do you have extreme values or outliers, where is the data centered. Do you need to remove some data?

### Cleaning the data

- Dealing with missing values: remove (rows, or columns) or impute data
- Dealing with extreme values or outliers: remove data
- Transform data where necessary, e.g. to log or sqrt to try to get some feature closer to normal distribution, or binning
- If helpful create new features by combining existing ones
  
### Relationships in the data

- Compute the correlation matrix and plot it (eg.pairplot)
- Are there evident correlations?
- Are all the conclusions expected or unexpected?

### Conclusions

- Were the hypotheses true?
- What recommendations can be given to the stakeholder?
- What are the next steps for  refining the Analysis?

