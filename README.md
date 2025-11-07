# CI2025_lab2 - Travelling Salesman Problem

### Genetic Algorithm results (population=100, generations=1000)

- tournament selection ($\tau = 5$)
- order-based crossover 
- swap mutation ($p = \frac{1}{genome size}$)

| Problem name    | Best distance | Average distance | Runtime (s) |      Notes |
| --------------- | ------------: | ---------------: | ----------: | ---------: |
| problem_g_10    |     1497.6636 |        1497.6636 |        3.46 |            |
| problem_g_20    |     1755.5147 |        1788.3416 |        5.53 |            |
| problem_g_50    |     2852.1778 |        3020.7105 |       13.68 |            |
| problem_g_100   |     5386.7016 |        5870.2513 |       32.94 |            |
| problem_g_200   |    13680.8010 |       14448.8698 |       91.67 |            |
| problem_g_500   |         46833 |                / |         479 | single run |
| problem_g_1000  |        111060 |                / |        1730 | single run |
| problem_r1_10   |      184.2734 |         184.2734 |        3.45 |            |
| problem_r1_20   |      340.8621 |         346.2260 |        5.57 |            |
| problem_r1_50   |      604.4144 |         650.8863 |       13.66 |            |
| problem_r1_100  |     1132.3645 |        1199.3823 |       32.95 |            |
| problem_r1_200  |     2867.8982 |        2816.1037 |       91.89 |            |
| problem_r1_500  |          9218 |                / |         473 | single run |
| problem_r1_1000 |         21223 |                / |        1722 | single run |
| problem_r2_10   |     -411.7017 |        -411.7017 |        3.42 |            |
| problem_r2_20   |     -858.6408 |        -839.9048 |        5.48 |            |
| problem_r2_50   |    -2203.2104 |       -2164.5329 |       13.50 |            |
| problem_r2_100  |    -4345.1764 |       -4260.0590 |       32.48 |            |
| problem_r2_200  |    -7841.7098 |       -8149.4002 |       91.80 |            |
| problem_r2_500  |        -18573 |                / |         478 | single run |
| problem_r2_1000 |        -34542 |                / |        1721 | single run |

Notes:
- Best distance: shortest tour length found among the runs.
- Average distance: mean over 10 runs.