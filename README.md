# Startegies to solve Set-Cover Problem

## Strategies used
- Hill Climbing with single mutation
- Hill Climbing with multiple mutations
- Hill Climbing with multiple mutations strenght
- Simulated Annealing with multiple mutations

## Results

The result are computed with:
- MAX_STEPS = 1000
- BUFFER_SIZE = 13

### Hill Climbing with single mutation

|  UNIVERSE_SIZE | NUM_SETS  |DENSITY   |  COSTS | 
|---|---|---|---|
|  100 | 10  | 0.2  |  -289 |   
|  1_000 |  100 |  0.2 |  -6_520.12 |   
|  10_000 | 1_000  | 0.2  |  -766_944.45 | 
|  100_000 | 10_000  | 0.1  | -113_984_650.28  | 
|  100_000 | 10_000  | 0.2 | -246_658_890.72 | 
|  100_000 | 10_000  | 0.3 |  | 


### Hill Climbing with multiple mutation

|  UNIVERSE_SIZE | NUM_SETS  |DENSITY   |  COSTS | 
|---|---|---|---|
|  100 | 10  | 0.2  |  -289 |   
|  1_000 |  100 |  0.2 |  -6_520.12 |   
|  10_000 | 1_000  | 0.2  | -787_839.88  | 
|  100_000 | 10_000  | 0.1  |  -113_928_819.72 | 
|  100_000 | 10_000  | 0.2 | -246_148_120.01 | 
|  100_000 | 10_000  | 0.3 |  | 


### Hill Climbing with multiple mutations strenght

|  UNIVERSE_SIZE | NUM_SETS  |DENSITY   |  COSTS | 
|---|---|---|---|
|  100 | 10  | 0.2  | -289  |   
|  1_000 |  100 |  0.2 |  -7_357.59 |   
|  10_000 | 1_000  | 0.2  |  -814_636.96 | 
|  100_000 | 10_000  | 0.1  |  -113_304_292.79 | 
|  100_000 | 10_000  | 0.2 | -249_484_875.23 | 
|  100_000 | 10_000  | 0.3 |  | 



### Simulated Annealing with multiple mutations

|  UNIVERSE_SIZE | NUM_SETS  |DENSITY   |  COSTS | 
|---|---|---|---|
|  100 | 10  | 0.2  | -289  |   
|  1_000 |  100 |  0.2 |  -6_495.79 |   
|  10_000 | 1_000  | 0.2  |  -1_046_828.62 | 
|  100_000 | 10_000  | 0.1  |  -104_595_829.98 | 
|  100_000 | 10_000  | 0.2 | -225_883_266.26 | 
|  100_000 | 10_000  | 0.3 |  | 
