# COMPUTATIONAL INTELLIGENCE LAB2

The first solution in [TSP-Fast](tsp.ipynb) computes the shortest path starting from the i-th city and moving for each current city to the closest one. The final solution is the best overall found using all the i-th cities as first city.

The second solution in [TSP-EA](tsp_ea.ipynb) provide a solution using a customized evolutionary algorithm.

## SOLUTIONS

The following table shows the best overall results obtained with the two methods applyed.

### Fast Greedy Computation

| Country | N Cities | N Iteration | Best Lenght Fast Solution (km) |
| ------- | -------- | ----------- | ------------------------------ |
| Vanuatu | 8        | 8*8         | 1_475.53                       |
| Italy   | 46       | 40*40       | 4_436.03                       |
| Russia  | 167      | 167*167     | 40_051.59                      |
| US      | 326      | 326*326     | 46_244.33                      |
| China   | 726      | 726*726     | 62_116.04                      |
<br>
### EA Custom Computation

| Country | N Cities | N Generations | Best Lenght EA Solution (km) |
| ------- | -------- | ------------- | ---------------------------- |
| Vanuatu | 8        | 200           | 1_345.54                     |
| Vanuatu | 8        | 4_000         | 1_345.54                     |
| Italy   | 46       | 200           | 4_181.18                     |
| Italy   | 46       | 4_000         | 4_172.76                     |
| Russia  | 167      | 200           | 37_344.65                    |
| Russia  | 167      | 4_000         | 35_714.91                    |
| US      | 326      | 200           | 43_156.82                    |
| US      | 326      | 4_000         | 40_164.23                    |
| China   | 726      | 200           | 60_041.85                    |
| China   | 726      | 4_000         | 56_216.41                    |