# eye_disease_detection_ODIR5k

# Eye Disease Detection Program

## Project Overview
This project aims to develop a deep learning model for the detection and classification of various eye diseases, including cataracts, diabetic retinopathy, and glaucoma. By leveraging advanced machine learning techniques, the program seeks to provide accurate diagnoses based on retinal images.

## Table of Contents
- [Installation](#installation)
- [Usage](#usage)
- [Dataset](#dataset)
- [Model Training](#model-training)
- [Evaluation Metrics](#evaluation-metrics)
- [Contributing](#contributing)
- [License](#license)

## Installation
To set up the project, follow these steps:

1. Clone the repository:
```bash
git clone https://github.com/yourusername/eye-disease-detection.git
cd eye-disease-detection
```

2. Install the required packages:
```bash
pip install -r requirements.txt
```

3. Ensure you have the necessary environment set up (Python 3.x).
```bash
python main.py --image_path path/to/image.jpg
```

## Usage
After installation, you can run the model using the following command:
Replace `path/to/image.jpg` with the path to the image you want to analyze.

## Dataset
The model is trained on a dataset containing images of different eye conditions. The dataset can be obtained from Kaggle or other medical image repositories. Ensure that images are organized into appropriate class folders for training and validation.

### Key Dataset Links:
- **Kaggle Dataset**: [Eye Diseases Classification Dataset](https://www.kaggle.com/datasets/gunavenkatdoddi/eye-diseases-classification)
- **Prepared Dataset**: [Google Drive Link](https://drive.google.com/drive/folders/1HEti1Qv_-iXiOf2zp2amG8XFgk-HPuLj?usp=sharing)

## Model Training
The program employs Convolutional Neural Networks (CNNs) for image classification. Key steps include:

1. **Data Preprocessing**: 
   - Resize images to 224x224 pixels.
   - Normalize pixel values.
   - Apply data augmentation techniques.

2. **Model Architecture**: 
   - Implement various CNN architectures (e.g., ResNet, VGG).
   - Conduct hyperparameter tuning to optimize performance.

3. **Training**: 
   - Split the dataset into training (80%), validation (10%), and testing (10%) sets.
   - Use an appropriate optimizer (e.g., Adam) for efficient training.

## Evaluation Metrics
The model's performance is evaluated using several metrics:
| Metric        | Description                                                        |
|---------------|--------------------------------------------------------------------|
| Accuracy      | Proportion of correctly classified images                          |
| Precision     | The ratio of true positive predictions to all positive predictions |
| Recall        | The ratio of true positive predictions to all actual positives     |
| F1 Score      | The harmonic mean of precision and recall                          |

## Contributing
Contributions are welcome! If you have suggestions for improvements or features, please create a pull request or open an issue.

## License
This project is licensed under the MIT License. See the LICENSE file for more details.
