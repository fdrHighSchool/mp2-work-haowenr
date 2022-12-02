# FizzBuzz
#### Respond to the following:

1. Fill out the following truth table:

| P  | Q  | P && Q | P \|\| Q |
|:--:|:--:|:------:|:--------:|
| T  | T  |   T    |     T    |
| T  | F  |   F    |     T    |
| F  | T  |   F    |     T    |
| F  | F  |   F    |     F    |


2. Prove a version of DeMorgan's Law:

| P  | Q  | P \|\| Q | ! (P \|\| Q) | !P | !Q | !P && !Q |
|:--:|:--:|:--------:|:------------:|:--:|:--:|:--------:|
| T  | T  |     T    |      T       |  F | F  |   F      |
| T  | F  |     T    |      F       |  F | T  |   F      |
| F  | T  |     T    |      F       |  T | F  |   F      |
| F  | F  |     F    |      F       |  T | T  |   T      |

3. What does DeMorgan's state and how did you prove it for the case above?
The complement of the product of all the terms is equal to the sum of the complement of each term, and i proved it by seeing if P and Q passes or fails
