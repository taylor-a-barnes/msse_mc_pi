# Using Monte Carlo Simulation to Evaluate Pi

The code in `src/main.cpp` implements a very simple Monte Carlo simulation to estimate the value of Pi.
For more information about the math behind this application, see [this link](https://www.geeksforgeeks.org/estimating-value-pi-using-monte-carlo/).

You can build the code with:

```
mkdir build
cd build
cmake ..
cmake --build .
```

You can then run the code with:
```
mpiexec -n 1 ./mcpi
```

Use MPI to parallelize this code.
