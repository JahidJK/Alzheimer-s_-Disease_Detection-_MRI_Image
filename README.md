 Project Name: Alzheimer's Disease Detection in MRI Image by Deep Learning: A Transfer Learning Approach 

Data Acquisition: The MRI images Dataset was utilized in this investigation. The Kaggle website was the source of the publicly available dataset. Mild demented, moderate demented, non-demented, and very mild demented pictures are included in this collection. The database was ideal for DL since it contained excellent quality, cleansed data. We extracted 6400 photos from the dataset.

![image](https://github.com/user-attachments/assets/e99643a6-0102-4147-8d25-853dad5fb09d)

Dataset Split: 5121 images for training, 640 images for validation, and 639 images for testing.

Data Augmentation: To improve model robustness and enrich the dataset, use data augmentation techniques. Zooming, flipping, and rotation are a few possible techniques. For pre-trained models, all those images are resized to 224 × 224 pixels. We employed the data normalization technique to fit the models.

Deep Learning Models: We utilize three widely used DL architectures for feature extraction and classification: VGG16, EfficientNetB3, and EfficientNetB5.

Transfer Learning Phase: In Alzheimer's disease (AD) detection utilizing transfer learning, the process involves several key phases to effectively analyze brain images and classify potential instances of the disease. 

A flowchart that provides an overview of this study process.
![image](https://github.com/user-attachments/assets/1eac914c-2653-4919-ad86-a5b460147ba0)

Accuracy and loss graph of (a) VGG-16, (b) EfficientNet-B3, (c) EfficientNet-B5 model.

![image](https://github.com/user-attachments/assets/971ed965-c2c2-4eee-bdde-4ca53d5a6ae7)

AUC curve of a) VGG-16, b) EfficientNet-B3 and c) EfficientNet-B5

![image](https://github.com/user-attachments/assets/ff6b3f92-dfdf-43f6-9387-ecea53a047a5)

Table 1 shows the performance of the Models for Each Class.

![image](https://github.com/user-attachments/assets/23a7113a-8955-469f-945c-fa69a82e26c4)
