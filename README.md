# Data Wrangling Benchmarks

This repository is for benchmarking some data wrangling routines from Pandas (both with numpy and arrow backends), Polars and PySpark (on a single machine) against each other over two datasets.

## Build environment

## Prepare Data

### Download data

## Results

| task          | Pandas (numpy) | Pandas(arrow) | Polars | Pyspark |
|---------------|----------------|---------------|--------|---------|
| input         |                |               |        |         |
| output        |                |               |        |         |
| mean          |                |               |        |         |
| std           |                |               |        |         |
| quantile      |                |               |        |         |
| n_unique      |                |               |        |         |
| value_counts  |                |               |        |         |
| exp, log, etc |                |               |        |         |
| sorting       |                |               |        |         |
| string 1 |                |               |        |         |
| string 2 |                |               |        |         |
| aggregation 1 |                |               |        |         |
| aggregation 2 |                |               |        |         |
| aggregation 3 |                |               |        |         |
| datetime 1    |                |               |        |         |
| datetime 2    |                |               |        |         |
| rolling       |                |               |        |         |
| scipy 1       |                |               |        |         |
| scipy 2       |                |               |        |         |

string 1 = splitting by a substring  
string 2 = testing substring presence  
aggregation 1 = groupby by low-cardinality column  
aggregation 2 = groupby by high-cardinality column  
aggregation 3 = groupby by several columns + map the mean/std/nunique by groups  
datetime 1 = calculating year/month/days  
datetime 2 = resampling  
rolling = resampling  
scipy 1 = peak searching  
scipy 2 = ...  
