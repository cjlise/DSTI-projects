# Simulated Annealing Lab report
## EXERCISE 1
```Python
def fitnessFunc(x):
    m = 1 + math.cos(0.04 * x)**2
    n = math.exp(-x**2/20000.0)
    return m * n 
```

## EXERCISE 2
Wave fitness
![Wave fitness](https://github.com/cjlise/DSTI-projects/blob/master/python_WaveFitness.png)


## EXERCISE 3
The chart of the trajectory of the annealing algorithm with T=10 along the fitness surface is displayed below:
![Annealing alogorithm](https://github.com/cjlise/DSTI-projects/blob/master/SAnnealing-Ex3.png)

