# NLP_Sarcasm
NLP course project at Oregon State University 

Group Members:
York Yang,
Dennis Huang,
Chengxi Yang,
Dayeon Oh.

1. Create a python 3.7.9 using conda:

```
conda create -n nlp_sarcasm python=3.7.9
conda activate nlp_sarcasm
```
2. Install the required third-party Python libraries:

```
pip install -r requirements.txt
bash setup_torch.sh
```

3. The sarcasm dataset is registered as a submodule, to download the dataset:

```
git submodule init
git submodule update
```

This will download the dataset to `/chengxi/sarcasm`.

### To run everything from the project root

Export the project root directory to the $PYTHONPATH:

```
export PYTHONPATH=$PWD
```
