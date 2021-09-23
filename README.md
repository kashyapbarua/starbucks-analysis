<img src="https://digital.hbs.edu/platform-rctom/wp-content/uploads/sites/4/2017/11/tumblr_static_sb-banner.jpeg" width="1000" height="200" />

# Starbucks Capstone Project

### Who is Starbucks?
Starbucks Corporation is an American multinational chain of coffeehouses and roastery reserves headquartered in Seattle, Washington. As the world's largest coffeehouse chain, Starbucks is seen to be the major representation of the United States' second wave of coffee culture.

### What is the problem statement and project motivation?
The idea behind picking up the starbucks promotional dataset is to firstly understand the nuances in the promotions program run by Starbucks, and the adoption and engagement metrics by its customers. We try to understand answer to some questions:
* What are the different types of offers rolled out to the customers?
* What is the income and age distribution of the customers in the dataset?
* What is the age group of the different genders?
* What is the distribution of different types of actions performed on the promotions rolled out to the customers?

### What are the contents of the repository?
* A [juptyer notebook](https://github.com/kashyapbarua/starbucks-analysis/blob/main/Starbucks_Capstone_notebook.ipynb) containing the analysis, insights & modeling
* [Readme](https://github.com/kashyapbarua/starbucks-analysis/edit/main/README.md) file explaining the project motivation and other contents
* [Data](https://github.com/kashyapbarua/starbucks-analysis/tree/main/data) contains all the raw json files

### Packages used in the dataset

`pandas`
`matplotlib.pyplot`
`sklearn`
`json`

### How does the datasets look like?

For this project, the data sets are provided by Starbucks and Udacity in the form of three JSON files. These contains simulated data that mimics customer behavior on the Starbucks rewards mobile app.

* portfolio.json - containing offer ids and meta data about each offer (duration, type, etc.)
* profile.json - demographic data for each customer
* transcript.json - records for transactions, offers received, offers viewed, and offers completed

### Modeling

After pre-processing the dataset, we use different models to evaluate the model and their performances w.r.t their predictive capabilities
