# Problem Statement
Design a tripeptide model (Ala-X-Ala, where X is any amino acid of your choice). Analyze the phi (φ) and psi (ψ) backbone dihedral angles, focusing on steric clashes. Construct a Ramachandran plot to visualize its stable and unstable conformational space.

# Solution

## Getting the desired tripeptide:
- We first went to the CHEBI database and searched for any existing tripeptides.
- We found an full list of tripeptides and in that list we searched for the ones which were in the Ala-X-Ala format.
- We finally found one that matched the format and it was Ala-Leu-Ala.
- So the "X" amino acid is Leucine.
- Link for [Ala-Leu-Ala](https://pubchem.ncbi.nlm.nih.gov/compound/7016119)
- We then downloaded the SDF file of it's structure and projected it in PyMOL.
- We then visualised the structure using PyMOL: ![alt text](A-L-A.pse)
- We also visualised it using ChimeraX and found the ![clashes](alaleuala.cxs)

Some features of this tripeptide:
- Formula: C12H23N3O4
- Net Charge: 0
- Average Mass: 273.333
- Monoisotopic Mass: 273.16886
- Chemical Roles: Bronsted Base
- IUPAC Name: L-alanyl-L-leucyl-L-alanine

## Calculating the phi (φ) and psi (ψ) backbone dihedral angles & Plotting the Ramachandran Plot of the Tripeptides
Now we construct our own Ala-Leu-Ala tripeptide on ChimeraX and find the angles to be: φ = -86.4526° and ψ = 143.018°

We then plotted the values in the ![alt test](RamChanPlot-AlaLeuAla.png)

## Conclusion
From the above, we can conclude that the tripeptide Ala-Leu-Ala has a Antiparallel beta sheet structure.
