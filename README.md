# Brain Tumor Diagnosis Using Convolutional Neural Networks (CNN)

This project focuses on the diagnosis of brain tumors utilizing Convolutional Neural Networks (CNNs). The primary objective is to develop a model capable of accurately classifying brain tumors from MRI images.

## Dataset

The dataset employed in this study is the [Brain Tumor MRI Dataset](https://www.kaggle.com/datasets/masoudnickparvar/brain-tumor-mri-dataset) available on Kaggle. It comprises MRI scans categorized into:

- **Glioma Tumor**
- **Meningioma Tumor**
- **Pituitary Tumor**
- **No Tumor**

## Methodology

1. **Data Preprocessing**: MRI images are preprocessed to enhance quality and ensure consistency, including steps like skull stripping, histogram equalization, and noise reduction.

2. **Model Architecture**: A CNN model is constructed to extract features and perform classification. The architecture includes convolutional layers, pooling layers, and fully connected layers optimized for image classification tasks.

3. **Training and Evaluation**: The model is trained on the preprocessed dataset, and its performance is evaluated using metrics such as accuracy, precision, recall, and F1-score.

## Results

The CNN model demonstrates high accuracy in classifying brain tumors, indicating its potential as a reliable tool for assisting in medical diagnoses.

## References

- [Brain Tumor MRI Dataset](https://www.kaggle.com/datasets/masoudnickparvar/brain-tumor-mri-dataset)
- [Human brain tumor classification and segmentation using CNN](https://link.springer.com/article/10.1007/s11042-022-13713-2)
- [A hybrid deep CNN model for brain tumor image multi-classification](https://bmcmedimaging.biomedcentral.com/articles/10.1186/s12880-024-01195-7)
