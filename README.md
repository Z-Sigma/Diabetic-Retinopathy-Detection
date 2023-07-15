# Diabetic Retinopathy Detection

This project focuses on the detection of diabetic retinopathy in retinal eye scans using a combination of a custom 13-layered CNN architecture and transfer learning with the EfficientNet model. The goal is to accurately classify retinal images into five categories related to the severity of diabetic retinopathy.

## Dataset

The dataset used in this project consists of retinal eye scans categorized into five classes: no diabetic retinopathy, mild, moderate, severe, and proliferative diabetic retinopathy. The dataset contains a diverse range of retinal images, enabling the model to learn patterns and features associated with different stages of diabetic retinopathy.

## Model Architecture

The project includes a custom 13-layered CNN architecture designed specifically for diabetic retinopathy detection. This architecture aims to capture important features and patterns present in retinal images. Additionally, transfer learning techniques were applied using the EfficientNet model as a feature extractor, leveraging its pre-trained weights to improve the model's performance.

## Model Training and Evaluation

The model was trained on a labeled dataset, with appropriate data preprocessing and augmentation techniques applied to enhance the learning process. The training process involved optimizing the model's parameters using an appropriate optimizer and loss function.

## Results

The final model achieved an accuracy of approximately 76% on the test dataset, demonstrating its ability to effectively classify retinal images into the five categories of diabetic retinopathy.

## Future Improvements

Further improvements can be made to enhance the performance of the model, such as exploring additional data augmentation techniques, experimenting with different hyperparameters, and leveraging larger and more diverse datasets. Additionally, incorporating interpretability methods, such as visualizing learned features, can provide insights into the model's decision-making process.

## Conclusion

The diabetic retinopathy detection project showcases the application of deep learning techniques for identifying and classifying retinal images related to diabetic retinopathy. With its custom CNN architecture and transfer learning approach, the project demonstrates the potential of machine learning models in assisting healthcare professionals in the early detection and management of diabetic retinopathy.

Please refer to the documentation and code in this repository for more details on the implementation and usage of the diabetic retinopathy detection.The model is in here: https://github.com/Z-Sigma/Diabetic-Retinopathy-Detection/blob/main/diabetic-retinopathy-final%20(1).ipynb
