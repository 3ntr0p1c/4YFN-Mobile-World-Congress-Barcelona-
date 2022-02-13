# 4YFN-Mobile-World-Congress-Barcelona-
Solution of the individual online data science challenge.


Overview: the dataset and challenge

Two datasets will be used: the first contains data from Nuwefruit customers and the other contains data from the orders made by them.

1. The customer dataset 'CLIENT TABLE' contains the following variables:

- CLIENT ID: Unique identifier of the client
- CLIENT_SEGMENT: Client segment
- AVG CONSO: Average monthly customer consumption calculated at the end of 2020 (in pieces of fruit)
- AVG BASKET SIZE: Average customer basket size calculated at the end of 2020 (in pieces of fruit)
- RECEIVED_COMMUNICATION: 1 = Received promotion of your products / 0 = did not receive it

2. The customer dataset 'ORDERS TABLE' contains the following variables:

- CLIENT ID: Unique identifier of the client
- NB PRODS: Number of 'prods' of the fruit variety in the order (1 prod = 10 pieces of fruit)
- ORDER ID: Unique identifier of the order
- FRUIT_PRODUCT: Variety of fruit


Objective

The are two main objectives:

1. Make an exploratory analysis of the data that allows:

- Analyze sales and customer activity
- Evaluate the impact of the promotion

2. Perform a predictive model that allows knowing the type of segment to which each client belongs based on the predictor variables: AVG CONSO', 'AVG BASKET SIZE', 'RECEIVED_COMMUNICATION.

Reference metric for model evaluation: f1-score ('macro')
