# Playing-Card-Classification
A convolutional neural network built with PyTorch that classifies images of playing cards into their correct suit and rank.
### Overview
This project trains an image classifier on a dataset of playing card photos, learning to distinguish all 52 cards (+ jokers) from raw pixel data. The full pipeline — data loading, training, evaluation, and inference — is contained in a single Jupyter notebook.

### Libraries needed
torch

torchvision

numpy

matplotlib

jupyter

### Running the notebook
git clone https://github.com/your-username/Playing-Card-Classification.git

cd Playing-Card-Classification

jupyter notebook

### Structure
Playing-Card-Classification/

├── playing_card_classification.ipynb   # Main notebook

├── data/                               # Card image dataset

└── README.md

### Dataset
Loaded from https://github.com/lordloh/playing-cards