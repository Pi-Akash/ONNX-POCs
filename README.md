# ONNX-POCs
Experiments I did to understand ONNX 

ONNX Models.ipynb : Notebook to learn how to convert a small pytorch model to ONNX format and then use the ONNX model in a Tensorflow environment.
You can download the dataset used in the notebook 

[Dataset](https://www.kaggle.com/cactus3/basicshapes)

I have performed second part of the objective that is to run the onnx model in Tensorflow environment in Kaggle notebook.

[Kaggle Notebook](https://www.kaggle.com/piakash96/onnx-models)

ONNX extended.ipynb : I was looking for a way to convert models made from scratch in numpy into ONNX format models.
In this notebook i have taken a small regression problem and performed following operations:
1. Performed gradient descent to calculate the weights of the model.
2. Saved the model as a pickle file.
3. Converted the pickle file into onnx format.
4. Used the ONNX model to predict the output.

Note: Please install required libraries as given in the notebook before running.

You can find the model and other resources in the "resources" folder in case you directly want to use the model itself.
