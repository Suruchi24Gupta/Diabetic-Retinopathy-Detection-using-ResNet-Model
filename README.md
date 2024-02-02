 Pioneered healthcare tech with Transfer Learning, ResNet models for 90%+ accuracy in Diabetic Retinopathy detection, and designed a robust GUI 
for seamless image classification, empowering medical professionals for early intervention in retinal health.

Abstract
Retinopathy is the most prevalent cause of avoidable vision impairment, mostly affecting the 
working-age population in the world. Recent research has given a better understanding in the 
clinical eye care practice to identify better and cheaper ways of identification and 
understanding, management, diagnosis and treatment of Retinal Diseases. In previous studies, 
the deep learning systems were usually trained directly end-to-end from original fundus images 
to the labels of DR grades, these end-to-end systems might fail to encode the lesion features 
due to the Black-box nature of deep learning. In our study, we improved the image processing 
quality using the RESNET model and increased the accuracy above 90 percent. The GUI we 
developed classifies the images into different classes of DR.

Algorithms Discussed
Using a ResNet (Residual Neural Network) model for the classification of retinal diseases 
involves several technical concepts and algorithms. ResNet is a deep learning architecture 
known for its ability to train very deep neural networks effectively. When applying ResNet to 
retinal disease classification, we encountered the following technical concepts and algorithms:

 ResNet Architecture: ResNet is a type of Convolutional Neural Network (CNN) designed 
for deep learning tasks. It utilizes residual connections to train very deep neural networks 
effectively by preventing the vanishing gradient problem.

 Convolutional Layers: These layers automatically extract features from retinal images. 
They're crucial for recognizing patterns in scans of the retina, helping the model identify 
signs of various diseases.

 Data Augmentation: Techniques like image rotation, scaling, and flipping increase the 
diversity of the training data, enhancing the model's ability to generalize from a limited 
dataset.

 Transfer Learning: Leveraging pre-trained ResNet models, originally trained on a large 
dataset like ImageNet, accelerates model training and boosts performance by transferring 
knowledge learned from one domain to retinal disease classification.

 Evaluation Metrics: Metrics such as accuracy, precision, recall, F1-score, and AUC-ROC 
are used to assess the model's performance, ensuring its ability to correctly identify retinal 
diseases.
