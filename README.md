# TCSS 556: Advanced Machine Learning

Student: Kevin Ewig

Github link: [https://github.com/enivek/tcss556](https://github.com/enivek/tcss556)

## Introduction
- This code is taken from the paper "[Session-based Recommendation with Self-Attention Networks](https://arxiv.org/abs/2102.01922)"
- The Github repository for this paper as well as the original code can be found here: [https://github.com/GalaxyCruiser/SR-SAN](https://github.com/GalaxyCruiser/SR-SAN)

## Relevant Files
- `sr-san.ipnyb`: This contains the Jupytr notebook implementation of the SR-SAN code.
- `.\datasets\preprocess.py`: This Python script converts the three dat files (`yoochoose-clicks.dat`, `yoochoose-click.dat` and `yoochoose-test.dat`) into a binary files (`test.txt` and `train.txt`).

## Dataset
- You can find the Yoochoose dataset here [https://www.kaggle.com/datasets/chadgostopp/recsys-challenge-2015](https://www.kaggle.com/datasets/chadgostopp/recsys-challenge-2015)
- I was unable to find the diginetica dataset.

## Usage
- Step 1. Download the three dat files yoochoose-clicks.dat, yoochoose-click.dat and yoochoose-test.dat.
- Step 2. Copy the three files to the `datasets` folder.
- Step 3. Run `cd datasets; python preprocess.py --dataset=yoochoose`

## Requirements
- Python 3.7
- pytorch (torch==1.11.0)
- numpy (numpy==1.21)

## Results
Best Result (from local machine):
- Recall@20:	71.4677	
- MMR@20:	31.3229	
- Epoch:	4,	10

Best Result (from paper):
- Recall@20: 71.74     
- MRR@20: 31.58
