# 🧪 Chem-IT Lab

A working notebook documenting my exploration of computational chemistry, cheminformatics, and scientific programming.

This repository records experiments, technical problems, observations, and lessons learned while building computational chemistry projects with Python and RDKit.

## Current Focus

* Molecular structure manipulation
* Cheminformatics with RDKit
* Substructure matching
* Bioisosteric transformations
* Molecular property analysis
* Scientific programming

## Experiment: Bioisosteric Transformations

### Objective

Explore how molecular structures can be modified computationally using common bioisosteric transformations.

### Implemented

* `carb_acid_to_tetrazole` — replaces carboxylic acid groups with tetrazole rings
* `methyl_swapping` — substitutes methyl groups with chlorine atoms
* Molecular structure visualization before and after transformations

### Technical Challenge

RDKit's `ReplaceSubstructs()` can return multiple possible products rather than a single molecule. Understanding this behavior was necessary to prevent unexpected tuple-related errors and correctly handle the generated structures.

### What I Learned

* The difference between **SMILES**, which represents molecular structures, and **SMARTS**, which describes structural patterns used for matching.
* Substructure matching requires thinking in terms of patterns rather than complete molecular representations.
* Bioisosteric transformations cannot be evaluated purely from structural similarity; electronic effects, pharmacokinetics, and biological context also matter.

One useful mental model I developed was the distinction between a complete molecular representation and a structural pattern, similar to the distinction between a polymer's monomer and its repeating unit.

## Current / Planned Experiments

* Halogen substitution scans
* Aromaticity and electronic effects
* Molecular property calculations
* Quantitative comparison of molecular transformations

## Tools

* Python
* RDKit
* Computational chemistry
* Cheminformatics
* Algorithms and data structures

## Why This Repository Exists

Unlike my finished projects, this repository is intended to preserve the reasoning and experimentation behind my technical work.

It serves as a record of questions I encountered, problems I solved, concepts I learned, and ideas I want to investigate further.
