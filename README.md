# Emotion Detection

This project implements and compares Convolutional Neural Networks (CNN) architectures for emotion detection from facial expressions. The goal is to classify faces into one of seven emotion categories using deep learning models: ResNet50, VGG16, and a custom CNN. The project is deployed using Gradio and OpenCV.

## Models
- **ResNet50**: Pretrained ResNet50 model for emotion detection.
- **VGG16**: Pretrained VGG16 model for emotion classification.
- **Custom CNN**: A custom convolutional network model designed for emotion detection.

Note: Due to file size restrictions, model files (`Custom_CNN_model.keras`, `Final_Resnet50_Best_model.keras`) are not included in the repository.

## Dataset

The dataset used is the **FER-2013** dataset, available on [Kaggle](https://www.kaggle.com/datasets/msambare/fer2013). It contains 48x48 pixel grayscale images of faces, each labeled with one of the following emotions:

- 0: Angry
- 1: Disgust
- 2: Fear
- 3: Happy
- 4: Sad
- 5: Surprise
- 6: Neutral

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/Ani2599/Emotion-Detection.git
    ```

2. Install the dependencies:
    ```bash
    pip install -r requirements.txt
    ```

## Files

- **Emotion_Detection_Complete_Project.ipynb**: Jupyter notebook containing the full project, including training and evaluation of models.
- **emotion_app.py**: Python file for emotion detection using OpenCV.
- **test.py**: Python file for testing the emotion detection model.
- **requirements.txt**: List of dependencies required to run the project.

## Usage

1. Train and test models using the Jupyter notebook or by running `test.py` and `emotion_app.py`.
2. Use Gradio for web-based deployment of the emotion detection model.

## Contributing

Feel free to fork the repository and submit pull requests. Contributions are welcome to improve the models and performance.

## License

This project is licensed under the MIT License.


