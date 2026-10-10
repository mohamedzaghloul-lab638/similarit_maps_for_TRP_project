similarit_maps_for_TRP_project

2D Structural Similarity of Natural Compounds to Reference TRPM8 Ligands

Cheminformatics workflow (RDKit) for evaluating the 2D structural similarity between selected natural compounds and known reference TRPM8 modulators (GNE-551 and TC-I) using Morgan fingerprints and Tanimoto coefficients, together with atom-level similarity maps.

Overview

This repository contains a Jupyter notebook that:

Loads reference ligands and natural compounds from SMILES.
Computes Morgan fingerprints and pairwise Tanimoto similarity.
Generates atom-contribution similarity maps (RDKit SimilarityMaps).
Exports the maps as PNG images and bundles them into a ZIP file.
Compounds

Reference ligands (TRPM8): GNE-551, TC-I

Natural compounds: Cypellocarpin C, Rosmarinic acid, Jensenal, Avicularin

Results
Reference	Compound	Tanimoto
GNE-551	Cypellocarpin C	0.094  <img width="479" height="309" alt="image" src="https://github.com/user-attachments/assets/f7e7ff19-3f1c-4295-bbac-81d7d67104ff" />

GNE-551	Rosmarinic acid	0.103   <img width="457" height="303" alt="image" src="https://github.com/user-attachments/assets/c1635fa1-5294-4468-8cae-fa6b252a7d49" />

TC-I	Jensenal	0.091 <img width="494" height="315" alt="image" src="https://github.com/user-attachments/assets/d52816ea-227d-4635-9de9-216279b4646c" />

TC-I	Avicularin	0.077  <img width="461" height="304" alt="image" src="https://github.com/user-attachments/assets/9a205005-2192-4fe3-95ee-99c5b3d22914" />


All values fall in the range 0.077-0.103, indicating negligible 2D structural resemblance between the natural compounds and the reference ligands. The differences between individual values are not meaningful. The compounds therefore do not share a common scaffold with the known modulators and may represent structurally distinct chemotypes. Since 2D similarity does not necessarily reflect binding or functional similarity, further evaluation (e.g., molecular docking, pharmacophore matching, 3D shape similarity) is recommended.

