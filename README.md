# Aerofit---Descriptive-Statistics-Probability

### About Aerofit:

Aerofit is a leading brand in the field of fitness equipment. Aerofit provides a product range including machines such as treadmills, exercise bikes, gym equipment, and fitness accessories to cater to the needs of all categories of people.


### Business Problem:

The market research team at AeroFit wants to identify the characteristics of the target audience for each type of treadmill offered by the company, to provide a better recommendation of the treadmills to the new customers. The team decides to investigate whether there are differences across the product with respect to customer characteristics.
* Perform descriptive analytics to create a customer profile for each AeroFit treadmill product by developing appropriate tables and charts.
* For each AeroFit treadmill product, construct two-way contingency tables and compute all conditional and marginal probabilities along with their insights/impact on the business.

### Dataset:

The company collected the data on individuals who purchased a treadmill from the AeroFit stores during the prior three months. The dataset has the following features:

* Product Purchased:	KP281, KP481, or KP781
* Age:	In years
* Gender:	Male/Female
* Education:	In years
* MaritalStatus:	Single or partnered
* Usage:	The average number of times the customer plans to use the treadmill each week.
* Income:	Annual income (in $)
* Fitness:	Self-rated fitness on a 1-to-5 scale, where 1 is the poor shape and 5 is the excellent shape.
* Miles:	The average number of miles the customer expects to walk/run each week

### Evaluation Criteria:

1. Defining Problem Statement and Analysing basic metrics
   * 1.1 Observations on shape of data, data types of all the attributes, conversion of categorical attributes to 'category' (If required), statistical summary
3. Non-Graphical Analysis: Value counts and unique attributes
4. Visual Analysis - Univariate & Bivariate
   * 3.1 For continuous variable(s): Distplot, countplot, histogram for univariate analysis
   * 3.2 For categorical variable(s): Boxplot
   * 3.3 For correlation: Heatmaps, Pairplots
4. Missing Value & Outlier Detection
5. Business Insights based on Non-Graphical and Visual Analysis
   * 5.1 Comments on the range of attributes
   * 5.2 Comments on the distribution of the variables and relationship between them
   * 5.3 Comments for each univariate and bivariate plot
6. Recommendations - Actionable items for business. No technical jargon. No complications. Simple action items that everyone can understand

### What good looks like?

1. Import the dataset and do usual data analysis steps like checking the structure & characteristics of the dataset
2. Detect Outliers (using boxplot, “describe” method by checking the difference between mean and median)
3. Check if features like marital status, age have any effect on the product purchased (using countplot, histplots, boxplots etc)
4. Representing the marginal probability like - what percent of customers have purchased KP281, KP481, or KP781 in a table (can use pandas.crosstab here)
5. Check correlation among different factors using heat maps or pair plots.
6. With all the above steps you can answer questions like: What is the probability of a male customer buying a KP781 treadmill?
7. Customer Profiling - Categorization of users.
8. Probability- marginal, conditional probability.
9. Some recommendations and actionable insights, based on the inferences.
