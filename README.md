# Deep-Learning-For-Drug-Protein-Interactions
This repo contains a Python implementation for training a neural network for predicting drug-protein interactions using Keras and Tensorflow.

The objective is to create a model that is able to predict which xenobiotics (drugs) can be catalyzed by Cytochrome P450 enzymes in the human body. Using **only the string representations** of the drugs and the protein sequences, I am able to extract quantitative features from both types of molecules, which I later represent as a column vector that will be used as the input to a Deep Neural Network. The network achieves accuracies close to 80% using a batch size of 10 and 150 epochs.

## Description
This repo contains 5 Notebooks that implement a Neural Network trained on drug-protein interactions from a subset of enzymes (Cytochrome P450) and drugs. The networks is trained to recognize substrates that are transformed by CYP450 enzymes.


## Notebooks
Each notebooks is numbered according to the order in which they must be executed and contains relevant documentation for each step. The first Notebooks (1-4) deal with downloading, cleaning, and pre-processing the data using the KEGG API and Mole DB. 

The last Notebook shows the implementation of the Neural Network and how to visualize the results
