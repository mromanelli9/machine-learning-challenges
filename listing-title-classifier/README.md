# Listing title classifier

## Challenge statement
In [COMPANY NAME] we handle many online infringements provided by automatic online search bots. These bots extract from the different websites the titles for all the listings found online.  

For example, imagine that we have a protected product called: "dji mavic pro". Bots start searching and retrieve many listings, providing us with this titles:
* DJI Mavic Pro Clone Drone With Wifi FPV 1080P HD Camera Foldable RC Quadcopter
* DJI MAVIC PRO FLY MORE COMBO con Garanzia Attiva + Eliche Platinum + Accessori
* dji mavic pro fly SPECIAL White Edition
* Vectorsave 10 Mavic RS paracaídas sistema para DJI Mavic drones

Some of them belong to the protected product, and some of them don’t (the listings sell accessories instead of the main product, they sell a different product or a different model that the one we are protecting). Given this information, we propose the following problem to be developed with Python3:
1. Design a text classifier which will be able to classify a listing title in two categories: ASSET or NON-ASSET (is the product or not, respectively). For this, we provide three datasets for three different products, so you have examples of the kind of data that the bots provide. The data has been already labeled by some users. You should create a single model for each product using the same method: same algorithm, different data.
2. Try at least two or three methods to do this, and compare the results, explaining the advantages and disadvantages for each method. Additionally, provide at least one graphic with the algorithm comparison.
3. (Optional) Take into account training and prediction time. How long does the algorithm take to train and predict? Does your selected algorithm work properly under heavy time constraints?

## Setup
Python 3.7 and Jupyter are required, as long as some external libraries (pandas, numpy, etc).  
If you have Anaconda or miniconda installed, you can quickly create an environment
by typing:
```
$ conda env create -f environment.yml
$ conda activate ml-challenge
```

## Usage
Run the notebooks simply by typing:
```
$ jupyter notebook listing-title-classifier.ipynb
```

# License
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)