# Reproduction of the Malicious Network Traffic Classification of FENCE paper

[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)


This project serves as a reproduction of the paper titled "Feasible Evasion Attacks on Neural Networks in Constrained Environments," specifically focusing on the experiment related to Malicious Network Traffic Classification.

## Table of Contents

- [Attack](#installation)
- [Botnet detector using machine learning](#usage)


## Attack folder
The attack folder contains Python files designed for launching attacks on a pre-trained model using the FENCE framework. To execute the attack against a pre-trained model with FENCE, run the attack.ipynb file. Additionally, the Evaluation of Adversarial Training.ipynb file includes code to evaluate a model trained with adversarial training.

To run the attack against a pre-trained model using FENCE, execute the code in the attack/attack.ipynb notebook.

## data folder
The data folder includes essential files, such as datasets, required to conduct the experiments.

## out folder
The out folder is utilized to store models after training.

## training folder
The training folder contains crucial files for both normal training and adversarial training. To train a model, whether it's adversarial or normal, use the train.ipynb file.


## Botnet folder
The botnet folder contains code to create a Botnet Detector model. This model is employed in the "Attack Results for Raw Data Representation" experiment discussed in the paper.
