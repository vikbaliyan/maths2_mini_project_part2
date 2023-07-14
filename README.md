# VisualVortex

VisualVortex is a sophisticated image classification app developed with the power of the MobileNet V2 model. This application offers users a platform to upload and analyze images accurately and gain valuable insights into their visual content.

## Project Overview

VisualVortex employs the MobileNet V2 deep learning model that has been trained on a large dataset of images for precise image classification and object recognition. Users can upload an image through the app, which is then processed by VisualVortex using the pre-trained model to identify the objects within. The analysis results are displayed to the user, offering a practical tool for image understanding and analysis.

## Installation & Usage

### Prerequisites

Ensure the following dependencies are installed before running VisualVortex:

- Python 3
- TensorFlow
- OpenCV
- NumPy

### Installation and Running the App

Follow these steps to set up and run VisualVortex:

```bash
# Clone the repository to your local machine
git clone <repo_link>

# Navigate to the cloned repository
cd <repo_name>

# Install the required packages
pip install -r requirements.txt

# Run the app.py file using Python
streamlit run app.py

## Features

- User-friendly interface for uploading and analyzing images.
- Utilizes the MobileNet V2 model for accurate image classification.
- Real-time processing and analysis of uploaded images.
- Displays the top predictions and probabilities for the identified objects.
- Supports a wide range of image formats and sizes.

## References:

1. MobileNetV2: Inverted Residuals and Linear Bottlenecks, Mark Sandler, Andrew Howard, Menglong Zhu, Andrey Zhmoginov, Liang-Chieh Chen, 2018.
2. TensorFlow: An open-source platform for machine learning, https://www.tensorflow.org/
3. OpenCV: Open Source Computer Vision Library, https://opencv.org/
4. NumPy: The fundamental package for scientific computing with Python, https://numpy.org/
5. ChatGPT OpenAi
6. https://www.section.io/engineering-education/building-a-multiclass-image-classifier-using-mobilenet-v2-and-tensorflow/
7. https://medium.com/@nutanbhogendrasharma/image-classification-model-mobilenet-v2-from-tensorflow-hub-8191b28a202a
8. "The OpenCV Library", Gary Bradski, Dr. Adrian Kaehler, 2018. [Link](https://www.mendeley.com/catalogue/the-opencv-library/)
9. "NumPy: A Guide to NumPy", Travis E. Oliphant, 2006. [Link](https://numpy.org/doc/stable/user/)
10. "MobileNetV2: Inverted Residuals and Linear Bottlenecks", TensorFlow Hub, 2020. [Link](https://tfhub.dev/s?module-type=image-classification)
11. "Image Classification with Transfer Learning using MobileNetV2", TensorFlow Tutorial. [Link](https://www.tensorflow.org/tutorials/images/transfer_learning)


## License

This project is licensed under the [MIT License](LICENSE).
