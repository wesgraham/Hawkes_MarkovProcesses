# hawkesprocess
Python Script for Simulating Hawkes Processes

About Hawkes Processes
A Hawkes process {\displaystyle N_{t}} N_{t}, also known as a self-exciting counting process, is a simple point process whose conditional intensity can be expressed as:
{\displaystyle {\begin{array}{ll}\lambda (t)&=\mu (t)+\int _{-\infty }^{t}\nu (t-s)dN_{s}\\&=\mu (t)+\sum _{T_{k}<t}\nu (t-T_{k})\end{array}}}
where {\displaystyle \nu :\mathbb {R} ^{+}\rightarrow \mathbb {R} ^{+}} {\displaystyle \nu :\mathbb {R} ^{+}\rightarrow \mathbb {R} ^{+}} is a kernel function which expresses the positive influence of past events {\displaystyle T_{i}} T_{i} on the current value of the intensity process {\displaystyle \lambda (t)} \lambda (t), {\displaystyle \mu (t)} {\displaystyle \mu (t)} is a possibly non-stationary function representing the expected, predictable, or deterministic part of the intensity, and {\displaystyle \{T_{i}:T_{i}<T_{i+1}\}\in \mathbb {R} } {\displaystyle \{T_{i}:T_{i}<T_{i+1}\}\in \mathbb {R} } is the time of occurrence of the i-th event of the process. 
This process is used to model self-exciting point processes, for example - how many tweets one could expect in the event of a major news event, the buying order tendencies displayed once a whale purchases a large lump sum of stock, and more. 

Interacting with the Script
To model a point process, call the function wes_hawkes(lambda_0, alpha, beta, bigTboi). Keep in mind that alpha <= beta. 
