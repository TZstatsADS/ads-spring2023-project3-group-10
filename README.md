# Project: Weakly supervised learning-- label noise and correction


### [Full Project Description](doc/project3_desc.md)

Term: Spring 2023

+ Team 10
+ Team members
	+ Zhu, Yiming
	+ Liu, Yunfan
	+ He, Tianxiao
	+ Ng, Brendan
	+ Zhang, Xueyi

+ Project summary: In this project, we created two models for image classification in order to improve the baseline logistic classification model. We mainly use CNN model since it is applied to analyze visual imagery. The first model is a CNN model using the package from TensorFlow on Python, using the noisy labels to train it. The second model utilizes weakly supervised learning. We applied label correction and used the corrected labels to train our model from model 1. Overall, we see improvement of accuracy from baseline model to the 2 new models. The accuracy for image prediction enhanced from 24% to 49%. In the mean time, running time is saved from model 1 to model 2 as well.
	

**Contribution statement**: 

All team members contributed equally in all stages of this project. All team members approve our work presented in this GitHub repository including this contributions statement. 

Yunfan built model 1, Tianxiao improved it and trained model 2 while Brendan finished the label correction process.Tianxiao also compared the 3 models and made evaluations. Yiming and Xueyi contributed to presentation and documentation. 

Following [suggestions](http://nicercode.github.io/blog/2013-04-05-projects/) by [RICH FITZJOHN](http://nicercode.github.io/about/#Team) (@richfitz). This folder is orgarnized as follows.

```
proj/
├── lib/
├── data/
├── doc/
├── figs/
└── output/
```

Please see each subfolder for a README file.
