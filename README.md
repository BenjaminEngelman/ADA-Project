# Nice to Meat You: An Analysis on Meat Consumption

**For milestone 2 please look at [this link]https://nbviewer.jupyter.org/github/BenjaminEngelman/ADA-Project/blob/master/main.ipynb?flush_cache=true) that contains the main.ipynb (so that interactive plots work).**

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

[USDA National Nutrient DB](https://data.world/craigkelly/usda-national-nutrient-db): This dataset is a flattened version of the USDA National Nutrient Database. It includes nutritional information of the different types of food as well as their description and food category.

# Structure
```
.
├── data # contains all the data from the preprocess steps
│   ├── food_products.cvs
│   └── meat_products.csv
│   └── vegetables_products.csv
├── main.ipynb # notebook for the second milestone
├── preprocess.ipynb # notebook with the preprocessing of the data to create meat vegetable, ... dataframe
└── README.md
```

# Milestone 2 : 
For this milestone two notebooks have been written.

*main.ipynb* contains the descriptive statistics and detailed analysis at demographic, household, product and campaign level. <br/>
In the first part, datasets are inspected one by one, their inconsintencies are corrected and a dataset analysis is done.<br/>
In the second part, links between the different datasets are made and a higher level analysis is made for the research questions.
It compares the consuming behaviors of households with their demographic features with a focus on meat consumption.

*preprocess.ipynb* is a secondary notebook creating preprocessed products datasets depending on their categories (food products, meat products, pure meat products and vegetable products). As this step has less analytical power, it has been decided to write it in a separate notebook. The datasets are then imported in the *main.ipynb* file to be used and analysed.
