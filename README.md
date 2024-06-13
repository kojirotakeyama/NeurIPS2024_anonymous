# LocoVR: Multiuser Indoor Locomotion Dataset in Virtual Reality (NeurIPS 2024)

## Introduction

This is the anonymized repo for our paper at NeurIPS 2024.
The purpose of this repo is to allow reviewers to confirm the reproducibility of our evaluation results in the main paper.

All materials are available at the following link.

[Materials for the evaluation](https://drive.google.com/drive/folders/14L3F231hmZ0kZd6U8zGw6_4tY3JR9cnZ?usp=drive_link)


The material includes the following items.
- Datasets (LocoVR, THOR-MAGNI, GIMO)
- Code (for both evaluation and training) and trained models for three experiments
- Shell script to run the evaluation

## Instructions 

1. Download the folder "Evaluation_main_paper_NeurIPS2024" from the above link.
2. "pip install -r requirement.txt" to install the libraries needed to run the code.
3. Run "evaluate.sh" to get the evaluation result shown in the paper. The evaluation results are created with csv files in each task folder: "Global_Path_Prediction", "Trajectory_Prediction", "Goal_Prediction".
4. If you want to train the models, run "training_vrlocomotion2.py" in each model folder.

## Note
- Dataset folder includes trajectories and map files used in our evaluation.
- We also have public repository on the [GitHub](https://anonymous.4open.science/r/LocoVR-1B87/README.md) that includes LocoVR dataset, test codes to visualize the dataset, and instructions to execute the code.
  
