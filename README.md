# delightfulFireflies

Made by:
  
  - Alan Pascual
  - Julia Loh
  - Tal Moriah
  - Bryan Guan  

This demo was developed as a final project for an AI
practicum. The goal of the algorithm is to be able to learn how to
trace a given symbol, such the Batman logo. The GUI shows the genetic algorithm in
progress during one of its iterations. Each iteration, the algorithm generates many "fireflies" that are given random/semi-random directions.
Every generation of fireflies is influenced by the most successful fireflies in the previous iteration(the fireflies
that most accurately traced the logo) as well as a few induced mutations to reduce the likelyhood of local optimums.
To optimize performance, the time each generation is alloted to perform is gradually increased. Instead of attempting to trace the entire graph every generation, each 
generation traces slightly more of the graph than the previous generation - which is why the Batman symbol in the demo is only partially complete. This optimization also improves the accuracy of the algorithm.
Users can toggle between showing every firefly or just the most
accurate firefly. 

![](https://github.com/b-guan/delightfulFireflies/blob/main/genetic%20algorithm.gif)
