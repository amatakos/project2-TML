# Differential Privacy project
## Alexandros Matakos 015538460

### Description
For the project I decided to try and improve the results of the "Skin Cancer: Malignant vs. Benign" study we saw in the lectures, and to try to improve the results both in terms of accuracy and privacy. I am relying on this notebook for the data preparation https://github.com/RuchitaSuranagi/Skin-Cancer-Classifier/blob/main/Malignant_vs_Benign_DP_Opacus_Skin_Cancer_Classification.ipynb, and the model is a modification of the MNIST model from the previous exercise.

The reported test accuracy was $80.33$ and $47.58$, which practically means 0 differential privacy, and was the motivation for the project.

I uploaded the dataset to this github repo: https://github.com/amatakos/project2-TML, so if you wish to rerun the notebook I suggest you download it from there and put it in the main directory.

Admittingly, my results were not what I hoped for, and I suspect a more complex model would be required, but it was nevertheless quite fun trying to implement a simple CNN for this task, and I believe this also allowed me to have lower values.

### Results
My best results were the following:
Accuracy = 78.1%
$\epsilon$ = 22.92

### Implementation
Implementation at ex3/ex3.ipynb.
