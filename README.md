# Problem Statement
Design a tripeptide model (Ala-X-Ala, where X is any amino acid of your choice). Analyze the phi (φ) and psi (ψ) backbone dihedral angles, focusing on steric clashes. Construct a Ramachandran plot to visualize its stable and unstable conformational space.

# Solution

## Getting the desired tripeptide:
- We first went to the CHEBI database and searched for any existing tripeptides.
- We found an full list of tripeptides and in that list we searched for the ones which were in the Ala-X-Ala format.
- We finally found one that matched the format and it was Ala-Leu-Ala.
- So the "X" amino acid is Leucine.
- Link for Ala-Leu-Ala: [/https://www.ebi.ac.uk/chebi/searchId.do;jsessionid=F296D1D805B17192EB96C5755B09280F?chebiId=CHEBI%3A158283](https://www.ebi.ac.uk/chebi/searchId.do;jsessionid=F296D1D805B17192EB96C5755B09280F?chebiId=CHEBI%3A158283)
- We then downloaded the SDF file of it's structure and projected it in PyMOL.
- We then visualised the structure using PyMOL: ![alt text](A-L-A.pse)

Some features of this tripeptide:
- Formula: C12H23N3O4
- Net Charge: 0
- Average Mass: 273.333
- Monoisotopic Mass: 273.16886
- Chemical Roles: Bronsted Base
- IUPAC Name: L-alanyl-L-leucyl-L-alanine

## Calculating the phi (φ) and psi (ψ) backbone dihedral angles
Now we construct our own Ala-Leu-Ala tripeptide on ChimeraX using various dihedral angles and secondary structures:
- Condition 1: alpha helix --> φ = -57 degree & ψ = -47 degree --> It had no clashes
- Condition 2: antiparalles beta-strand --> φ = -139 & ψ = 135 --> It had no clashes
- Condition 3: paralles beta-strand --> -119 & 113 --> It had no clashes
- Condition 4: MAN IDK IF ITS RIGHT OR WRONG AHFHWFHOFOHFWJEIHVUFIWJQPOHUFUIEFJOHINUEFJO

|Residue|Backbone Atoms|
|-|-|
|Residue 1 (Ala)|C (2), O (3)|
|Residue 2 (Leu)|N (5), C (7), CA (8), C (9)|
|Residue 3 (Ala)|N (11), C (12), CA (13), C (18)|



## Plotting the Ramachandran Plot of the Tripeptides
-
