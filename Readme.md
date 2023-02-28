# Cuisine Recommender System

A machine learning web app that recommends recipes based on ingredient preferences.

## Installation
You must have python and node.js installed in your system<br>

1.Clone the repository:
```
git clone <repo url>
``` 
2.Navigate to the project directory: 
```
cd cuisine-recommender
```
3.Install the required Python packages: 
```
pip install -r requirements.txt
```
## Usage
![screenshot of cuisine recommender wep app](./img/cuisine%20recommender.png?raw=true "Screen Shot") <br>
1.Open the index.html file in your browser<br>

2.Enter the ingredients you have on hand into the form.<br>

3.Submit the form to view the recommended cusine.

## Model Details
The machine learning model used in this project is a Support Vector Machine (SVC) model. The model was trained on a dataset of cusines and their corresponding ingredients. The SVC model was chosen because it performs well on high-dimensional data like the ingredient vectors used in this project.

The SVC model was trained using the scikit-learn library in Python. The notebook used to train the model is included in the notebook.ipynb file.

The trained model was exported to an ONNX file using the onnxmltools library. The ONNX file and is used for making predictions in the web app.