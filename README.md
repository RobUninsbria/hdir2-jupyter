README - Reproduce SYN Flood Attack Detection using (H-DIR)² Pipeline
======================================================================

This package contains all artifacts to reproduce the SYN Flood scenario
described in the H-DIR² framework (Hybrid-Distributed Information Retrieval
with Entropy and ARNN).

Included Files
--------------

1. reproduce_Syn_Flood.ipynb    - Jupyter notebook for local execution
2. datasets/Syn/                - Folder with CSV and RDF files

Steps Summary
-------------

- O1: RDF conversion from packet traces (c_*)
- O2: SQL-like temporal windowing over timestamps
- O3: Vectorization using statistical and entropy features (d_*)
- O4: ARNN training and inference for risk propagation
- O5: Risk score reification into RDF (f_*)
- O6: Final graph update (h_*)

Requirements
------------

- Python >= 3.8
- rdflib
- pandas, sklearn, torch

Execution
---------

Run the notebook step by step inside a Jupyter environment
(preferably inside Docker) where all dependencies are pre-installed.

Author
------

Generated with support from ChatGPT + user-local Docker lab.
