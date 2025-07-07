MNIST Digit Classifier (Flask + TensorFlow)
This is a simple web application built using Flask and TensorFlow that allows users to upload an image of a handwritten digit (0–9), and the model predicts the digit using a pre-trained Convolutional Neural Network (CNN) trained on the MNIST dataset.

📁 Project Structure
mnist_digit_classifier/
├── app.py
├── model.hdf5
├── templates/
│   ├── index.html
│   └── result.html

*** 🧠 Features  ***
Upload an image containing a handwritten digit

Automatically preprocess and invert the image

Predict the digit using a trained CNN model

View the predicted digit in a simple web interface

*** 🛠️ Requirements  ***
Python <=3.12

Flask

TensorFlow

Pillow

NumPy

*** 🧠 Model Details  ***

Model type: CNN

Dataset used: MNIST Handwritten Digit Dataset

Saved as: model.hdf5

⚙️ How It Works
User uploads an image (.png, .jpg, etc.)

Image is:

Converted to grayscale

Inverted (so white background and black digits)

Resized to 28x28

Normalized and reshaped

CNN model predicts the digit

Prediction result is displayed on the web page

🧪 Running the App

python app.py
Then open your browser and go to:
📍 http://127.0.0.1:5000/

Ensure model.hdf5 exists in the same directory as app.py.

The uploaded image should clearly contain a single handwritten digit for best results.

🔒 License
This project is open-source and free to use under the MIT License.
