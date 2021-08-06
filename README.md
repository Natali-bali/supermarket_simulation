# supermarket_simulation
Markov Chain-based simulation of customer behaviour in supermarket

In first notebook Supermarket EDA and plotting i explored our input data, created extra features, made plots and saved new dataframe in xlsx/clean_xl_final.csv

In second notebook i created matrices of probability vectors for prob of entering first location, prob of next move, prob of time client spent at each location.

To create simulation i generated 2 classes:

Customer class for each individual customer generate time customer spent at each location, next step, check if client reached check out, draw function for each client

Supermarket class creates new customers, move all customers, remove customers if they reached check out or by the end of the day (customers dont rech check out)
draw image

![Alt Text](output.gif)
