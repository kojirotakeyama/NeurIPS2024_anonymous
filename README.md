# Loco3D: Indoor Multiuser Locomotion 3D Dataset (ICLR 2024)

## Introduction

This is the anonymized repo for our paper at ICLR 2024.
The purpose of this repo is to allow reviewers to confirm the reproducibility of our evaluation results in the main paper.

All materials are available at the following link.

[https://drive.google.com/drive/folders/1QLl3o_xT0_zUETv0Acyj_iEA_ckkZzkI?usp=sharing](https://drive.google.com/drive/folders/1uFB5anbFJQ-Jd_fBJ7Api5iO7MnHM3TX)


The material includes the following items.
- Datasets (Loco3D, Loco3D-R, GIMO)
- Code (for both evaluation and training) and trained models for three experiments
- Shell script to run the evaluation

### Instructions 

1. Download the materials from the above link.
2. "pip install -r requirement.txt" to install the libraries needed to run the code.
3. Run "evaluate.sh" to get the evaluation result shown in the paper. The evaluation results are created as csv files.
4. If you try to train the models, run "training_vrlocomotion2.py" in each model folder.

### Note
- The dataset in the link above contains 2D pedestrian trajectories used in our evaluation.
- We plan to publish our full dataset (3D position/position of 6 body parts) and test codes on a website after reviewing.
