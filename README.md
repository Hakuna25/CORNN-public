# CORNN-public

The reproduction repository for the Neurips 2023 paper titled "CORNN: Convex optimization of recurrent neural networks for rapid inference of neural dynamics". Link: https://openreview.net/forum?id=GGIA1p9fDT

The data are publicly available here: https://drive.google.com/drive/folders/1PRJ-v9eH4iaZastq61kFbgvjNwIgCkkZ?usp=share_link

# Workspace Installation
1. Install [miniforge](https://github.com/conda-forge/miniforge)
   
   Here's one case on ubuntu24.04:
   
   ```wget "https://github.com/conda-forge/miniforge/releases/latest/download/Miniforge3-$(uname)-$(uname -m).sh"```
   
   Run the script with:
   
   ```bash Miniforge3-$(uname)-$(uname -m).sh```
3. Environment Create
   ```mamba env create -n cornn -f env.xml
   mamba activate cornn```
