# VT-Former: Vehicle Trajectory Prediction with Graph Attentive Tokenization and Transformer

[GitHub Repository](https://github.com/akanshamingwal/VT-Former.git)

## Overview
This project focuses on predicting vehicle trajectories using a combination of graph attention mechanisms and transformer models. The trajectories are modeled through a graph structure, where each vehicle is represented as a node defined by specific parameters, and the spatial relationships between vehicles are captured as edges. A transformer module enhances predictive accuracy by refining the trajectory representation.

## Project Structure

### Graph Construction
The input data for vehicle trajectories is organized in a graph structure:

- **Node Representation**: Each node represents a vehicle and is defined by four selected parameters that influence trajectory prediction.
- **Edge Representation**: Each edge captures the distance between vehicles, representing spatial relationships and interactions.

### Graph Attentive Tokenization
Graph attention mechanisms are applied to capture dynamic relationships within the graph. This allows the model to focus on the most influential nodes and edges, thereby improving the representation of interactions between vehicles.

### Transformer Module
A transformer model processes the graph structure, playing a crucial role in refining and enhancing trajectory predictions. The transformer's attention mechanism focuses on critical parts of the trajectory and learns dependencies across the spatial-temporal interactions represented in the graph.

## Key Components

- **Node Representation**: Each node is defined by four specific parameters that encapsulate essential information about each vehicle, contributing to the prediction accuracy.
- **Edge Representation**: The distance between vehicles is encoded as an edge, helping to capture the influence of nearby vehicles on each node’s trajectory.
- **Graph Attention Layer**: Applies attention mechanisms on the graph, allowing the model to weigh the importance of different nodes and edges in trajectory prediction.
- **Transformer Module**: Refines the representations learned by the graph attention layer, enhancing the model’s ability to capture both spatial and temporal dependencies.

## Getting Started

### Prerequisites
- Python 3.x
- Libraries: PyTorch, PyTorch Geometric, NumPy, Pandas

### Installation
Install the required packages:

```bash
pip install torch torch_geometric
pip install numpy
pip install pandas
pip install scikit-learn
