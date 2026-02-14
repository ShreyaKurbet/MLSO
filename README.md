# Distributed Random Forest using Apache Spark
Group: 53

# Objective
Implement and evaluate a distributed Random Forest using Apache Spark.

## Dataset
Synthetic dataset with:
- 50,000 samples
- 20 features
- Binary classification

## Experiments
Tested with partitions:
- 1
- 2
- 4
- 8

## Metrics
- Training Time
- Speedup
- AUC

## Results
Near-linear speedup observed.
AUC remains stable (~0.89).
