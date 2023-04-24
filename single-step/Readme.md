# Single-step Retrosynthesis: methods and implementations

## Reactant-Based Methods
| Paper                                                        | Representation        | Year | Journal / Conference         | Code                                                         |
| ------------------------------------------------------------ | --------------------- | ---- | ---------------------------- | ------------------------------------------------------------ |
| Bayesian Algorithm for Retrosynthesis | SMILES | 2020 | JCIM | [pytorch](https://github.com/zguo235/bayesian_retro)                    |
| RetCL: A Selection-based Approach for Retrosynthesis via Contrastive Learning | Graph  |       2021  |    IJCAI       |[pytorch](https://github.com/hankook/RetCL)    |


## Template-Based Methods

| Paper                                                        | Representation        | Year | Journal / Conference         | Code                                                         |
| ------------------------------------------------------------ | --------------------- | ---- | ---------------------------- | ------------------------------------------------------------ |
| Neural-Symbolic Machine Learning for Retrosynthesis and Reaction Prediction | Molecular Fingerprint | 2017 | ChemistryA European Journal | [pytorch](https://github.com/linminhtoo/neuralsym)                    |
| Computer-Assisted Retrosynthesis Based on Molecular Similarity | Molecular Fingerprint | 2017 | ACS Central Science          | [link](https://github.com/connorcoley/retrosim)              |
| Prediction and Interpretable Visualization of Retrosynthetic Reactions Using Graph Convolutional Networks | Graph                 | 2019 | JCIM                         | [tensorflow](https://github.com/connorcoley/retrosim)        |
| Retrosynthesis Prediction with Conditional Graph Logic Network | Graph                 | 2019 | NIPS                         | [pytorch](https://github.com/Hanjun-Dai/GLN) |
| Data Augmentation and Pretraining for Template-Based Retrosynthetic Prediction in Computer-Aided Synthesis Planning | Molecular Fingerprint | 2020 | JCIM                         | [tensorflow](https://gitlab.com/mefortunato/template-relevance) |
| Deep Retrosynthetic Reaction Prediction using Local Reactivity and Global Attention | Graph                 | 2021 | JACS Au                      | [pytorch](https://github.com/kaist-amsg/LocalRetro) |
| Improving Few- and Zero-Shot Reaction Template Prediction Using Modern Hopfield Networks | Molecular Fingerprint | 2022 | JCIM                         | [pytorch](https://github.com/ml-jku/mhn-react) |



## Semi-Template Methods

| Paper                                                        | Representation        | Year | Journal / Conference         | Code                                                         |
| ------------------------------------------------------------ | --------------------- | ---- | ---------------------------- | ------------------------------------------------------------ |
| A Graph to Graphs Framework for Retrosynthesis Prediction    | Graph                 | 2020 | ICML                         | [pytorch](https://github.com/DeepGraphLearning/torchdrug)    |
| RetroXpert: Decompose Retrosynthesis Prediction like a Chemist | Graph + SMILES        | 2020 | NIPS                         | [pytorch](https://github.com/uta-smile/RetroXpert)           |
| Single-Step Retrosynthesis Prediction Based on the Identification of Potential Disconnection Sites Using Molecular Substructure Fingerprints | Molecular Fingerprint | 2021 | JCIM                         | [tensorflow](https://github.com/hasic-haris/one_step_retrosynth_ai) |
| Learning Graph Models for Retrosynthesis Prediction          | Graph                 | 2021 | NIPS                         | [pytorch](https://github.com/vsomnath/graphretro)            |
| RetroPrime: A Diverse, plausible and Transformer-based method for  Single-Step retrosynthesis predictions | SMILES                | 2021 | Chemical Engineering Journal | [pytorch](https://github.com/wangxr0526/RetroPrime)          |



## Template-Free Methods

| Paper                                                        | Representation    | Year | Journal / Conference                     | Code                                                         |
| ------------------------------------------------------------ | ----------------- | ---- | ---------------------------------------- | ------------------------------------------------------------ |
| Retrosynthetic reaction prediction using neural sequence-to-sequence models | SMILES            | 2017 | ACS Central Science                      | [tensorflow](https://github.com/pandegroup/reaction_prediction_seq2seq) |
| A Transformer Model for Retrosynthesis                       | SMILES            | 2019 | ICANN                                    | [tensorflow](https://github.com/bigchem/retrosynthesis)      |
| Predicting Retrosynthetic Reactions Using Self-Corrected Transformer Neural Networks | SMILES            | 2019 | JCIM                                     | [pytorch](https://github.com/Jh-SYSU/SCROP)                  |
| Automatic Retrosynthetic Route Planning Using Template-Free Models | SMILES            | 2020 | Chemical Science                         | [tensorflow](https://github.com/PKUMDL-AI/AutoSynRoute)      |
| State-of-the-art augmented NLP transformer models for direct and single-step retrosynthesis | SMILES            | 2020 | Nature Communications                    | [tensorflow](https://github.com/bigchem/synthesis)           |
| GTA: Graph Truncated Attention for Retrosynthesis            | SMILES            | 2021 | AAAI                                     | [pytorch](https://github.com/sw32-seo/GTA)                   |
| Valid, Plausible, and Diverse Retrosynthesis Using Tied Two-way Transformers with Latent Variables | SMILES            | 2021 | JCIM                                     | [pytorch](https://github.com/ejklike/tied-twoway-transformer/) |
| Molecular graph enhanced transformer for retrosynthesis prediction | SMILES + Graph    | 2021 | Neurocomputing                           | [pytorch](https://github.com/papercodekl/MolecularGET)       |
| Molecule Edit Graph Attention Network: Modeling Chemical Reactions as Sequences of Graph Edits | Graph             | 2021 | JCIM                                     | [pytorch+tensorflow](https://github.com/molecule-one/megan)  |
| Retrosynthesis prediction using grammar-based neural machine translation: An information-theoretic approach | Customized String | 2021 | Computers and Chemical Engineering       | [tensorflow](https://github.com/vupil/grammarTransformerReactionPrediction) |
| Substructure-based neural machine  translation for retrosynthetic prediction | Customized String | 2021 | Journal of Cheminformatics               | [pytorch](https://github.com/knu-chem-lcbc/fragment_based_retrosynthesis) |
| Towards understanding retrosynthesis by energy-based models  | SMILES            | 2021 | NIPS                                     | -                                                            |
| Chemformer: A Pre-Trained Transformer for Computational Chemistry | SMILES            | 2022 | Machine Learning: Science and Technology | [pytorch](https://github.com/MolecularAI/Chemformer)         |
| Retrosynthetic reaction pathway prediction through neural machine translation of atomic environments | Customized String | 2022 | Nature Communications                    | [pytorch](https://github.com/knu-lcbc/RetroTRAE)             |
| Root-aligned SMILES: A Tight Representation for Chemical Reaction Prediction | SMILES | 2022 |  Chemical Science |[pytorch](https://github.com/otori-bird/retrosynthesis)|



## Performance

Most of these results are obtained from their published papers, while some are obtained from additional experiments we conducted.

The accuracy obtained from our experiments is indicated in *italics*.


|                  | **USPTO-50K** |       |       |        |        |        | **USPTO-MIT** |       |       |        |        |        | **USPTO-FULL** |       |       |        |        |        |
| ---------------- | ------------- | ----- | ----- | ------ | ------ | ------ | ------------- | ----- | ----- | ------ | ------ | ------ | -------------- | ----- | ----- | ------ | ------ | ------ |
| **Model**        | **K = 1**     | **3** | **5** | **10** | **20** | **50** | **K = 1**     | **3** | **5** | **10** | **20** | **50** | **K = 1**      | **3** | **5** | **10** | **20** | **50** |
| **Reactant-based**   |               |       |       |        |        |        |               |       |       |        |        |        |                |       |       |        |        |        |
| Bayesian-Retro   | 47.5          | 67.2  | 77.0    | 80.3   |        |        |               |       |       |        |        |        |                |       |       |        |        |        |
| RetCL            | 71.3          | 86.4  | 92.0    | 94.1   | 95.0     | 96.4   |               |       |       |        |        |        |                |       |       |        |        |        |
| **Template-based**   |               |       |       |        |        |        |               |       |       |        |        |        |                |       |       |        |        |        |
| Neuralsym        | *45.3*          | *66.9*  | *74.2*  | *81.6*   | *86.2*   | *87.8*   | *52.7*          | *70.3*  | *75.4*  | *80.0*     | *83.0*     | *85.0*    | *42.7*          | *58.7*  | *63.4*  | *67.9*   | *70.8*   | 72.1*   |
| GLN              | 52.5          | 69.0    | 75.6  | 83.7   | 89.0     | 92.4   |               |       |       |        |        |        | 39.3           |       |       | 63.7   |        |        |
| LocalRetro       | 53.4          | 77.5  | 85.9  | 92.4   |        | 97.7   | 54.1          | 73.7  | 79.4  | 84.4   | *87.2*   | 90.4   | *39.1*           | *53.3*  | *58.4*  | *63.7*   | *67.5*   | *70.7*   |
| **Semi-template**    |               |       |       |        |        |        |               |       |       |        |        |        |                |       |       |        |        |        |
| G2Gs             | *41.8*          | *67.7*  | *75.1*  | *81.6*   | *85.7*   | *90.9*   |               |       |       |        |        |        |                |       |       |        |        |        |
| GraphRetro       | 53.7          | 68.3  | 72.2  | 75.5   | *75.6*   | *75.9*   | *41.1*          | *54.2*  | *57.3*  | *59.9*   | *60.3*   | *60.8*   | *24.8*           | *34.5*  | *36.9*  | *38.7*   | *39.5*   | *39.8* |
| RetroPrime       | 51.4          | 70.8  | 74    | 76.1   | *76.1*  | *81.3*   | *53.5*          | *70.4*  | *74.3*  | *76.9*   | *78.5*   | *84*    | *45.8*           | *61.6*  | *63.9*  | *70.3*   | *71.2*   | *72.6*   |
| **Template-free**    |               |       |       |        |        |        |               |       |       |        |        |        |                |       |       |        |        |        |
| Transformer      | 42.7          | *63.9*  | *69.8*  | *71.1*   | *72.8*   | *74.0*   | *53.8*          | *70.5*  | *75.3*  | *79.5*   | *82.5*   | *84.4*   | *44.7*           | *61.1*  | *66.0*    | *70.7*   | *74.1*   | *76.2*   |
| GTA              | 51.1          | 67.6  | 74.8  | 81.6   | *82.9*   | *85.7*   | *53.1*          | *70.6*  | 75.7  | *80.4*   | *83.0*     | *85.8*   | 46.6           | *52.5*  | *57.9*  | *63.3*   | *67.2*   | 70.4   |
| Tied-Transformer | 47.1          | 67.2  | 73.5  | 78.5   | *83.5*   | *85.4*   | *51.6*          | *70.0*    | *75.0*    | *79.6*   | *82.7*   | *85.2*   | *37.7*           | *53.6*  | *58.7*  | *63.7*   | *67.8*   | *71.0*     |
| MEGAN            | 48.1          | 70.7  | 78.4  | 86.1   | 90.3   | 93.2   | *46.2*         | *66.5*  | *74.3*  | *81.1*   | *85.4*   | *89*     | 33.6           |       |       | 63.9   |        | 74.1   |
| RetroTRAE        |               |       |       |        |        |        | 58.3          | 66.1  | 69.4  | 73.1   |        |        |                |       |       |        |        |        |
| Retroformer      | 53.2          | 71.1  | 76.6  | 82.1   | 84.2   | 88.8   | *33.6*          | *49.3*  | *55.3*  | *60.9*   |        |        |                |       |       |        |        |        |
| R-SMILES         | 56.3          | 79.2  | 86.2  | 91.0   | 93.1   | 94.6   | 60.3          | 78.2  | 83.2  | 87.3   | 89.7   | 91.6   | 48.9           | 66.6  | 72.0    | 76.4   | 80.4   | 83.1   |
