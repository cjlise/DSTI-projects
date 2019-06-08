# Simulated Annealing Lab report
## EXERCISE 1
```Python
def fitnessFunc(x):
    m = 1 + math.cos(0.04 * x)**2
    n = math.exp(-x**2/200000.0)
    return m * n 


