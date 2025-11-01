# JK3_protein_drug_effectiveness
Machine learning driven predictions for Janus Kinase 3 Protein Drug Effectiveness. This study explores the application of machine learning, including deep learning-based models, to predict the efficacy of drugs targeting JAK3.

## Summary

We developed predictive models to estimate pIC50 values (drug potency) from molecular SMILES notations using:
- Traditional machine learning (Random Forest, XGBoost, MLP) with molecular descriptors
- Large language models (PubChem10M, ChemBERTa) fine-tuned for molecular structures

**Dataset**: 4,154 drug compounds from ChEMBL database

**Best Result**: Random Forest with molecular descriptors achieved MSE of 0.75 (RÂ² = 0.67)

## Key Findings

- Traditional molecular descriptors with ensemble methods outperformed deep learning approaches
- PubChem10M transformer model showed promising results (MSE: 0.81) when combined with XGBoost
- The models can effectively filter drug candidates for further testing, potentially accelerating drug discovery

## Authors

**Awani Gadre** (Santa Clara University), **Sindhu Ghanta** (AIClub), **Bharath Ramsundar** (Deep Forest Sciences)

## Citation

```
Gadre, A., Ghanta, S., & Ramsundar, B. (2024). 
Machine Learning-Driven Predictions for Janus Kinase 3 Protein Drug Effectiveness.
```
