# Polymer Property Prediction using ChemBERTa Transformer

This project applies **Deep Learning** and **Chemoinformatics** to establish a Structure-Property Relationship (SPR) for polymers. It leverages a Transformer-based Language Model to predict crucial physical properties directly from their chemical structures.


* **Predictive Modeling:** Trained a **regression model** using the pre-trained **ChemBERTa** Transformer to predict five key polymer properties ($T_g$, $T_c$, Density, FFV, $R_g$) directly from **SMILES** chemical representations.
* **Data Pipeline:** Engineered a comprehensive data pipeline utilizing **RDKit** to aggregate, clean, and unify thousands of polymer entries from multiple sources, ensuring high-quality input for the model.

