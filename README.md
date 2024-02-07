# NLP Python tools


This repository contains examples of how to use NLP tools in Python such as POS-tagging and NER. The examples are based on the following libraries:

* [spaCy]: [spacy.ipynb](./spacy.ipynb) - [spaCy](https://spacy.io/)
* [Stanza]: [stanza.ipynb](./spacy.ipynb) - [https://stanfordnlp.github.io/stanza/](https://stanfordnlp.github.io/stanza/)
* [Perdido]: [perdido.ipynb](./perdido.ipynb) - [https://github.com/ludovicmoncla/perdido/](https://github.com/ludovicmoncla/perdido/)


Sample outputs are available in the [output](./output) folder.


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