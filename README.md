**Machine learning–based classification of copper-binding sites for protein structures**

*Overview:* 
This repository provides a pipeline to identify copper-binding sites from PDB files and classify them into structurally defined clusters using a trained Support Vector Machine (SVM) model. The workflow extracts coordination-based features and assigns a class label for each detected copper site.

## 🔗 Open in Colab
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1Ubfl9owZYXzzXGhzeIwQDuwgnyUcWb9D?usp=sharing)


*Usage:*
Run the provided Google Colab notebook:
1. Execute the **setup cell** to install and import required dependencies.
2. Run the **helper functions** cell to process the input PDB file and identify copper coordination environments.
3. Run the **prediction cell** to classify each detected copper-binding site.

The output includes the predicted class and coordinating residues for each site, along with optional visualization.

*Citation*
If you use this work, please cite:
