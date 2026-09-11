# RepoRT — Liquid Chromatography Retention Times

A collection of small-molecule retention times and chromatographic
conditions for developing and evaluating retention-time prediction models.

## Source

[Original RepoRT repository](https://github.com/michaelwitting/RepoRT)

[Processed datasets](https://github.com/michaelwitting/RepoRT/tree/master/processed_data)

[Data documentation](https://github.com/michaelwitting/RepoRT/blob/master/DataDescription.md)

## Contents

- Measured liquid-chromatography retention times
- Molecular structures and chemical identifiers, including SMILES and InChI
- Column information, temperature, and flow rate
- Mobile-phase compositions and gradient information
- Different separation modes, including reversed-phase LC and HILIC

Available metadata varies between datasets.

## Suggested uses

- Predict retention times from molecular structures.
- Compare machine-learning and deep-learning models.
- Study how chromatographic conditions affect retention.
- Support small-molecule identification.
- Teach regression and model evaluation.

## Data quality and preparation

Retention times depend on the chromatographic method.
For a beginner exercise, start with one well-documented method.

When combining datasets, account for differences in columns,
mobile phases, gradients, and other experimental conditions.

Check missing metadata and repeated compounds. Choose evaluation
splits that match the goal: predicting new compounds or transferring
predictions to new chromatographic methods.

## Licence

The repository provides a Creative Commons Attribution-ShareAlike
4.0 International licence (CC BY-SA 4.0).

Follow its attribution and ShareAlike requirements when redistributing
or adapting covered material.

[Original licence](https://github.com/michaelwitting/RepoRT/blob/master/LICENSE)

This catalogue entry links to the original data; no dataset copy is hosted here.

## Citation

Kretschmer, F., Harrieder, E.-M., Hoffmann, M. A., Böcker, S.,
and Witting, M. (2024).

RepoRT: a comprehensive repository for small molecule retention times.
Nature Methods, 21, 153–155.

https://doi.org/10.1038/s41592-023-02143-z

Record the RepoRT release or commit used in your work and retain
the original dataset references where applicable.

[Back to the catalogue](README.md)
