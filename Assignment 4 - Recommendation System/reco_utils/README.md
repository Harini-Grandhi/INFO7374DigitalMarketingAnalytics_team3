# Recommender Utilities

This package (reco_utils) contains functions to simplify common tasks used when developing and evaluating recommender systems. A short description of the sub-modules is provided below. For more details about what functions are available and how to use them, please review the doc-strings provided with the code.

See the [online documentation](https://readthedocs.org/projects/microsoft-recommenders/).


## [Common](common)

This submodule contains high-level utilities for defining constants used in most algorithms as well as helper functions for managing aspects of different frameworks: gpu, spark, jupyter notebook.

## [Dataset](dataset)

Dataset includes helper functions for interacting with Azure Cosmos databases, pulling different datasets and formatting them appropriately as well as utilities for splitting data for training / testing.

### Data Loading

There are dataloaders for several datasets. For example, the movielens module will allow you to load a dataframe in pandas or spark formats from the MovieLens dataset, with sizes of 100k, 1M, 10M, or 20M to test algorithms and evaluate performance benchmarks.

```python
df = movielens.load_pandas_df(size="100k")
```
