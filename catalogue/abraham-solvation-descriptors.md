# Abraham Solvation Descriptors

Molecular solute descriptors from the Reaction Mechanism Generator
(RMG) database, suitable for exploring solvation models and machine learning.

## Source

[View the original dataset on GitHub](https://github.com/ReactionMechanismGenerator/RMG-database/blob/main/input/solvation/libraries/solute.py)

Maintained by the RMG Team.

## Contents

The file inspected on 11 September 2026 contains 450 entries,
including molecular structures, source notes, and six descriptors:

| Descriptor | Meaning |
|---|---|
| E | Excess molar refraction |
| S | Dipolarity/polarizability |
| A | Hydrogen-bond acidity |
| B | Hydrogen-bond basicity |
| V | McGowan characteristic volume |
| L | Log gas-to-hexadecane partition coefficient |

Format: structured Python data, not CSV.

## Suggested uses

- Predict descriptors from molecular structures.
- Compare machine-learning models.
- Explore relationships between molecular structure and solvation.
- Teach explainable AI using chemically meaningful targets.

## Data quality

The collection combines literature-derived descriptors and
computationally fitted values, including entries labelled “COSMO fit”.

Separate these sources and check duplicate structures before training.
The 450 entries do not necessarily represent 450 unique molecules.

## Licence

Redistribution permission is unconfirmed. This catalogue links to
the original source; it does not host a copy of the dataset.

## Citation

Follow the source notes for each entry used. The file header cites:

Abraham et al., J. Chem. Soc., Perkin Trans. 2 (1994), 1777–1791.
https://doi.org/10.1039/P29940001777

Also acknowledge RMG-database and record the source version used.

[Back to the catalogue](README.md)
