# GNN-based Vertex Reconstruction for ANNIE

Graph Neural Network (GNN) based vertex reconstruction for the **ANNIE neutrino experiment**, developed during a research internship at **NCSR Demokritos**.

The project uses detector hit information to reconstruct neutrino interaction vertices using **GraphNeT** and the **DynEdge** architecture.

## Pipeline

ROOT data → Parquet preprocessing → Event-level graph construction → DynEdge GNN → Vertex prediction (X, Y, Z) → Performance evaluation

## Technologies

Python · PyTorch · PyTorch Geometric · GraphNeT · DynEdge · ROOT · CUDA

## Project Presentation

The repository includes a presentation describing the preprocessing pipeline, model architecture, training procedure, and reconstruction results.

> Research code and collaboration data are not publicly distributed.
