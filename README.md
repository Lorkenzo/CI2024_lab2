# COMPUTATIONAL INTELLIGENCE LAB2

The first solution in [TSP-Fast](tsp.ipynb) computes the shortest path starting from the i-th city and moving for each current city to the closest one. The final solution is the best overall found using all the i-th cities as first city.

The second solution in [TSP-EA](tsp_ea.ipynb) provide a solution using a customized evolutionary algorithm.

## SOLUTIONS

The following table shows the best overall results obtained with the two methods applyed.  

| Country | N Cities | Best Lenght Fast Solution (km) | Best Lenght EA Solution (km) |
| ------- | -------- | ------------------------------ | ---------------------------- |
| Vanuatu | 8        | 1_475.53                       | 1_345.54                     |
| Italy   | 46       | 4_436.03                       | 4_181.18                     |
| Russia  | 167      | 40_051.59                      | 37_344.65                    |
| US      | 326      | 46_244.33                      | 43_156.82                    |
| China   | 726      | 62_116.04                      | 60_041.85                    |