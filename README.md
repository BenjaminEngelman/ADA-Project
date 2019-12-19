# Nice to Meat You: An Analysis on Meat Consumption

**Data analysis with interactive plots is available [here](https://nbviewer.jupyter.org/github/BenjaminEngelman/ADA-Project/blob/master/main.ipynb?flush_cache=true).

**The data story is available [here](http://benjaminengelman.github.io/).**

# Abstract
Meat consumption is a highly controversial topic in nowadays society in terms of [environment](https://www.theguardian.com/environment/2018/oct/10/huge-reduction-in-meat-eating-essential-to-avoid-climate-breakdown), [health](https://gamechangersmovie.com/), and [ethical](http://traslosmuros.com/en/slaughterhouse-documentary/) reasons. This situation introduces different ways of consuming meat and divides people according to their behaviors such as vegan, vegetarian, occasional meat consumer, and people consuming large amounts of meats.

In this project, we are particularly interested in the factors related to consuming meat and how the behavior of households varies according to their meat consumption. We are going to focus on demographic information such as economic status, family composition, age, and their relation with consuming meat. Moreover, we are going to study external effects that are related to meat consumption such as seasonal changes, campaigns, and discounts. Finally, we are going to categorize households according to their meat consumption and perform a behavior analysis per category.

To do so, we are going to use the Dunnhumby dataset. This dataset contains shopping information collected over two years from a group of 2,500 households as well as their information for each household. Moreover, we are planning to expand our analysis with an additional dataset about nutritional information.

# Research questions
## Factors that influence meat consumption
* Does the economical status of the household influence the meat consumption?
* How does the family composition affect meat consumption?
* Is there a relation between the age of the individual and her/his meat consumption?
* How do the seasonal changes, bank holidays affect meat consumption?
* What is the influence of campaigns and discounts on meat consumption?
## Behavior Analysis of meat consumers
* What are the other type of products that meat consumers frequently buy?
* How much does meat consumption affect the sensitivity to a different type of campaigns?
* Does meat consumption vary in time for a household?

# Dataset
[Dunnhumby](https://www.dunnhumby.com/careers/engineering/sourcefiles): This dataset contains household level transactions over two years from a group of 2,500 households who are frequent shoppers at a retailer. Moreover, this dataset provides demographic information for households as well as information about campaigns and discounts of stores.

# Structure
```
.
├── data # contains all the data from the preprocess steps
│   ├── food_products.csv
│   └── meat_products.csv
│   └── vegetables_products.csv
│   └── pure_meat_products.csv
│   └── spentt_by_houshold.csv
├── main.ipynb # notebook with complete work of our research
├── preprocess.ipynb # notebook with the preprocessing of the data to create related dataframes
├── statistics.csv # notebook that contains results of statistical tests applied in main notebook
└── README.md
```

# Contribution

Soner: Preliminary data analysis of demographic data and coupons, demographic analysis on consumption, design of data story

Thomas: Preliminary data analysis and preprocessing of products, statistical tests, group comparisons.

Benjamin: Preliminary data analysis of transactions, group comparison analysis, interactive plots and graphs for the data story

David: Preliminary data analysis of Transaction data, time analysis, coding the data story

Although these are the main division of work, everyone patricipated in almost all the tasks as we were most of the time working and together discussing the results.
