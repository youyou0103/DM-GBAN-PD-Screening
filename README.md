**DM-GBAN-PD-Screening**



A lightweight project page for Parkinson’s disease drug screening based on drug–target interaction prediction, external virtual screening, and molecular docking validation.



**Overview**

This repository presents my ongoing research on deep learning based Parkinson’s disease drug screening. The project is organized as a complete workflow including: drug–target interaction prediction, benchmark evaluation under multiple split settings, baseline comparison, ablation study, sensitivity analysis, external candidate virtual screening, novelty analysis based on similarity and scaffold, molecular docking validation on MAOB, and result visualization and interpretation.



**Research Scope**

This project focuses on PD-oriented candidate discovery with an emphasis on: generalization across different evaluation settings, robustness under new scaffold scenarios, multimodal representation learning for drug-target prediction, and downstream validation through candidate screening and docking.



**Technical Contributions**

My work in this project mainly includes: constructing a PD-oriented drug–target prediction framework based on molecular graph and protein sequence information; introducing Graph Transformer and Dual-Mask BAN based ideas for multimodal feature fusion; organizing benchmark experiments under random, cold-drug, scaffold, and PD-specific settings; conducting baseline comparison with representative DTI / DTA models; performing ablation studies for fusion architecture variants; carrying out sensitivity analysis and imbalance-learning strategy analysis; building an external virtual screening pipeline for MAOB-related candidate selection; and completing molecular docking validation and pose visualization for representative candidates.



**Benchmark and Validation Coverage**

The current project includes: BindingDB random split benchmark, BindingDB cold-drug benchmark, BindingDB scaffold benchmark, PD downstream validation, baseline comparison, ablation studies, sensitivity analysis, external screening, and molecular docking validation.



**Tools and Environment**

The project involves the following tools and frameworks: Python, PyTorch, RDKit, TDC / BindingDB benchmark, AutoDock Vina, PyMOL, and YAML-based configuration and experiment management.



**Repository Structure**

README.md: project overview and research scope  

results/experiment\_scope.txt: summary of completed experimental coverage  

results/benchmark\_overview.txt: overview of benchmark and evaluation settings  

results/screening\_overview.txt: overview of external virtual screening workflow  

results/docking\_overview.txt: overview of molecular docking workflow  

figures/README.txt: placeholder description for figures and diagrams



**Public Release Scope**

This repository is intended as a research project page rather than a full public code release. At the current stage, this repository mainly provides: project overview, technical scope, experimental coverage, and workflow summary. Core implementation details, full experimental scripts, and detailed result tables will be released after paper publication when appropriate.



**Current Status**

This work is currently under preparation for SCI submission.

