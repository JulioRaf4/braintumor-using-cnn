# Brain Tumor Diagnosis Using Convolutional Neural Networks (CNN)

This project focuses on the diagnosis of brain tumors utilizing Convolutional Neural Networks (CNNs). The primary objective is to develop a model capable of accurately classifying brain tumors from MRI images.

## Dataset

The dataset employed in this study is the [Brain Tumor MRI Dataset](https://www.kaggle.com/datasets/masoudnickparvar/brain-tumor-mri-dataset) available on Kaggle. It comprises MRI scans categorized into:

- **Glioma Tumor**
- **Meningioma Tumor**
- **Pituitary Tumor**
- **No Tumor**

For this project, a subset of the dataset was used, consisting of **800 images in total**, with **200 images for each type of tumor**. These were divided equally, with **100 images for training** and **100 images for testing** for each category.

## Methodology

1. **Data Preprocessing**: MRI images were preprocessed to enhance quality and ensure consistency. This included resizing, normalization, and other standard techniques.

2. **Model Architecture**: A CNN model was constructed to extract features and perform classification. The architecture included convolutional layers, pooling layers, and fully connected layers optimized for image classification tasks.

3. **Training**: The model was trained for **13 epochs** on the training dataset.

4. **Evaluation**: The model's performance was evaluated on the testing dataset using metrics such as accuracy, precision, recall, and F1-score.

## Results

The CNN model achieved satisfactory results given the limited dataset size and number of epochs. Future improvements may include increasing the number of epochs, utilizing the full dataset, or incorporating data augmentation techniques.

## References

- [Brain Tumor MRI Dataset](https://www.kaggle.com/datasets/masoudnickparvar/brain-tumor-mri-dataset)
- [Human brain tumor classification and segmentation using CNN](https://link.springer.com/article/10.1007/s11042-022-13713-2)
- [A hybrid deep CNN model for brain tumor image multi-classification](https://bmcmedimaging.biomedcentral.com/articles/10.1186/s12880-024-01195-7)