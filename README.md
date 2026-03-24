# Predicting-Thermodynamically-Preferred-Conformational-States-of-LC3-and-Its-Mutants
Developed a machine learning framework using ESM-2 embeddings and autoencoders to predict LC3 protein conformational states and free-energy differences, validated with MD simulations and experimental data.


This project aims to develop a machine learning framework that predicts the thermodynamically preferred
conformational states of LC3 protein and its mutants using ESM-2 embeddings and autoencoder
architectures. The model will classify LC3 sequences into functionally relevant conformational states,
with thermodynamic interpretation validated via correlation with free-energy estimates from molecular
dynamics simulations or experimental data.To achieve this, a comprehensive dataset of LC3 structures
and mutants will be curated from experimentally resolved protein entries. ESM-2 will be used to generate
sequence embeddings that capture evolutionary, physicochemical, and structural characteristics of LC3
variants. These embeddings will be processed through an autoencoder to learn a compact latent
representation of conformational variability. Within this latent space, the model will identify clusters
corresponding to distinct conformational states and infer inter-state transition probabilities. Using the
Boltzmann relation, these transitions will be mapped to relative free-energy differences, providing a
thermodynamic interpretation of the predicted conformational landscape.Thermodynamic correlations
will be established by benchmarking model predictions against free-energy profiles derived from
molecular dynamics (MD) simulations and experimental thermodynamic measurements, ensuring
scientific validity and interpretability. The resulting framework offers a sequence-only, data-driven
approach for probing how specific mutations alter conformational preferences and thermodynamic
stability. This methodology lays the foundation for scalable prediction of conformational energetics in
LC3 and potentially other autophagy-related proteins.
