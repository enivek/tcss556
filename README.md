# TCSS 556: Advanced Machine Learning

## Introduction
Implementation for the paper entitled "[Session-based Recommendation with Self-Attention Networks](https://arxiv.org/abs/2102.01922)"

Github Repository: [https://github.com/GalaxyCruiser/SR-SAN](https://github.com/GalaxyCruiser/SR-SAN)

## Dataset
You can find the Yoochoose dataset here: 
- [https://www.kaggle.com/datasets/chadgostopp/recsys-challenge-2015](https://www.kaggle.com/datasets/chadgostopp/recsys-challenge-2015)

## Usage
Run the file  `datasets/preprocess.py` to preprocess the data before train the model.

For example: `cd datasets; python preprocess.py --dataset=yoochoose`
```bash
usage: preprocess.py [-h] [--dataset DATASET]

optional arguments:
  -h, --help         show this help message and exit
  --dataset DATASET  dataset name: diginetica/yoochoose
```

## Requirements
- Python 3
- PyTorch 1.2

