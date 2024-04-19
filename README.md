# Hand Gesture Recognition with Accelerometer Data

## Abstract
This research presents a comparative analysis of acceleration-based hand gesture recognition algorithms. The study aims to evaluate various implementation approaches to identify the most efficient and accurate method. It involves collecting acceleration data with an accelerometer sensor and processing it with algorithms such as linear SVC, Decision Trees, random forest classifiers, and Artificial Neural Networks (ANNs). Results indicate that Gradient boosting decision tree and ANN outperform other algorithms in terms of accuracy and response time, showcasing the potential of acceleration data for hand gesture detection.

## Introduction
With the proliferation of mobile devices equipped with sensors, such as accelerometers, vast amounts of data have become available for various applications. Accelerometer data, in particular, has found utility in fields like activity recognition, motion analysis, and gesture recognition. This research leverages data generated by the Phyphox app, focusing on hand gesture detection. The dataset includes gestures like circle, wave, come here, and go away, captured without gravitational information at a sampling frequency of 100Hz.

## Objectives and Research Questions
The study aims to address several key questions:
- What preprocessing techniques yield optimal results for live feed data?
- How can the accuracy of hand gesture recognition on real-time data be enhanced?
- How many features from signal data are necessary to build a better model?
- What methods can be used to segment each gesture's signal effectively?

## Literature Review
The research draws insights from previous studies such as:
- A system for real-time hand gesture recognition using a sensor dataglove.
- A framework for hand gesture recognition using accelerometer data and similarity matching.
- The application of machine learning techniques for automated hand gesture classification using a wristband device.

## Methodology
Two approaches for hand gesture classification using accelerometer data are explored:
1. **First Approach**: Preprocessing, Exploratory Data Analysis, and Data Modelling/Classification.
2. **Second Approach**: Preprocessing, Exploratory Data Analysis, and Data Modelling/Classification.

## Results
The findings reveal the performance of different classifiers:
- Decision Tree with Gradient Boosting: Accuracy of 95%, Precision of 0.95, Recall of 0.95, F1-score of 0.95.
- Artificial Neural Network (ANN): Accuracy of 99%, Precision of 0.99, Recall of 0.99, F1-score of 1.0.
- Random Forest: Accuracy of 93%, Precision of 0.93, Recall of 0.93, F1-score of 0.93.
- Linear SVC: Accuracy of 86%, Precision of 0.85, Recall of 0.85, F1-score of 0.85.

## Discussion
The study compares the performance of machine learning models and discusses the implications of different feature extraction methods and parameter settings on recognition performance. It highlights the strengths and weaknesses of various algorithms and offers insights into their suitability for hand gesture recognition using accelerometer data.

## Conclusion and Future Recommendations
The research concludes by identifying the most effective algorithms for hand gesture recognition and discussing future prospects for the technology. It emphasizes the potential applications of hand gesture detection using accelerometer data across diverse fields and suggests avenues for further research and development.

## Repository Structure
- **/data**: Contains the dataset generated by the Phyphox app.
- **/code**: Includes implementation of preprocessing techniques and machine learning models.
- **/docs**: Documentation and research findings.
- **/results**: Visualization of results and comparative analysis.
- **/references**: Relevant papers and literature used in the study.

  
[Implementation Based Comparative Analysis of Hand Gesture Recognition using Acceleration Data.pdf](https://github.com/deepak6174/Hand-Gesture-Recognition/files/15032141/Implementation.Based.Comparative.Analysis.of.Hand.Gesture.Recognition.using.Acceleration.Data.pdf)

