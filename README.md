# Spatiotemporal tuples

The simulation framework consists of Alchemist and ScaFi.

## Run experiments

Experiments are run by launching: 

```bash
$ ./gradlew XXXXX
```

Data will be generated in separate CSV files for each different simulation run. 

Plots can be generated from data through the following command (use Python 2.7):

```bash
$ ./plotter.py XXX.yml data .*YYY.* corr
```

## Project structure

- Source code for the API and simulations: `src/main/scala`
- Simulation descriptors: `src/main/yaml`
