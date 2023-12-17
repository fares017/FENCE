# Reproduction of the Malicious Network Traffic Classification of FENCE paper

[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)


This project is a reproduction of the paper Feasible Evasion Attacks on Neural Networks in Constrained Environments, precisely the experiment Malicious Network Traffic Classification.

## Table of Contents

- [Attack](#installation)
- [Botnet detector using machine learning](#usage)


## Attack folder
The attack folder, contains python files that you can use to attack the a pretrained model using the FENCE framework.
To run the attack against pretrained model using FENCE, you need to run the file located at: attack.ipynb.
The file Evalution of Adeversarial training.ipynb contains the code, in order to evaluate the model trained with adversarial training.

To run the attack against a pretrained model using FENCE, run the file located at: attack/attack.ipynb

## data folder
This folder contains some neccesary files as dataset to run the experiments.

## out folder
We use this folder to output to store the models after the training

## training folder
It contains essential files in order to perform: normal training or adversarial training
to train a model (adversarial or normal) use the file train.ipynb.


## Botnet folder
It contains a the code to create a Botnet_detector model, to be used in the Attack results for raw data representation experiment of the paper.
