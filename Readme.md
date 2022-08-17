# DeepRetrosynthesis: methods and implementations

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

