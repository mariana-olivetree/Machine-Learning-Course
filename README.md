# CRISPR-Cas9 Repair Outcome Prediction

This project was developed as part of the Machine Learning for Life Sciences course at Ghent University. The goal is to build a predictive machine learning model that estimates repair outcomes of CRISPR-Cas9 editing experiments from DNA sequences.

## Challenge

The task is to predict **four key repair outcomes** of CRISPR-Cas9 genome editing:

- **Fraction_Insertions**: Fraction of indel reads resulting in insertions  
- **Avg_Deletion_Length**: Average deletion length observed  
- **Indel_Diversity**: Variability in indel types and lengths  
- **Fraction_Frameshifts**: Fraction of repair outcomes leading to frameshift mutations  

This is a **prediction-focused problem**: the main objective is to optimize **predictive accuracy** (R², MSE) rather than explain causal biological mechanisms.
