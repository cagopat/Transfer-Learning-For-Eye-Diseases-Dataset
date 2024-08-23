# Transfer-Learning-For-Eye-Diseases-Dataset
Overview


This project focuses on classifying various eye diseases using deep learning techniques, particularly transfer learning and data augmentation. The model leverages pre-trained convolutional neural networks (CNNs) and fine-tunes them to accurately classify eye diseases from medical images.


The dataset used for this project can be found on Kaggle: [Eye Diseases Dataset](https://www.kaggle.com/datasets/walaaomara/eye-diseases/data).



![image](https://github.com/user-attachments/assets/04700b2a-db9e-4145-82e9-6018a164d1f0)



Features


Transfer Learning: VGG16 is the base model as it displayed a stronger performance on this particular dataset than the other architectures like Xception.


Data Augmentation: Applies techniques such as rotation, flipping, and zooming to artificially increase the size of the training dataset and improve model generalization.


Evaluation: The model's performance is evaluated using metrics like accuracy, precision, recall, and F1-score.

Results

The project achieved an accuracy of 96.68% on the test set, demonstrating the effectiveness of transfer learning and data augmentation in improving model performance on limited data.



![image](https://github.com/user-attachments/assets/9f32cc5e-aea8-46b4-8b47-e0294e178c3a)

Acknowledgments
The project uses pre-trained models from Keras Applications.
Data augmentation techniques inspired by various deep learning research papers.
