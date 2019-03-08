# hawkesprocess
Python Script for Simulating Hawkes Processes

## About Hawkes Processes
Hawkes processes are a particularly interesting class of stochastic process that have been applied in diverse areas, from earthquake modelling to financial analysis. They are point processes whose defining characteristic is that they 'self-excite', meaning that each arrival increases the rate of future arrivals for some period of time. Hawkes processes are well established, particularly within the financial literature, yet many of the treatments are inaccessible to one not acquainted with the topic. 

This type of process is used to model self-exciting point processes, for example - how many tweets one could expect in the event of a major news event, the buying order tendencies displayed once a whale purchases a large lump sum of stock, and more. 

## Interacting with the Script
To model a point process, call the function wes_hawkes(lambda_0, alpha, beta, bigTboi). Keep in mind that alpha <= beta. 
