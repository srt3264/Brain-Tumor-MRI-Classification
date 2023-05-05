
## Overview
This project aims to build a classification model on brain tumor data obtained from the Brain Tumor MRI Dataset on Kaggle. The data consists of magnetic resonance imaging (MRI) scans of the brain, with each scan labeled as either having a tumor or being a healthy scan.

The project has two main phases:

1. **Building the classification model**: In this phase, we use the brain tumor MRI dataset to train a classification model that can distinguish between tumor and healthy brain scans with high accuracy.
2. **Adding synthetic noise to the data**: In this phase, we introduce synthetic noise to the brain MRI scans to simulate real-world scenarios where scans may be noisy or distorted. We then test the previously built classification model on the noisy data to see how well it still works.
3. **Retraining the classifier using the noisy data**: In this phase, we retrain the classification model using the noisy data to see if it performs better on the noisy data.

## Installation
Clone this repository to your local machine.

Install the required Python packages using pip. You can do this by running the following command in your terminal:

```make install requirements.txt```
Download the Brain Tumor MRI Dataset from Kaggle and extract it to the data directory.

## Usage
### Building the Classification Model
We read the MRI data from the data directory, preprocesses it, and trains a convolutional neural network (CNN) model using Keras.


### Adding Synthetic Noise to the Data
To add synthetic noise to the MRI scans, run the add_noise.py script. This script reads the MRI data from the data directory, adds various types of noise to the images, and saves the noisy images in the noisy_data directory.



## Testing the Classifier on Noisy Data
To test the previously built classification model on the noisy data, run the test_noisy_data.py script. This script reads the noisy MRI data from the noisy_data directory, preprocesses it, and tests the classifier on the noisy data.




## Retraining the Classifier Using Noisy Data
To retrain the classification model using the noisy data, run the retrain.py script. This script reads the MRI data from the data and noisy_data directories, preprocesses it, and retrains the CNN model using Keras.





## Conclusion
This project demonstrates how to build a classification model on brain tumor MRI data and how to add synthetic noise to the data to simulate real-world scenarios. The project also shows how retraining the classifier using the noisy data can improve its performance on noisy data.
****put results here**** 
