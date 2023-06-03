# Cotton Crop Disease Detector

The Cotton Crop Disease Detector is a web application that uses machine learning techniques to identify and classify diseases in cotton crops. The application is built using TensorFlow, Flask, HTML, CSS, and Bootstrap.

### Features 

* __Cotton Disease Classification:__ The application is trained on a dataset of cotton crop images to classify diseases accurately.
* __Web Interface:__ The application provides a user-friendly web interface for users to upload cotton crop images and receive disease classification results.
* __Interactive Design:__ The web interface is designed using HTML, CSS, and Bootstrap to create an attractive and responsive user experience.

### Requirements

To run the Cotton Crop Disease Detector, you need to have the following software installed:

* Python (version 3.6 or higher)
* TensorFlow (version 2.0 or higher)
* Flask (version 1.1.2 or higher)
HTML5, CSS3
* Bootstrap (version 4.6.0 or higher)

### Installation

1. Clone this repository to your local machine:

> git clone https://github.com/SahilWagh1/cotton-crop-disease-detector.git

2. Navigate to the project directory:

> cd cotton-crop-disease-detector
Install the required Python packages using pip:

3.Install the required Python packages using pip:
>pip install -r requirements.txt

4. Start the Flask development server:

> flask run

5.Open your web browser and navigate to __http://localhost:5000__ to access the Cotton Crop Disease Detector.

### Usage

1. Access the web interface by opening your web browser and visiting __http://localhost:5000__.

2. Click on the "Choose File" button to select an image of a cotton crop with a disease from your local machine.

3. Click the "Upload" button to submit the selected image to the application for disease classification.

4. Wait for the application to process the image and display the classification results, including the predicted disease.

5. You can repeat the process with different images to classify diseases in cotton crops.

### Model Training

The machine learning model used in the Cotton Crop Disease Detector is trained using TensorFlow. If you wish to train your own model or retrain the existing one, follow these steps:

1. Prepare a labeled dataset of cotton crop images with their corresponding disease labels.

2. Split the dataset into training and validation sets.

3. Use the training set to train the model using a suitable deep learning architecture.

4. Evaluate the trained model on the validation set to assess its performance.

5. Save the trained model in the __models__ directory of the project.

6. Update the model path in the Flask application code __(app.py)__ to use your trained model.

7.Restart the Flask server and test the updated model using the web interface.

### Credits 

* This project is inspired by the work of various contributors in the field of crop disease detection using machine learning.
* The TensorFlow library is used for building and training the machine learning model.
* Flask is used for building the web application.
* HTML, CSS, and Bootstrap are used for designing the web interface.
### License
The Cotton Crop Disease Detector is open-source software licensed under the __MIT License__. Feel free to modify and distribute it as per the terms of the license.
