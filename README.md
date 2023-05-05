
## Overview
This project aims to build a classification model on brain tumor data obtained from the Brain Tumor MRI Dataset on Kaggle. The data consists of magnetic resonance imaging (MRI) scans of the brain, with each scan labeled as either having a tumor or being a healthy scan.

The project has two main phases:

1. **Building the classification model**: In this phase, we use the brain tumor MRI dataset to train a classification model that can distinguish between tumor and healthy brain scans with high accuracy.
2. **Adding synthetic noise and other conditions to the data**: In this phase, we introduce synthetic noise, motion blur, and synthetically lower the resolution to the brain MRI scans to simulate real-world scenarios where scans may be noisy or distorted. We then test the previously built classification model on the noisy data to see how well it still works.
3. **Retraining the classifier using the noisy data**: In this phase, we retrain the classification model using the noisy data to see if it performs better on the noisy data.

### For phase 2, here are example images for each synthetic adjustment. 

#### Gaussian Noise

![download-18](https://user-images.githubusercontent.com/110945807/236569872-0dbaf2b0-0559-488c-a1cb-d05362461ad1.png)


#### Poission Noise

![download-19](https://user-images.githubusercontent.com/110945807/236569915-2231b5c8-32d0-4994-9d45-962bd6118968.png)


#### Quantization Noise

![download-20](https://user-images.githubusercontent.com/110945807/236569950-41576988-7622-46f3-9643-839a12c67a05.png)


#### Motion Blur


![download-21](https://user-images.githubusercontent.com/110945807/236569982-fc37dbd7-eb07-472b-a325-fab26b8cbff8.png)



#### Lowered Resolution 

![download-22](https://user-images.githubusercontent.com/110945807/236570018-c9b15a4c-0d21-42d6-bbac-2bbd5ab25d1a.png)




Below is what the initial data looks like. 
![download](https://user-images.githubusercontent.com/110945807/236569126-af423a77-7073-4dac-88e6-4db310ca36fa.png)

Below is a table summarizing the test and train data split. 

```
| Tumor Type | Train Quantity | Test Quantity |
|------------|----------------|---------------|
| Pituitary  | 1457           | 300           |
| Glioma     | 1321           | 300           |
| Meningioma | 1339           | 306           |
| No Tumor   | 1595           | 405           |
```

[Here is a link to the final paper](https://github.com/srt3264/Brain-Tumor-MRI-Classification/blob/main/Final_Paper.pdf)


[Here is a link to the final presentation](https://github.com/srt3264/Brain-Tumor-MRI-Classification/blob/main/ML%20imaging%20powerpoint.pdf)
