# Chest-Disease-Classification-From-Chest-CT-Scan

# To activate python environment using bash

```bash
source chest/Scripts/activate
```

## Workflows

1. Update config.yaml
2. Update params.yaml
3. Update the entity
4. Update the configuration manager in src config
5. Update the components
6. Update the pipeline 
7. Update the main.py
8. Update the dvc.yaml 



## Live matarials docs

[link](https://docs.google.com/document/d/1UFiHnyKRqgx8Lodsvdzu58LbVjdWHNf-uab2WmhE0A4/edit?usp=sharing)


## Git commands

```bash
git add .

git commit -m "Updated"

git push origin main
```

## How to run?

```bash
conda create -n chest python=3.8 -y
```

```bash
conda activate chest
```

```bash
pip install -r requirements.txt
```

```bash
python app.py
```

### Mlflow dagshub connection uri

```bash
MLFLOW_TRACKING_URI=https://dagshub.com/ReshmaChikate5/Chest-Disease-Classification-From-Chest-CT-Scan.mlflow \
MLFLOW_TRACKING_USERNAME=ReshmaChikate5 \
MLFLOW_TRACKING_PASSWORD=96c75beb6b32b3a1e411de33eabe748e722be036 \
python script.py

```


### RUN from bash terminal

```bash
export MLFLOW_TRACKING_URI=https://dagshub.com/ReshmaChikate5/Chest-Disease-Classification-From-Chest-CT-Scan.mlflow

export MLFLOW_TRACKING_USERNAME=ReshmaChikate5 

export MLFLOW_TRACKING_PASSWORD=96c75beb6b32b3a1e411de33eabe748e722be036

```

### Execute above 3 commands on git bash
