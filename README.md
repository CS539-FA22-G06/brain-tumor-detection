# Brain Tumor Detection

This repository represents our semester-long deep-learning project for ECE/CS 539 - Introduction to Neural Networks at the University of Wisconsin - Madison. It contains our developments throughout the semester, and illustrates several portions of the machine learning pipeline from data synthesis and preprocessing, to model iteration and beyond.

## Authors

- [Nicholas Beninato](https://github.com/beninato8) -- University of Wisconsin - Madison -- Department of Computer Sciences
- [Sebastian Murrell](https://github.com/sebastianmurrell) -- University of Wisconsin - Madison -- Department of Statistics
- [Garrison Waugh](https://github.com/gwaugh39) -- University of Wisconsin - Madison -- Department of Computer Sciences

### Advisor

- [Prof. Yu-Hen Hu](https://directory.engr.wisc.edu/ece/Faculty/Hu_Yu-hen/) -- University of Wisconsin - Madison -- Department of Electrical & Computer Engineering

## Abstract

The goal of this project was to create a convolutional neural network that will be trained for multi-class classification on several images of human brain MRIs. This image set contains MRIs of three types of brain tumors–glioma, meningioma, and pituitary–and MRIs without tumors. The ultimate goal is the classification of glioma, meningioma, pituitary, or no tumor. To start, we followed the example model from Kumar (2021) on Kaggle to implement our own CNN to perform the binary classification if an MRI has a tumor. After we had this model working, we developed a multi-class model to classify the type of tumor.

## Repository Layout

- [Project Proposal](./project_proposal.pdf)
- [Gantt Chart](./gantt_chart.pdf)
- [Progress Report](./progress_report.pdf)
- [Final Report](./final_report.pdf)
- [Final Slides](./final_slides.pdf)
- [Preprocessing](./preprocessing/)
  - [BR35 Preprocessing](./preprocessing/preprocessing_br35.ipynb)
  - [Figshare Preprocessing](./preprocessing/preprocessing_figshare_conversion.ipynb)
  - [Kaggle BTClassification Preprocessing](preprocessing/preprocessing_kaggle_btclassification.ipynb)
- [Data](./data/)
  - [Combined Dataset](data/combined.csv)
- [Models]
  - [Binary Model](./models/Binary_Model_GPU.ipynb)
  - [Multiclass Model](./models/Multiclass_Model_GPU.ipynb)