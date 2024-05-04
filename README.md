# Geometric ML in Neurology

APMTH 220 Final Project - Hao Zhao

Please see ABIDE.ipynb in main repository for all code needed to run the analysis pipeline, including markdown cells providing additional detail. The notebook is split into five sections.

Section 1 ("Setup"): Imports all necessary packages (primarily from sklearn and pytorch for general ML tools, nilearn for analysis of fMRI data, and torch-geometric for geometric ML tools).

Section 2 ("Load data"): Loads fMRI and atlas data, performs processing to convert fMRI data into multigraph or single-graph datasets.

Section 3 ("Graph Neural Network"): Performs multiscale GNN analysis as described in project. Also performs single-graph GNN analysis which we did not include in the paper.

Section 4 (Shallow Embedding Followed by SVM): Performs shallow embedding of single-graph dataset followed by SVM for classification.

Section 5 ("Convolutional Neural Network"): Performs conventional CNN on correlation data.
