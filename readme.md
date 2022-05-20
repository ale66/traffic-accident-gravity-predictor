## The traffic-accident-gravity-predictor project

## A new dataset and a new pipeline for the UK traffic data.

This repository introduces a new dataset to assess the performance of machine learning algorithms in the prediction of the seriousness of injury in a traffic accident. 

The dataset has been created by aggregating publicly available datasets from the UK Department for Transport, which are drastically imbalanced with missing attributes sometimes approaching 50\% of the overall data dimensionality. 

In a companion paper on the Proceedings of the [EANN 2022 Conference](https://eannconf.org/2022/) we present the data analysis pipeline starting from the publicly available data of road traffic accidents and ending with predictors of possible injuries and their degree of severity.  
It addresses the huge incompleteness of public data with a MissForest model.  
We also introduces two baseline approaches to create injury predictors: a supervised artificial neural network and a reinforcement learning model. 
The dataset can potentially stimulate diverse aspects of machine learning research on imbalanced datasets and the two approaches can be used as baseline references when researchers test more advanced learning algorithms in this area.

## How to cite this work

Please use the following reference:

```bibtex
@inproceedings{eann22,
  author    = {Predicting Seriousness of Injury in a Traffic Accident},
  editor    = {Lazaros Iliadis et al.},
  title     = {Paschalis Lagias and George D. Magoulas and Ylli Prifti and Alessandro Provetti},
  booktitle = {Proceedings of the 23rd Engineering Applications of Neural Networks
               Conference - {EANN} 2022, Crete, Greece, 17-20 June, 2022},
  volume    = {},
  pages     = {--},
  publisher = {Springer},
  year      = {2022},
  url       = {},
  doi       = {}
}
```


### The team

Our work is carried out at Birkbeck, University of London, [Dept. of Computer Science & Information Systems](https://www.dcs.bbk.ac.uk/).

Members are [George Magoulas](https://www.dcs.bbk.ac.uk/about/people/academic-staff/gmagoulas/) and [Alessandro Provetti](https://www.dcs.bbk.ac.uk/~ale/) from Birkbeck and [Paschalis Lagias](https://github.com/PaschalisLagias), MSc Data Science.





