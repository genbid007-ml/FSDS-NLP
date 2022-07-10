# dvc-project-template
DVC project template

## STEPS -

### STEP 01- Create a repository by using template repository

### STEP 02- Clone the new repository

### STEP 03- Create a conda environment after opening the repository in VSCODE

```bash
conda create --prefix ./env python=3.7 -y
```

```bash
conda activate ./env
```
OR
```bash
source activate ./env
```

### STEP 04- install the requirements
```bash
pip install -r requirements.txt
```

### STEP 05- initialize the dvc project
```bash
dvc init
```

### STEP 06- commit and push the changes to the remote repository

```bash
git init
git remote add origin https://github.com/genbid007-ml/FSDS-NLP.git
git status
git add .
git commit -m "first commit after setup and stage 00 completed"
git status
git log
git push origin master



```