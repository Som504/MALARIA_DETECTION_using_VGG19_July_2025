# Malaria Parasite Detection 

## Description
* Detected malarial parasites from thin blood smear images using deep learning. Images were collected from the Malaria screening research activity by the National Institutes of Health (NIH).

* Used VGG19, a pre-trained convolutional neural network model, and fine-tuned the model weights to classify infected vs uninfected images.

* Training was done using TensorFlow 2.0 on Google Colab. The entire network was incrementally unfrozen, and all layers were tuned for improved accuracy.

* Image augmentation and resizing were applied in real-time during training to improve generalization.

* Achieved a categorical cross-entropy loss of 0.159 and an accuracy of 95.7% on the test set.


```
Domain 		: Computer Vision, Machine Learning
Sub-Domain	: Deep Learning, Image Recognition
Techniques	: Deep Convolutional Neural Network, Transfer Learning, VGG19
Application	: Image Classification, Medical Imaging, Bio-Medical Imaging
```


## Dataset Details
Dataset Name		        : Malaria Cell Images Dataset
Original Dataset	        : [Malaria Datasets - National Institutes of Health (NIH)](https://lhncbc.nlm.nih.gov/publication/pub9932)
Kaggle Link                 : [MALARIA](https://www.kaggle.com/datasets/iarunava/cell-images-for-detecting-malaria/code)
Number of Classes		    : 2

## Tools/ Libraries
```
Languages	    : Python
Tools/IDE	    : Jupyter. Notebook and Google Collab
Libraries	    : TensorFlow 2.0, VGG19
```

## Performance Metrics
| Dataset | Training | Validation |
| ------- | -------- | ---------- |
| Accuracy | 0.9206	| 0.9503 |
| Loss | 0.14285 | 0.1762 |
| Precision | 0.96 |
| Recall | 0.96 |
		

## Model and Training Parameters
| Parameter | Value |
| --------- | ----- |
| Base Model |VGG19	|
| Loss Function | Categorical Crossentropy |
| Learning Rate | 0.0001 |
| Batch Size | 32 |
| Number of Epochs | Round 1 and 2: 10 epochs, Round 3: 35 epochs |	
 


