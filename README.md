# Integrated Machine Learning, Pharmacophore Modelling, Molecular Docking and in vitro validation Pipeline for the Identification of Novel EZH2 Inhibitors as potential anti-cancer agents
Enhancer of Zeste Homolog 2 (EZH2) is the catalytic subunit of the Polycomb Repressive Complex 2 (PRC2), responsible for trimethylation of histone H3 at lysine 27 (H3K27me3), a key epigenetic mark associated with tumour suppressor gene silencing. EZH2 is overexpressed across multiple malignancies including breast, lung, prostate, and ovarian cancers, making it a high-priority therapeutic target.

## 📌 EZH2 Inhibitor Discovery Pipeline
A sequential computational pipeline integrating machine learning classification, ligand-based pharmacophore modelling, and molecular docking for the identification of novel EZH2 methyltransferase inhibitors — with in vitro biochemical validation.

✅ **Machine Learning Classification** — Four classifiers (RF, SVM, KNN, XGBoost) trained on PubChem fingerprints to screen the Maybridge compound library

✅ **Ligand-Based Pharmacophore Filtering** — Phase-generated pharmacophore hypothesis (DHHRR_1) used to filter ML hits

✅ **Molecular Docking** — Glide XP docking against EZH2 crystal structure (PDB: 5WG6)

![image alt](https://github.com/krishna95nikita/EZH2_Data/blob/a1dda7931c8715a6c340b67640f476bb3e6aafca/graphical_abstract.jpg)


## Installation & Dependencies ##

### Prerequisites ###

✅Python 3.12.4

✅Java Runtime Environment (JRE) — required for PaDEL fingerprint software

✅PaDEL-Descriptor — download separately

✅Schrödinger Maestro (licensed) — required for pharmacophore modelling and molecular docking steps.
