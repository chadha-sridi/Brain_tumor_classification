# Brain_tumor_classification
<p>Building a detection model, that classifies brain tumors into 4 categories: glioma, meningioma, notumor and pituitary.</p>
The data is MRI images of the human brain.
<p>For such a project you can use the dataset at the following link: https://www.kaggle.com/datasets/masoudnickparvar/brain-tumor-mri-dataset</p>
<p>This repository contains two attempts to train the Brain tumor classification model:</p>
<ol>
<li>A CNN model</li>
<li>Finetuning the VGG16 model</li>
</ol>

<h2>Data Augmentation</h2>
<p>Data augmentation is a technique used in ML to increase the size of the dataset, when it's small or to handle class imbalance</p>
It involves techniques such as rotation, flipping, scaling, cropping, translation, and adding noise to generate variations of the original images.
<h2>The VGG16 pretrained model</h2>
The VGG16 model is a deep convolutional neural network architecture. It consists of 16 layers, including convolutional and max-pooling layers followed by three fully connected layers. VGG16 is renowned for its simplicity and effectiveness in computer vision tasks, achieving state-of-the-art performance on the ImageNet dataset. 
<p>I fine-tune the VGG16 model on this specific tasks to leverage learned features from large datasets, improving performance, especially with the limited data at hand.</p>
<p>The accuracy achieved after only 3 epochs is of 0.9011</p>
