# Submission for MLMR’s Annual Materials Informatics Competition 2024
Click [here](https://github.com/martintb/active_learning_tutorial) for more information on the competition, which involved predicting the phase map of a three-component system using active learning. Each experiment returned realistic small-angle neutron scattering (SANS) data that varied with sample composition.

<img src="assets/Phase_Map_Active_Learning.png" alt="Overview" width="600"/>

The first submission employed spectral clustering for the label phase, a GaussianProcessClassifier with the RationalQuadratic kernel for the extrapolate phase and entropy for the acquire phase. 
<a target="_blank" href="https://colab.research.google.com/github/DieterPlessers/materials_informatics_competition/blob/main/notebooks/Challenges_Submission_DP_1.ipynb"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/></a>

The two alternative submissions made use of a KNN classifier for the extrapolate phase, respectively with n_neighbors=8 and 5.
<a target="_blank" href="https://colab.research.google.com/github/DieterPlessers/materials_informatics_competition/blob/main/notebooks/Challenges_Submission_DP_2.ipynb"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/></a>  <a target="_blank" href="https://colab.research.google.com/github/DieterPlessers/materials_informatics_competition/blob/main/notebooks/Challenges_Submission_DP_3.ipynb"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/></a>
