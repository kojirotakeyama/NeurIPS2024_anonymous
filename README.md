# Loco3D: Indoor Multiuser Locomotion 3D Dataset (ICLR 2024)

## Introduction

This is the anonymized repo for our paper of ICLR 2024.
Purpose of this repo is to enable reviewers to confirm reproducibility of our evaluation result in the main paper.

All the materials can be accessed by following link. (Approximately 2GB)
[https://drive.google.com/drive/folders/1QLl3o_xT0_zUETv0Acyj_iEA_ckkZzkI?usp=sharing](https://drive.google.com/drive/folders/1uFB5anbFJQ-Jd_fBJ7Api5iO7MnHM3TX)

The material contain items below.
- Datasets (Loco3D, Loco3D-R, GIMO)
- Code (for both evaluation and training) and trained models for three trials
- Shell script to run the evaluation

### Instructions 

1. Download the materials from the link above.
2. "pip install -r requirement.txt" to install the libraries necessar to run the code.
4. Run "evaluate.sh" to get the evaluation result shown in the paper. The evaluation result will be created as csv files.
5. If you try training the models, run "training_vrlocomotion2.py" in each model folder.

### Note
- Dataset in the link above contains 2D trajectories of pedestrians, which is used in our evaluations.
- We are planning to publish our full dataset (3D position/pose of 6 body parts) and test codes on a website after a while.
