# Imageclassification
## Image Classification using MobileNetV2 with Image Display

This Python script demonstrates how to perform image classification using the pre-trained MobileNetV2 model provided by TensorFlow Keras. It fetches a random image from an online source (`picsum.photos`), displays the image using Matplotlib, preprocesses it for the model, predicts its content, and prints the top 3 predicted labels along with their confidence scores.

---

### Features

*   Loads the pre-trained MobileNetV2 model with 'imagenet' weights.
*   Fetches a random image from a specified URL (`https://picsum.photos`).
*   Displays the fetched image in a plot window.
*   Resizes and preprocesses the image to meet MobileNetV2 input requirements (224x224 pixels).
*   Performs inference using the model to classify the image.
*   Decodes the predictions into human-readable labels (using ImageNet classes).
*   Outputs the top 3 most likely classifications with their probabilities.
*   Includes basic error handling for image fetching.

---

### Requirements

You need Python 3 installed, along with the following libraries:

*   `tensorflow`: For the core deep learning framework and Keras API.
*   `Pillow` (PIL Fork): For image manipulation (opening, resizing).
*   `numpy`: For numerical operations, especially array handling.
*   `requests`: For fetching the image from the URL.
*   `matplotlib`: For displaying the image.
