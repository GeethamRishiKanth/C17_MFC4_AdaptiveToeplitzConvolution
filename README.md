# Adaptive Toeplitz Convolution for ECG Signal Analysis

# 

# TEAM C 17 :

#### CH. PRIYA MADHAV - CB.SC.U4AIE24211

#### G.G. RISHI KANTH - CB.SC.U4AIE24218

## 

## Project Outline

This project focuses on analyzing ECG (Electrocardiogram) signals using an adaptive Toeplitz convolution approach. The ECG signals are obtained from the ECG5000 dataset and processed using a Toeplitz matrix formulation of convolution. An adaptive kernel is constructed using the statistical properties of each signal, such as mean and standard deviation. The Toeplitz matrix representation allows convolution to be performed as a matrix multiplication, providing a clear mathematical interpretation of the operation.



After applying adaptive Toeplitz convolution, statistical features are extracted from the processed signals to capture important signal characteristics. These features are then used to train a machine learning classifier that categorizes ECG signals as normal or abnormal. The performance of the model is evaluated using metrics such as accuracy, confusion matrix, and ROC curve.



## Updates

Loaded and processed the ECG5000 dataset containing 5000 ECG signals



Implemented adaptive Toeplitz convolution for ECG signal processing



Designed an adaptive convolution kernel using signal statistics



Extracted statistical features such as mean, standard deviation, RMS, skewness, and kurtosis



Implemented K-Nearest Neighbors (KNN) classifier for ECG classification



Evaluated classification performance using accuracy, confusion matrix, and ROC curve



Visualized ECG signals using line plots and heatmap representations



## Challenges Faced

Understanding the Toeplitz matrix representation of convolution



Designing an adaptive kernel based on signal statistics



Handling a large number of ECG signals in visualization



Selecting appropriate features for effective classification



Interpreting classification results using confusion matrices and ROC curves





## RESULTS

```
================ TOEPLITZ RESULTS ================
Accuracy: 0.958
Confusion Matrix:
851 25
38 586

================ STANDARD RESULTS ================
Accuracy: 0.964
Confusion Matrix:
867 9
45 579
```

<img width="900" height="750" alt="image" src="https://github.com/user-attachments/assets/b7f76a63-d2c4-4205-a558-b799fdf4635a" />

1 Signal Example:
<img width="1143" height="857" alt="image" src="https://github.com/user-attachments/assets/699e37ea-226d-424f-b06c-e907329be75f" />


<img width="898" height="770" alt="image" src="https://github.com/user-attachments/assets/ac6ccffb-38ae-4d2f-935a-b381982fa36c" />

<img width="898" height="770" alt="image" src="https://github.com/user-attachments/assets/ebca450c-af58-4671-bb71-9fd1b5d01bfd" />

<img width="992" height="793" alt="image" src="https://github.com/user-attachments/assets/f0b06366-d5c5-4004-a75c-e8ad8280032c" />


## CONCLUSION
This project demonstrates the use of adaptive Toeplitz convolution for analyzing ECG signals and detecting
abnormalities. The ECG5000 dataset was used to obtain real heart signal recordings, which were then
normalized and processed using an adaptive convolution kernel. By constructing a Toeplitz matrix and
performing convolution, important signal characteristics were enhanced, allowing abnormal patterns in ECG
signals to become more distinguishable.
Statistical features such as mean, standard deviation, signal range, skewness, kurtosis, and RMS were
extracted from the processed signals to represent the signal behavior numerically. These features were used
to train a K-Nearest Neighbors (KNN) classifier that distinguishes between normal and abnormal ECG signals.
The experimental results show that the proposed approach achieves high classification accuracy and good
discrimination capability, as demonstrated by the confusion matrix and ROC curve analysis.

Overall, the combination of signal processing and machine learning provides an efficient framework for
automated ECG signal analysis. The adaptive Toeplitz convolution method improves feature extraction and
highlights abnormal patterns in ECG signals, making it useful for medical signal processing applications and
automated cardiac monitoring systems.






