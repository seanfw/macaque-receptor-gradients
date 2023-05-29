README for macaque-receptor-gradients

This GitHub repository contains the scripts and data required for the analysis outlined in our research paper titled 
"Gradients of neurotransmitter receptor expression in the macaque cortex". 

This paper discusses our analysis of 109 cortical areas in the macaque monkey brain, as defined in the Julich Brain Macaque Maps.

Contents
This repository includes scripts that facilitate the following:

Surface representation of cyto- and receptor-architectonic atlas and receptor data.
Surface representation of neural density data.
Identification of receptor gradients.
Surface representation of dendritic data.
Analysis of cortical T1w/T2w data.
Cross-species functional alignment and functional connectivity data.
Analysis of human gene expression data.
Receptor expression within functional activity maps from NeuroQuery.
Statistical analysis.
Each of these analyses are performed using various datasets, including neural density data, dendritic data, T1w/T2w data, cross-species functional connectivity data, human gene expression data, and NeuroQuery data.

The repository genemapper (github.com/seanfw/genemapper) includes the necessary code for preprocessing and analyzing gene expression data on the cortical surface, with features for visualizing this data and correlating it with other anatomical and functional maps.

Usage
To use this repository, clone it to your local machine and follow the instructions contained in the scripts. Note that some scripts may require the installation of specific software tools such as Connectome Workbench or FreeSurfer.

Dependencies
The scripts in this repository are written in Python and may require specific Python packages. These include standard scientific and data analysis packages such as numpy, pandas, and scipy.

Data Availability
The necessary data for these analyses can be accessed via the following resources:
Julich Brain Macaque Maps, and surface represenatation of anatomical data: https://balsa.wustl.edu/study/W336
Receptor per neuron data (table format): https://search.kg.ebrains.eu/instances/e39a0407-a98a-480e-9c63-4a2225ddfbe4
Allen Human Brain Atlas: https://alleninstitute.org
Human Connectome Project (HCP): https://www.humanconnectome.org/
fMRI meta-analyses: neuroquery.org

Citation
If you use the code or data in this repository, please cite our research paper as the source, in addition to any other data sources.
Froudist-Walsh S; T Xu; M Niu; L Rapan; D Margulies; K Zilles; XJ Wang+ N Palomero-Gallagher+. “Gradients of receptor expression in the macaque neocortex”. Nature Neuroscience (2023 – in press) https://doi.org/10.1038/s41593-023-01351-2


Contributing
This repository is not actively maintained. However, we welcome any feedback or issues you may have. Feel free to submit these through GitHub's standard issue submission tool.

Contact
For any further inquiries or support, feel free to contact the repository maintainers.