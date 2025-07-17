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
- There are two files regarding the road network of Milan. The network is retrived using OSMnx and graph_from_place function and saved as `milan_drive.graphml`. `myMilan_drive.gpkg` file is a geopackage file with two layers of nodes and edges and is saved as a geopackage after turning the graph into GeoDataframes of nodes and edges. Since openstreetmap data might be updated and changed, this process is done once and the files are saved to avoid potential conflicts during the procedure of this research. 

