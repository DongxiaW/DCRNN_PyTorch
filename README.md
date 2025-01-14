# Accelerating Stochastic Simulation with Interactive Neural Processes

This repository is a PyTorch implementation of Accelerating Stochastic Simulation with Interactive Neural Processes.

## Requirements
* torch
* scipy>=0.19.0
* numpy>=1.12.1
* pandas>=0.19.2
* pyyaml
* statsmodels
* tensorflow>=1.3.0
* torch
* tables
* future

To install requirements:
```
pip install -r requirements.txt
```
## Model Training and Evaluation for SEIR Simulator
```
cd leam_us/seir
```
Directly run *.ipynb using Google Colab.
## Model Training and Evaluation for LEAM-US Simulator
```
cd leam_us/random
python dcrnn_train_pytorch.py
cd ../maxzdiff
python dcrnn_train_pytorch.py
cd ../meanstd
python dcrnn_train_pytorch.py
cd ../maxentropy
python dcrnn_train_pytorch.py
cd ../random_maxzdiff
python dcrnn_train_pytorch.py
```
