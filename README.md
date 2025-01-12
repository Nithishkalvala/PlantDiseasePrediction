---

# Plant Disease Detection

This project is a machine learning-based web application designed to predict plant diseases from leaf images. The application uses a pre-trained Convolutional Neural Network (CNN) model and is deployed using **Streamlit** for a simple and interactive user experience.

---

## Features

- **Image Upload**: Users can upload an image of a plant leaf to check for diseases.
- **Disease Detection**: The model analyzes the uploaded image and predicts the disease, if present.
- **Confidence Scores**: Provides the probability of each disease class for transparency.
- **User-Friendly Interface**: Built with Streamlit for an intuitive and responsive UI.

---

## Tech Stack

### **Frontend**
- **Streamlit**: For creating the web interface.

### **Backend**
- **Python**: Core programming language.
- **TensorFlow/Keras**: For the CNN model.
- **NumPy & Pandas**: For data manipulation.

---

## Installation
Before following the below steps make sure you execute the Jupyter Source file and extract h5 model(obtain your own credentials , download the dataset from the link given below)


## Usage

1. Upload an image of a plant leaf through the application.
2. Wait for the model to process and predict the disease.
3. View the prediction result and confidence score.

---

## Model Details

- **Architecture**: CNN trained on a dataset of plant leaf images.
- **Input**: Images resized to a standard dimension (e.g., 224x224 pixels).
- **Output**: Disease class (e.g., healthy, bacterial spot, powdery mildew).

---

## Contributing

Contributions are welcome! Feel free to raise issues or submit pull requests.

---

## License

This project is licensed under the MIT License.

---

## Acknowledgements

- Plant dataset sourced from [Kaggle]([https://www.kaggle.com/datasets/abdallahalidev/plantvillage-dataset]).
- Frameworks and tools: TensorFlow, Streamlit.

---

