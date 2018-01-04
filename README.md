# Pointnet++ PyTorch implementation

This repository is for the NIPS Implementation Challenge by Nurture.ai

## Set up
1. Make a new virtualenv in Python3
2. python setup.py
3. python main.py

## Files
setup.py --- download ModelNet40 pointcloud dataset by Stanford and install the required packages
dataset.py --- custom PyTorch dataset loader for ModelNet40
models.py --- model definitions
logger.py --- saves model loss for tensorboard visualization, borrowed from **** TODO

status:
dataset(ModelNet40) : done
model:
	sampling: 
		FPS: in progress
	grouping: 
		knn: in progress
		ball query: in progress
	pointnet: in progress


Todo:
add citation 
use ipynb as demo 
