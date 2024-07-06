# Weather Classification using ResNet 50

## Overview

This project aims to classify various weather conditions using Convolutional Neural Networks (CNNs). By leveraging deep learning techniques, specifically the ResNet50 architecture, our model can identify a wide range of weather situations, such as:

- Day/Night
- Snow
- Glare or No Glare
- Rain
- Fog or No Fog
- Thunderstorms
- Sandstorms

The project integrates six distinct models into a unified framework to enhance weather detection accuracy across different industries. This robust and versatile methodology is designed to be user-friendly and adaptable, making it accessible to practitioners without special expertise.

## Project Structure

- **Code:** The code for the project is available in this repository. It includes scripts for data preprocessing, model training, and evaluation.
- **Models:** The trained model files (.h5) can be accessed via [Google Drive](https://drive.google.com/drive/folders/1CtRv5DPV4wPWPGYCOdIJijCLZcmvdN7Q?usp=drive_link).

## Dataset

The dataset used for training the models was manually collected and augmented by our team. This ensures a diverse and representative set of images covering various weather conditions.

## Getting Started

1. Clone the repository:
    ```bash
    git clone https://github.com/your-username/weather-classification.git
    cd weather-classification
    ```

2. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```

3. Download the model files from [Google Drive](https://drive.google.com/drive/folders/1CtRv5DPV4wPWPGYCOdIJijCLZcmvdN7Q?usp=drive_link) and place them in the `models` directory.

4. Run the prediction script:
    ```bash
    python predict.py --image_path path_to_your_image.jpg
    ```

## Data Augmentation Techniques

To improve the model's robustness and accuracy, various data augmentation techniques were applied, such as:

- Rotation
- Scaling
- Flipping
- Cropping

These techniques help the model generalize better to different weather conditions by introducing variability in the training data.

## Contributing

We welcome contributions to enhance this project. Please fork the repository and create a pull request with your changes.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.


