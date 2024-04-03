# Description
This repository hosts a Python script focusing on the computation and comparison of protein (pili) interfaces across different structures. It parses protein structure data, calculates distances between residues, generates and compares contact maps, and visualizes interface differences. The tool is used to understand the nuances of pili cryo-EM structure interactions and their variability under various assembly conditions

# Key Features
Protein Structure Parsing: Uses Biopython to load and manipulate protein structures from PDB files.
Residue Distance Calculation: Offers multiple modes for calculating distances between residues, including options to focus on alpha carbons, average positions, or minimum atom distances.
Contact Map Generation: Produces binary or numerical contact maps for intra- and inter-protein interfaces, facilitating the analysis of protein interaction sites.
Interface Comparison: Compares protein interfaces across different structures (e.g., in vivo vs. in vitro), highlighting conserved and variable interaction patterns.
Visualization: Uses Matplotlib and seaborn to generate intuitive visual representations of the data, such as heat maps and bar charts, to illustrate differences in protein interfaces.
Data Export: Summarizes comparison results in CSV files, enabling further statistical analysis.

# References:
Zyla, D., Wiegand, T., Bachmann, P., Zdanowicz, R., Giese, C., Meier, B.H., Waksman, G., Hospenthal, M.K., & Glockshuber, R. (2024). The assembly platform FimD is required to obtain the most stable quaternary structure of type 1 pili. Nature Communications. Published: xx xx 2024.
