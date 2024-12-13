# Brain Tumor Diagnosis Using Convolutional Neural Networks (CNN)

This project focuses on the diagnosis of brain tumors utilizing Convolutional Neural Networks (CNNs). The primary objective is to develop a model capable of accurately classifying brain tumors from MRI images.

## Dataset

The dataset employed in this study is the [Brain Tumor MRI Dataset](https://www.kaggle.com/datasets/masoudnickparvar/brain-tumor-mri-dataset) available on Kaggle. It comprises MRI scans categorized into:

- **Glioma Tumor**
- **Meningioma Tumor**
- **Pituitary Tumor**
- **No Tumor**

For this project, a subset of the dataset was used, consisting of 200 images for each type of tumor. These were divided equally, with **100 images for training** and **100 images for testing**.

The complete dataset is available for download at the following link: [Brain Tumor MRI Dataset](https://www.kaggle.com/datasets/masoudnickparvar/brain-tumor-mri-dataset).

## Methodology

1. **Data Preprocessing**: MRI images are preprocessed to enhance quality and ensure consistency, including steps like skull stripping, histogram equalization, and noise reduction.

2. **Model Architecture**: A CNN model is constructed to extract features and perform classification. The architecture includes convolutional layers, pooling layers, and fully connected layers optimized for image classification tasks.

3. **Training and Evaluation**: The model is trained on the preprocessed subset of the dataset, and its performance is evaluated using metrics such as accuracy, precision, recall, and F1-score.

## Results

The CNN model’s performance was affected by the limited number of images used in training and testing. While the model initially showed potential, the reduced dataset size likely contributed to lower accuracy and generalization. Future improvements can be achieved by utilizing the full dataset and incorporating data augmentation techniques.

## References

- [Brain Tumor MRI Dataset](https://www.kaggle.com/datasets/masoudnickparvar/brain-tumor-mri-dataset)
- [Human brain tumor classification and segmentation using CNN](https://link.springer.com/article/10.1007/s11042-022-13713-2)
- [A hybrid deep CNN model for brain tumor image multi-classification](https://bmcmedimaging.biomedcentral.com/articles/10.1186/s12880-024-01195-7)
