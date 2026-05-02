#🧪 chem-it-lab
This repository documents my journey in computational chemistry, cheminformatics, and scientific programming.

#🎯 Goals
Combine chemistry with computer science
Build real-world projects in computational chemistry
Develop problem-solving and research skills

📅 Project Log
Day 1 — May 2, 2026
Focus: Functional group bioisosteric transformations using RDKit 

What I did: 
* Implemented carb_acid_to_tetrazole to replace carboxylic acid groups with tetrazole rings (a known bioisosteric substitution in medicinal chemistry)
* Implemented methyl_swapping to substitute methyl groups with chlorine atoms
* Generated visual outputs (before/after) to validate structural transformations
  
Challenges: 
* Debugged RDKit behavior: ReplaceSubstructs() returns multiple possible products (tuple), which initially caused crashes
* Needed to better understand how RDKit handles substructure matching vs full molecule representations

What I learned: 
* Clear distinction between SMILES (molecule representation) and SMARTS (pattern matching)
* Substructure search requires thinking in terms of patterns, not full molecules. Gave me the impression of the difference between the monomer and the repeating unit of the polymer made from it. I kinda associated with that.
* Bioisosteric modifications are not purely structural — their real impact depends on electronic effects, pharmacokinetics, and biological context

Next step:
* Implement halogen_scan function
* Study aromaticity and electronic effects
* Explore integrating molecular property calculations to evaluate transformations

🛠️ Tools & Topics
Python
Chemistry concepts
Algorithms / data structures
