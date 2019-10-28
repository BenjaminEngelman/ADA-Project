# Title

# Abstract
Meat consumption is a highly controversial topic in nowadays society in terms of [environment](https://www.theguardian.com/environment/2018/oct/10/huge-reduction-in-meat-eating-essential-to-avoid-climate-breakdown), [health](https://www.netflix.com/ch-en/title/81157840), and [ethical](http://traslosmuros.com/en/slaughterhouse-documentary/) reasons. This situation introduces different ways of consuming meat and divides people according to their behaviors such as vegan, vegetarian, occasional meat consumer, and people consuming large amounts of meats.

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

# A list of internal milestones up until project milestone 2
## Until 7th of November
* Get familiar with the tables and their relations
* Apply descriptive statistics at demographic, household, product and campaign level
* Discuss outliers, missing values, inconsistent tables and transformations needed
## Until 24th of November
* Apply detailed analysis at demographic, household, product and campaign level
* Track consuming behaviors of household with their demographic features in time
* Track consumption of meat and vegetarian product at household level in time
* Analyse the meat consumption at household level and cluster households according to their meat consumption

# Questions for TAs
* How can we move from household level to individual level? Can we get in contact with Dunnhumby for more information on it?
* Do you know in which country/countries this data was collected since we could not find information about it in the Dunnhumby's data description?
* Do you also know if they use a standardized product description in their product table (COMMODITY_DESC COLUMN) so that we can find more information about these products in different datasets?
