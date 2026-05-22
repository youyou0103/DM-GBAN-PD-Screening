DM-GBAN-PD-Screening



A lightweight project page for Parkinson’s disease drug screening based on drug–target interaction prediction, virtual screening, and molecular docking validation.



Overview



This project presents my ongoing research on deep learning based Parkinson’s disease drug screening.



The overall pipeline includes:



drug–target interaction prediction

external candidate virtual screening

novelty analysis based on similarity and scaffold

molecular docking validation on MAOB

result visualization and interpretation

Project Motivation



The goal of this project is to identify potential candidate compounds for Parkinson’s disease related targets, with a focus on MAOB-oriented screening and validation.



Technical Route



The project is organized as the following pipeline:



Build a drug–target prediction framework based on molecular graph and protein sequence information

Use the trained model to score external candidate compounds

Perform similarity analysis, scaffold deduplication, and diversity-based filtering

Select representative candidates for molecular docking

Validate structural binding rationality using docking and visualize the binding poses

My Contributions



My work in this project mainly includes:



constructing a DTA prediction framework for PD-oriented drug screening

introducing Graph Transformer and Dual-Mask BAN based ideas for multimodal feature fusion

completing external virtual screening on MAOB-related candidate compounds

performing similarity analysis, scaffold filtering, and diversity-based selection

completing molecular docking and visualization for representative MAOB candidates

organizing the full workflow into a reproducible research pipeline

Tools and Environment

Python

PyTorch

RDKit

TDC / BindingDB benchmark

AutoDock Vina

PyMOL

Current Status



This project is currently under preparation for SCI submission.



Note



This repository is a lightweight project page for research presentation.

Core implementation details and full experimental contents will be released after paper publication.

