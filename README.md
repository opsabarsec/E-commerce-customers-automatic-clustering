# E-commerce customers automatic classification by ML/AI
![ecommerce](ecommerce.png)
## 1.Background
The Brazilian e-commerce platform Olist would like to use artificial intelligence to automatically classify customers into categories. 

The business goal is to identify user types based on their personal data and buying behavior. This can help them with:

    1. Competitive pricing.
    2. Targeting customers.
    3. Decision making.
    4. Making better strategies.
    
Expected goals for this project: 

- offer to Olist Marketing team a straightforward visualization of the machine learning (ML) classification algorithm output.

- estimate the timespan for the ML classification pipeline and offer to Olist a reasonable maintenance contract

## 2. The data

Customers unsupervised grouping from the Brazilian e-commerce company Olist dataset

https://www.kaggle.com/olistbr/brazilian-ecommerce

## 3. The model outcome

For details, you can consult the full [presentation describing target achievement to OList Marketing team](https://github.com/opsabarsec/E-commerce-customers-automatic-clustering/blob/master/segmentation_clients_fr.pdf)

Below an illustration of clusters generated using the K-Means alghorithm and represented after projection on the two main principal components

![clusters](cluster.png)

Calculations have been carried out using rapids.ai, running on Google COLABS GPUs

Python code can be found in the OList python notebooks

[part 1: data cleaning and exploration](https://github.com/opsabarsec/E-commerce-customers-automatic-clustering/blob/master/OList_part1.ipynb)
[part 2: unsupervised clustering of the customers] (https://github.com/opsabarsec/E-commerce-customers-automatic-clustering/blob/master/OList_part2.ipynb)
