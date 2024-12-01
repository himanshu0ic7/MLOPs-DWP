# MLOPs-DWP

git push origin main # to finally update git repo after commit
visa is the name of current environment

# -e .  this will make us_visa folder as a package(this can only be done when you have a setup.py in current directory)

## Tools
```
- Flowchart: https://whimsical.com/
- MLOPs Tool: https://www.evidentlyai.com/
- MongoDB: https://account.mongodb.com/account/login
- Data link: https://www.kaggle.com/datasets/moro23/easyvisa-dataset
```


## Git commands

```bash
git add .

git commit -m "Updated"

git push origin main
```


## How to run?

```bash
conda create -n visa python=3.8 -y
```

```bash
conda activate visa
```

```bash
pip install -r requirements.txt
```

## Workflow of the projects:
logger and exception then EDA and Feature enginering on juyter Notebook then below folders inside us_visa

1. constants: create a common used variable names like folder names (check data ingestion flow chart for more detail)
2. entity: 
3. components
4. pipeline
5. Main file



### Export the  environment variable
```
Approach: 1
In Git bash terminal


export MONGODB_URL="mongodb+srv://<username>:<password>...."

export AWS_ACCESS_KEY_ID=<AWS_ACCESS_KEY_ID>

export AWS_SECRET_ACCESS_KEY=<AWS_SECRET_ACCESS_KEY>

Approach: 2
Use system variable instead
```
