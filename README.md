# Single-cell proteomics analysis in python

This repository contains analyses done for [Ultra-high sensitivity mass spectrometry quantifies single-cell proteome changes upon perturbation](https://doi.org/10.15252/msb.202110798), A Brunner, ..., M Mann, Molecular Systems Biology (2022).

The analyses were performed in python and heavily use [scanpy](https://scanpy.readthedocs.io/en/stable/) and [anndata](https://anndata.readthedocs.io/en/latest/) functionality. Both python packages were originally created for single cell transcriptomics analyses, but can to a large part also directly be applied to protein data and thus help kick off this exciting new field! Especially scanpy enables easy data visualizations like PCA plots or UMAPs and provides some ready to use analysis methods like assigning cell cycle stage scores to single cells given some cell cycle markers.
