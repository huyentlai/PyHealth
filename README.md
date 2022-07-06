# PyHealth

## Environment
- pytorch: 1.12.0
- pytorch-lightning: 1.6.4

## Dataset
- MIMIC-III
- MIMIC-IV
- eICU
- OMOP CDM

## Input
- Condition code
- Drug code
- Procedure code

## Output
- Mortality prediction (binary classification)
- Length-of-stay estimation (multi-class classification)
- Drug recommendation (multi-label classification)
- Phenotyping (multi-label classification)

## Model






### datasets.py
- provide process for MIMIC-III, eICU and MIMIC-IV
- datasets.df gives the clean training data, which can be input into the task Class objects, such as tasks.DrugRec.
