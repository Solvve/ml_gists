# Few-Shot Learning for hyperspectral images
[![Solvve](https://img.shields.io/badge/made%20in-solvve-blue)](https://solvve.com/)

## Description
Training clasifier with lack amount of data using PrototypicalNetworks
This is an example of few-shot classification on hyperspectral images. Based on https://github.com/sicara/easy-few-shot-learning
Final model tested on 100 tasks. Accuracy: 91.68%

## Dataset

http://www.ehu.eus/ccwintco/index.php?title=Hyperspectral_Remote_Sensing_Scenes#Indian_Pines

Indian Pines
This scene was gathered by AVIRIS sensor over the Indian Pines test site in North-western Indiana and consists of 145x145 pixels and 224 spectral reflectance bands in the wavelength range 0.4–2.5 10^(-6) meters. This scene is a subset of a larger one. The Indian Pines scene contains two-thirds agriculture, and one-third forest or other natural perennial vegetation. There are two major dual lane highways, a rail line, as well as some low density housing, other built structures, and smaller roads. Since the scene is taken in June some of the crops present, corn, soybeans, are in early stages of growth with less than 5% coverage. The ground truth available is designated into sixteen classes and is not all mutually exclusive. 
| |Class|	Samples |
| ------- | --- | --- |
|1|	Alfalfa	|46|
|2|	Corn-notill|	1428|
3|	Corn-mintill|	830|
4|	Corn|	237
5|	Grass-pasture|	483
6|	Grass-trees|	730
7	|Grass-pasture-mowed|	28
8|	Hay-windrowed|	478
9|Oats|	20
10|	Soybean-notill|	972
11|	Soybean-mintill|	2455
12|	Soybean-clean|	593
13|	Wheat	|205
14|	Woods|	1265
15|	Buildings-Grass-Trees-Drives|	386
16|	Stone-Steel-Towers|	93

## Labraries
 - torch
 - easyfsl
 - sklearn
