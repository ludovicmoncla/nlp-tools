# NLP Python tools


This repository contains examples of how to use NLP tools in Python such as POS-tagging and NER. The examples are based on the following libraries:

* [spaCy](https://spacy.io/)
* [Stanza](https://stanfordnlp.github.io/stanza/)
* [Perdido](https://github.com/ludovicmoncla/perdido/tree/main)



## Configure a Python environment 

### Clone this repository

```bash
git clone https://github.com/ludovicmoncla/nlp-tools.git
```

### Configure the environment and install packages


* Create a new environment: `nlp-tools-py39`

```bash
conda create -n nlp-tools-py39 python=3.9
```

* Activate the environment

```bash
conda activate nlp-tools-py39
```


* Install Python packages using `pip`

```bash
pip install -r requirements.txt
```


### Run Jupyter server

```bash
jupyter notebook
```