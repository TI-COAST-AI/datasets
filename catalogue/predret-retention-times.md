# PredRet — Retention Times Across Chromatographic Systems

An experimental liquid-chromatography retention-time database
with a tool for predicting retention times by mapping between systems.

## Source

[Original PredRet website](https://predret.org/)

[Access and download instructions](https://predret.org/how-to-use-predret/)

[Prediction and data interface](https://predret.org/retention-time-prediction/)

The interface requires login. According to the documentation,
the “Get all data” tab provides experimental retention-time data
for the entire database or selected chromatographic systems.

The documentation was checked for this catalogue; a current export
and record count have not been verified.

## Contents

The documentation describes:

- Experimental retention times, with submissions specified in minutes.
- Compound names and PubChem identifiers or InChI.
- Chromatographic method identifiers.
- System descriptions covering column type, column description,
  eluents, pH category, and additives.

Predicted retention times are separate outputs of the modelling tool.
They should not be treated as experimental measurements.

## Suggested uses

- Explore retention-time relationships between chromatographic methods.
- Develop and evaluate retention-time mapping models.
- Teach regression, prediction intervals, and model validation.
- Support compound identification using retention-time evidence.

PredRet's own approach uses compounds measured in multiple systems
to learn mappings between those systems. It does not predict
retention solely from molecular structure.

[How PredRet works](https://predret.org/how-predret-works/)

## Data quality and preparation

Preserve chromatographic system identifiers when preparing data:
retention time depends on the experimental method.

Check reported compound identities, unusual values, and changes
in chromatographic conditions over time. PredRet notes limitations
associated with ambiguous structures and stereochemistry.

Its prediction intervals should not be used as strict exclusion
rules for compound identification.

[Source-specific limitations](https://predret.org/a-few-words-of-caution/)

RepoRT lists PredRet among its contributing collections. Check
overlapping compounds, methods, and measurements before combining
them or using one collection for training and the other for testing.

[RepoRT source list](https://github.com/michaelwitting/RepoRT#contributors)

For method-transfer evaluation, keep evaluation measurements out
of the data used to fit the mapping.

## Licence

PredRet states that its website data is licensed under
Creative Commons Attribution-ShareAlike 4.0 International
(CC BY-SA 4.0).

Credit the source, link to the licence, and indicate modifications.
Shared adaptations must follow the applicable ShareAlike terms.

[PredRet data licence statement](https://predret.org/how-to-use-predret/)

[CC BY-SA 4.0 licence](https://creativecommons.org/licenses/by-sa/4.0/)

This catalogue links to the original data; no dataset copy is hosted here.

## Citation

Stanstrup, J., Neumann, S., and Vrhovšek, U. (2015).

PredRet: Prediction of Retention Time by Direct Mapping between
Multiple Chromatographic Systems.

Analytical Chemistry.

https://doi.org/10.1021/acs.analchem.5b02287

[Official publication listing](https://predret.org/publications/)

Record the retrieval date and selected chromatographic systems.
Retain original contributor references where provided.

[Back to the catalogue](README.md)
