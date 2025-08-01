# Surrogate Model for Predicting Application Runtime

This repository contains the code and data processing scripts used to train a surrogate model for application runtime prediction.

## Dataset

We use two datasets, D1 and D2, which are publicly available at:

- [D1 and D2 on Zenodo](https://zenodo.org/records/16667461)

## Files

- `generate_graph_data.ipynb`:  
  Processes the raw data to generate feature tensors `X`, labels `Y`, and the adjacency matrix used for modeling.

- `smart.ipynb`:  
  Loads the preprocessed data and trains the surrogate model for runtime prediction.

## Notes

- All identifying information has been removed to comply with double-blind review requirements.
- For any questions or issues, please refer to the paper submission context.