# Dual Task Progress (DTP)

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.13131779.svg)](https://doi.org/10.5281/zenodo.13131779)

**Input: individual or collective .csv files ([~/sample](https://github.com/MatthieuGG/DualTaskProgress/tree/main/sample))  
Output: individual or collective .csv files, as well as a collective plot ([~/results](https://github.com/MatthieuGG/DualTaskProgress/tree/main/results))  
Script: [DualTaskProgress.ipynb](https://github.com/MatthieuGG/DualTaskProgress/blob/main/DualTaskProgress.ipynb)**  

Automatically calculates the cognitive-motor dual-task progress (DTP) from the cognitive and motor performances of subjects at 2 times (T1 and T2), both realised in single and dual task condition (ST and DT).  

To do so, you need to:
- transpose your participants performance into .csv files (see exemples of independant or gathered files structures in [~/sample](https://github.com/MatthieuGG/DualTaskProgress/tree/main/sample))
- use the provided Notebook [DualTaskProgress.ipynb](https://github.com/MatthieuGG/DualTaskProgress/blob/main/DualTaskProgress.ipynb) on your files to obtain the DTE and DTP scores and appreciation, as well as a graphical representation (see [~/results](https://github.com/MatthieuGG/DualTaskProgress/tree/main/results)). In the first cell, you need to bring some information to configurate the analysis: are you using independant or gathered data, what is the direction of the score you used, do you want to save the plot, and so on.
- you'll obtain this kind of results:

![Dual Task Progress Graph](https://github.com/MatthieuGG/DualTaskProgress/blob/main/results/DTP_plot.jpg?raw=true)  

`"Participant 1    : went from Cognitive priority tradeoff    at T1, to Motor priority trade off       at T2 with a DTP -/+ : cognitive trade-off of CMI"`  
(etc. for all participants)  

---
This code is provided allong with more detailed informations in this article: [Gallou-Guyot et al., 2024](). The data has been acquired within the [INCOME research project](https://matthieugg.github.io/income.html).  To cite this work:  
> (incoming: article)  

> Matthieu Gallou-Guyot. (2024). MatthieuGG/DualTaskProgress: v1.0.0 (v1.0.0). Zenodo. https://doi.org/10.5281/zenodo.13131779 

![Dual Task Progress](https://github.com/MatthieuGG/DualTaskProgress/blob/main/images/DTP.png?raw=true)

You may also be interested in the Dual-Task Effect caculator: https://github.com/MatthieuGG/DualTaskEffect
