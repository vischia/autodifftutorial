# Differentiable programming tutorial
(C) Pietro Vischia, 2025
 pietro.vischia@cern.ch

# Installation


### Conda

```
git clone https://github.com/vischia/autodifftutorial.git
cd autodifftutorial
conda create -n "autodifftutorial" python=3.10
conda activate autodifftutorial
conda install --file requirements.txt -c conda-forge -c pytorch
jupyter notebook
```
    

If you want, you can also run the following command, but it is not strictly needed (the command will be run within the notebook anyway)

```
pip install torchviz
w```

    
When you finish, run

```
conda deactivate
```
    
### Run on Google Colab

