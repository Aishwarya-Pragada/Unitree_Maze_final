# Results summary

## Experiment 1: robustness vs disturbance severity (success % with 95% Wilson interval)

| policy   |   severity |   n | success %    |   fall % |   stuck % |   wall contacts/run |   SPL (successes) |   time s (successes) |
|:---------|-----------:|----:|:-------------|---------:|----------:|--------------------:|------------------:|---------------------:|
| baseline |          0 |   5 | 100 [57-100] |        0 |         0 |                 0   |              1    |                   38 |
| baseline |          2 |   5 | 20 [4-62]    |       80 |         0 |                39.2 |              0.86 |                   29 |


## Experiment 2: unmapped obstacle, with vs without replanning

| policy   | replanning   |   n | success %    |   fall % |   stuck % |   wall contacts/run | SPL (successes)   | time s (successes)   |   replans |
|:---------|:-------------|----:|:-------------|---------:|----------:|--------------------:|:------------------|:---------------------|----------:|
| baseline | False        |   5 | 0 [0-43]     |        0 |       100 |               139.4 | -                 | -                    |         0 |
| baseline | True         |   5 | 100 [57-100] |        0 |         0 |                15.8 | 0.83              | 59                   |         1 |

