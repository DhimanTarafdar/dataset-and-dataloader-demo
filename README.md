# Dataset and DataLoader Demo (PyTorch)

This is a simple practice notebook where I tried to understand how 
PyTorch Dataset and DataLoader work.

In this notebook I created a small classification dataset using 
`sklearn.datasets.make_classification` and then converted the data 
into PyTorch tensors.

After that I created a custom dataset class using `torch.utils.data.Dataset`.
The class contains three main functions:
- __init__()
- __len__()
- __getitem__()

Using this custom dataset I loaded the data with `DataLoader` so that 
the data can be used easily in training deep learning models.

## What I practiced in this notebook

- Creating a synthetic dataset
- Converting data to PyTorch tensors
- Creating a custom Dataset class
- Understanding __len__ and __getitem__
- Loading data using DataLoader
