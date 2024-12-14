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

## Running .ipynb Files Locally with Jupyter and Poetry

Follow the steps below to run `.ipynb` files locally using Jupyter and Poetry on different operating systems.

### Prerequisites

Ensure that you have Poetry installed on your system. If not, install it by following the [official Poetry installation guide](https://python-poetry.org/docs/#installation).

### Steps

#### 1. Setting Up the Environment

- Open a terminal or command prompt.
- Create a new Poetry project or navigate to your existing project directory.

```bash
poetry init
```

- Add Jupyter as a dependency:

```bash
poetry add notebook
```

#### 2. Activate the Environment

- Activate the virtual environment created by Poetry:

```bash
poetry shell
```

#### 3. Run Jupyter Notebook

- Start the Jupyter Notebook server:

```bash
jupyter notebook
```

- Open your browser and navigate to the provided URL to access Jupyter Notebook.

### Platform-Specific Instructions

#### Windows

1. Ensure that Python and Poetry are installed and added to your PATH.
2. Follow the general setup steps above.

#### macOS

1. Use Homebrew to install Python if necessary: `brew install python`.
2. Follow the general setup steps above.

#### Linux

1. Use your package manager (e.g., `apt`, `yum`, or `dnf`) to install Python if necessary.
2. Follow the general setup steps above.

### Additional Tips

- If you encounter issues with Jupyter Notebook not being recognized, ensure the Poetry environment is active (`poetry shell`).
- To stop the server, press `Ctrl+C` in the terminal where the Jupyter server is running.

## References

- [Brain Tumor MRI Dataset](https://www.kaggle.com/datasets/masoudnickparvar/brain-tumor-mri-dataset)
- [Human brain tumor classification and segmentation using CNN](https://link.springer.com/article/10.1007/s11042-022-13713-2)
- [A hybrid deep CNN model for brain tumor image multi-classification](https://bmcmedimaging.biomedcentral.com/articles/10.1186/s12880-024-01195-7)
