# Problem Statement
Design a tripeptide model (Ala-X-Ala, where X is any amino acid of your choice). Analyze the phi (φ) and psi (ψ) backbone dihedral angles, focusing on steric clashes. Construct a Ramachandran plot to visualize its stable and unstable conformational space.

# Solution

## Getting the desired tripeptide:
- We first went to the CHEBI database and searched for any existing tripeptides.
- We found an full list of tripeptides and in that list we searched for the ones which were in the Ala-X-Ala format.
- We finally found one that matched the format and it was Ala-Leu-Ala.
- So the "X" amino acid is Leucine.
- Link for [Ala-Leu-Ala](/https://www.ebi.ac.uk/chebi/searchId.do;jsessionid=F296D1D805B17192EB96C5755B09280F?chebiId=CHEBI%3A158283)
- We then downloaded the SDF file of it's structure and projected it in PyMOL.
- The following is the structure that we saw in PyMOL:
![alt text](/ChEBI_158283.png)

## Calculating the phi (φ) and psi (ψ) backbone dihedral angles
- PyMOL>get_dihedral (resi 2 and name C), (resi 5 and name N), (resi 10 and name C), (resi 8 and name C)
 cmd.get_dihedral: 180.000 degrees.

|Residue|Backbone Atoms|
|-|-|
|Residue 1 (Ala)|C (2), O (3)|
|Residue 2 (Leu)|N (5), C (7), CA (8), C (9)|
|Residue 3 (Ala)|N (11), C (12), CA (13), C (18)|



## Plotting the Ramachandran Plot of the Tripeptides
-
