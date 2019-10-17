# Breast-cancer-detection-neural-network

For this project i would be constructing a cancer prediction/detection network using TensorFlow and implemented via the high-level API tf. Keras and run on google's colaboratory.
But first a little bit of my background. This would explain my preference for the easiest and fastest way to machine learning! I am primarily a biologist by education and work expereince and just recently picked up CS/Data Science/ML to boost my knowledge for the 21st century. In light of this i would desribe myself as 85% biologist and 25% CS. This is a very new field for me and so far qiute exciting. This is my first deep learning project, so please bare with the simplicity!

Lets talk about the tools i would be using for the task at hand. Keras is a neural network library while TensorFlow is the open source library for a number of various tasks in machine learning. TensorFlow provides both high-level and low-level APIs while Keras provides only high-level APIs. ... Keras is built in Python which makes it way more user-friendly than TensorFlow...which also makes it good for simple-minded blokes like me! However installing TensorFlow has its hassles and one needs to be somewhat computer savy and have powerful enough hardware to wade through all the technicalities. Also one of the hurdles with TensorFlow is soring it in different dependencies, creating the local enviroment with Anaconda..etc. 
This is where Google's colab come into play. It is basically a Jupyter notebook running on the cloud, free of charge and has TensorFlow pre-installed, and to boot, comes with a free GPU. Its awesome!

#Data
For my source of data i looked no further than the UCI machine learning repository. This repository maintains a wide variety of data sets under different domains all at hand for use by the machine learning community. For this project i will be using the Breast Cancer Coimbra Data Set.There are 10 predictors, all quantitative, and a binary dependent variable, indicating the presence or absence of breast cancer.
The predictors are anthropometric data and parameters which can be gathered in routine blood analysis.
Prediction models based on these predictors, if accurate, can potentially be used as a biomarker of breast cancer.

Attribute Information:

Quantitative Attributes:
Age (years)
BMI (kg/m2)
Glucose (mg/dL)
Insulin (µU/mL)
HOMA
Leptin (ng/mL)
Adiponectin (µg/mL)
Resistin (ng/mL)
MCP-1(pg/dL)

Labels:
1=Healthy controls
2=Patients

