# Project Supermarket simulation

### Description
At this Supermarket chain we would like to understand our customers better in order to optimize the layout, staffing and service of our supermarkets. We would like to model the way customers move through a representative shop. Our main business goals are:

- understand customer behavior
- explain customer behavior to our non-data staff
- optimize staffing so that the queues do not get unnecessary long

The supermarket is divided into four areas:

- fruit
- spices
- dairy
- drinks

The customers move between these areas freely. Sooner or later, they will enter the checkout area. Once they do, they are considered to have left the shop.

### Objective:
The project consists of the following stages:
- calculate transition probabilities (pandas)
- implement a Markov Chain-based data generator
- write a simulator
- visualize the customer movement

Data exploration was interested in the following:

- Calculate the total number of customers in each section
- Calculate the total number of customers in each section over time
- Display the number of customers at checkout over time
- Calculate the time each customer spent in the market
- Calculate the total number of customers present in the supermarket over time.
- Business managers have a hypothesis that the first section customers visit when they enter the market follows a different pattern than the following ones. Test the hypothesis
- Plot the distribution of customers of their first visited section versus following sections (treat all sections visited after the first as “following”)
- Estimate the total revenue for a customer
- Which is the most profitable section according to your data?
