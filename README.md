# Geometric ML in Neurology

APMTH 220 Final Project - Hao Zhao

Please see ABIDE.ipynb in main repository for all code needed to run the analysis pipeline, including markdown cells providing additional detail. The notebook is split into five sections.

Section 1 ("Setup"): Imports all necessary packages (primarily from sklearn and pytorch for general ML tools, nilearn for analysis of fMRI data, and torch-geometric for geometric ML tools).

Update: Necessary packages must be installed as well; if the above detail on packages is not enough (possibly due to package versioning issues), we have additionally included a GNN_environment.yml file to build the entire conda environment to run the script. Additionally, we have included an ABIDE_sample.ipynb notebook which is a sample run of all cells in the ABIDE.ipynb notebook.

Section 2 ("Load data"): Loads fMRI and atlas data, performs processing to convert fMRI data into multigraph or single-graph datasets.

Section 3 ("Graph Neural Network"): Performs multiscale GNN analysis as described in project. Also performs single-graph GNN analysis which we did not include in the paper.

Section 4 (Shallow Embedding Followed by SVM): Performs shallow embedding of single-graph dataset followed by SVM for classification.

Section 5 ("Convolutional Neural Network"): Performs conventional CNN on correlation data.
