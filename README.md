# Hand Gesture Recognition

This project is a part of the Prodigy Infotech Machine Learning Internship, focusing on developing a hand gesture recognition model.

## Author

- **Author:** Muhammad Awais Akhter
- **GitHub:** [awais-akhter](https://github.com/awais-akhter)

## Problem Statement

The task involves developing a hand gesture recognition model capable of accurately identifying and classifying different hand gestures from image or video data. This technology aims to enable intuitive human-computer interaction and gesture-based control systems.

## Dataset

The dataset used for this project can be accessed via the following Kaggle link:
[Dataset Link](https://www.kaggle.com/datasets/gti-upm/leapgestrecog)

## Implementation Details

### Libraries Used
- `keras`, `matplotlib`, `seaborn`: Deep learning and visualization libraries
- `cv2`, `numpy`, `random`: Image processing and data manipulation
- `sklearn`: Machine learning utilities

### Workflow

- **Data Loading and Preprocessing**: Loaded the hand gesture dataset and prepared the data for training.
- **Visualizing Data**: Displayed sample images from different hand gesture categories to understand the dataset.
- **Normalizing the Data**: Scaled the pixel values of images between 0 and 1 for model training.
- **Model Training**: Built a convolutional neural network (CNN) model using Keras for hand gesture recognition.
- **Model Evaluation**: Evaluated the model's performance using accuracy metrics and plotted loss and accuracy curves.
- **Confusion Matrix**: Visualized the confusion matrix to understand the model's classification performance.

### Conclusion

The developed model achieved impressive results with a test accuracy of 100% and a train accuracy of 99.99%. This indicates the model's capability to accurately recognize and classify hand gestures.

## Execution

To run this code locally, follow these steps:
1. Download the dataset from [Kaggle](https://www.kaggle.com/datasets/gti-upm/leapgestrecog).
2. Set up the Jupyter Notebook environment or Python with necessary libraries.
3. Execute the code cells in the provided `hand-gesture-recognition.ipynb` file.

## Acknowledgments

- Kaggle for hosting the dataset used in this project.

Feel free to explore the code and dataset further for insights and improvements!
