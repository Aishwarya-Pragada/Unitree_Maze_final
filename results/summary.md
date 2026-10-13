# Results summary

## Experiment 1: robustness vs disturbance severity (success % with 95% Wilson interval)

| policy   |   severity |   n | success %    |   fall % |   stuck % |   wall contacts/run |   SPL (successes) |   time s (successes) |
|:---------|-----------:|----:|:-------------|---------:|----------:|--------------------:|------------------:|---------------------:|
| baseline |        0   |  20 | 100 [84-100] |        0 |         0 |                 0   |              1    |                   32 |
| baseline |        0.5 |  20 | 100 [84-100] |        0 |         0 |                 0   |              1    |                   32 |
| baseline |        1   |  20 | 100 [84-100] |        0 |         0 |                 0.7 |              0.99 |                   35 |
| baseline |        1.5 |  20 | 85 [64-95]   |       15 |         0 |                 6.5 |              0.96 |                   37 |
| baseline |        2   |  20 | 20 [8-42]    |       80 |         0 |                17.1 |              0.9  |                   35 |
| dr       |        0   |  20 | 100 [84-100] |        0 |         0 |                 0   |              1    |                   34 |
| dr       |        0.5 |  20 | 100 [84-100] |        0 |         0 |                 0   |              1    |                   34 |
| dr       |        1   |  20 | 100 [84-100] |        0 |         0 |                 0   |              1    |                   34 |
| dr       |        1.5 |  20 | 100 [84-100] |        0 |         0 |                 0   |              1    |                   34 |
| dr       |        2   |  20 | 65 [43-82]   |       35 |         0 |                 0.3 |              0.98 |                   35 |


## Experiment 2: unmapped obstacle, with vs without replanning

| policy   | replanning   |   n | success %    |   fall % |   stuck % |   wall contacts/run | SPL (successes)   | time s (successes)   |   replans |
|:---------|:-------------|----:|:-------------|---------:|----------:|--------------------:|:------------------|:---------------------|----------:|
| baseline | False        |  20 | 0 [0-16]     |        0 |       100 |               135.8 | -                 | -                    |         0 |
| baseline | True         |  20 | 100 [84-100] |        0 |         0 |                 0.8 | 0.87              | 54                   |         1 |
| dr       | False        |  20 | 0 [0-16]     |        0 |        55 |               423.3 | -                 | -                    |         0 |
| dr       | True         |  20 | 100 [84-100] |        0 |         0 |                 0.5 | 0.88              | 52                   |         1 |

