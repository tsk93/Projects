# Capstone Project: Chart Interpretation with Computer Vision

## Table of Contents
- [Background](#Background)  
- [Problem Statement](#Problem-Statement) 
- [Dataset](#Dataset)
- [Modeling](#Modeling)
- [Conclusions and Recommendations](#Conclusions-and-Recommendations)
- [Future Work](#Future-Work)


### Background
By 2050, the Vision Loss Expert Group (VLEG) predicts approximately 61 million people to be blind. Visual impairment affects all age groups and brings about different inconveniences to the underprivileged. A common inconvenience is the limited or inablity to access educational materials. Currently, Braille helps to address the difficulty of reading conventional print. However there is no quick fix to interpreting graphics, including educational visuals such as graphs and charts. As it is resource intensive to produce the materials needed to help the visually challenged, it is hoped that machine learning will be able to bridge this gap eventually to help address the lack of materials.

[Return to top](#Table-of-Contents)  

### Problem Statement
As only a small fraction of educational materials are available for people with visual impairment, we aim to develop a machine learning model to extract chart information to help bridge the gap in learning resources.

[Return to top](#Table-of-Contents)  

### Dataset
Dataset was provided by Kaggle, with 7500 chart images (bar, scatter, line) selected randomly to train a neural network model for chart type classification. As an extension to this project, 300 images were classified manually to build a preliminary model to evaluate chart trend prediction.

[Return to top](#Table-of-Contents)


### Modeling

- Baseline score: 0.333


| Model | Train Score | Test Score |
| :-: | :-: | :-: |
| AlexNet 	|   0.8215 	  |     0.7380 |
| ResNet50  |   0.8871 	  |     0.9587 |
| VGG16  	|   0.9831 	  |     0.9967 |


[Return to top](#Table-of-Contents)


### Conclusions and Recommendations
- Feasible to classify chart types using CNN
- Transfer learning from VGG16/ResNet50 is more effective than training network from scratch
 
[Return to top](#Table-of-Contents)

### Future Work

- Add further classification of different chart images (pie charts, area charts, Venn diagrams etc)
- To extract more features from plots (axis names/values, legend etc)
- To interpolate chart values using computer vision and use the numerical data for curve fitting to accurately predict trends
- Use of OCR to create captions for charts
- Deployment of model for front end GUI

[Return to top](#Table-of-Contents)