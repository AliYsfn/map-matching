# ST Map Matching Algorithm

This repository contains a Jupyter Notebook implementing the Spatial-Temporal (ST) Map Matching algorithm. The project matches GPS trajectory points to a road network, refining noisy GPS data by selecting candidate road segments, computing spatial and temporal probabilities, and finding the most probable path.

## Features

- Candidate point selection using spatial buffers  
- Observation and transition probability computations
- Temporal similarity based on GPS speed and road speed limits  
- Construction of candidate graphs (DAG) and shortest path finding  
- Evaluation metrics  
- visualization of matched points and paths  

## Files

- `ST_Matching.ipynb`: Main Jupyter Notebook with full implementation and explanation  

