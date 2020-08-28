# Disclaimer: This project is based on the awesome work of [Mindy Yang](http://github.com/yangmindy4) and [Gary Thung](https://github.com/garythung/trashnet) for the final project for [Stanford's CS 229: Machine Learning class](http://cs229.stanford.edu).

## Dataset
This repository contains the dataset that they collected. The dataset spans six classes: glass, paper, cardboard, plastic, metal, and trash. Currently, the dataset consists of 2527 images:
- 501 glass
- 594 paper
- 403 cardboard
- 482 plastic
- 410 metal
- 137 trash

The pictures were taken by placing the object on a white posterboard and using sunlight and/or room lighting. The pictures have been resized down to 512 x 384, which can be changed in `data/constants.py` (resizing them involves going through step 1 in usage). The devices used were Apple iPhone 7 Plus, Apple iPhone 5S, and Apple iPhone SE.

The size of the original dataset, ~3.5GB, exceeds the git-lfs maximum size so it has been uploaded to Google Drive. If you are planning on using the Python code to preprocess the original dataset, then download `dataset-original.zip` from the link below and place the unzipped folder inside of the `data` folder.

**If you are using the dataset, please give a citation of this repository. The dataset can be downloaded [here](http://drive.google.com/drive/folders/0B3P9oO5A3RvSUW9qTG11Ul83TEE).**
