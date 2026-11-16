# 502FinalProject
Reproducible code and dataset for final project. Includes optional Part 1: R-Code for Differential Gene Expression workflow and Part 2: Computational Workflow for protein structure prediction using AlphaFold and PYMOL.
# Part 1 Differential Expression analysis
This step is OPTIONAL and not required to complete the computational analysis in Part 2. If you would like to run the DE gene analysis:
1. Download the attached "GSE234729_all_available_GEO_metadata.csv" file.
2. Then download R Studio Desktop, and run the attached R markdown (rmd) code. The code generates output for African ancestry.
3. If you would like to do DE analysis for other sample groups replace all instances of "African" in the original code with "Asian" and repeat runs, then replace those instances with "European" and run the workflow again for a total of three outputs.
# Part 2 Protein structural analysis
PYMOL download is required.
1. Retrieve full-length 3D structure from AlphaFold. (Directions included in code.)
2. Visualize the full-length protein in PyMOL. (Run Python code in PYMOL)
3. Complete domain isolation by extracting the active amino acid region.
4. Identify and visualize 2D and 3D output.
5. Examine structural confidence using pLDDT and PAE results.

Save all outputs as you go.
