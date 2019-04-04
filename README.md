# VisualizationTool-Chemkin
Files for using the Visualization tool in Chemkin

1.	Accessing the files

The necessary files have been uploaded to the GitHub page. The files include two shell scripts (chemkin.sh and refineVisualization.sh) and one folder (graphviz).
1)	chemkin.sh – shell script for running the chemkin code (FILE)
2)	refineVisualization.sh – performing post-processing on the visualization output file (FILE)
3)	graphviz – Open source code used for generating the visualizations (FOLDER)

All the above files/folders need to be copied into your working directory.
A quick description about the above files. 
1)	chemkin.sh – The file has been modified to generate the visualization files
2)	refineVisualization.sh – The file generates the visualization files without rerunning the chemkin code. The file uses Cutoffrate, EquilibriumTolerance, to refine the reaction network to be visualized. rpa_visualizationMaster.out file, generated by the chemkin code in the OUT.d folder, is used as an input for this script.
3)	graphviz – Graphviz, an open-source package specified in DOT language is used for the visualization. DOT is a graph description language that defines the graph involving nodes and edges. Graphviz manipulates and renders the graph. The folder contains executables necessary to generate the visualization files.

Features in the visualization tool:
1) 
