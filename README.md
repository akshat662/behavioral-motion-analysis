# Human Action Recognition for Behavioral Motion Analysis

This project focuses on analyzing human motion patterns from video rather than identifying specific activities. A CNN–LSTM based model is trained on selected classes from the UCF50 dataset to learn spatio-temporal motion dynamics present in human actions.

## Project Idea
The core idea of the project is to abstract action classes into domain-agnostic motion primitives. By grouping activities based on how motion occurs, rather than what task is being performed, the model captures general movement behavior independent of activity semantics.

## Methodology
A complete video preprocessing pipeline is implemented, including frame sampling, resizing, normalization, and temporal sequencing. A convolutional neural network extracts spatial features from individual frames, while an LSTM models temporal relationships across video sequences.

## Dataset
The UCF50 Action Recognition dataset is used as the data source, with a curated subset of classes selected based on their motion characteristics. The dataset itself is not included in this repository due to size and licensing constraints.

## Results and Interpretation
This project demonstrates that meaningful motion patterns can be learned from video data without relying on task-specific or interview-labeled datasets. The work is exploratory in nature and emphasizes understanding motion behavior rather than making automated decisions.

## Technologies Used
Python, TensorFlow/Keras, OpenCV, NumPy, Matplotlib

## Disclaimer
This repository is intended for educational and experimental purposes only.
