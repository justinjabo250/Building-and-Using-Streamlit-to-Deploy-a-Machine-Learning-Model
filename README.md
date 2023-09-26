
# 🚀 Building and Deploying a Machine Learning Model with Streamlit. 🚀

[![View Repositories](https://img.shields.io/badge/View-My_Repositories-blue?logo=GitHub)](https://github.com/justinjabo250?tab=repositories)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5?logo=linkedin&logoColor=orange)](https://www.linkedin.com/in/jabo-justin-2815341a2/) 
[![View My Profile](https://img.shields.io/badge/MEDIUM-Article-purple?logo=Medium)](https://medium.com/@jabojustin250)
[![Docker App](https://img.shields.io/badge/Streamlit-App-yellow)](https://huggingface.co/spaces/Justin-J/Sales-forecasting-and-prediction-Using-Streamlit)

## Building and Deploying a Machine Learning Model with Streamlit

<img src="https://i.ytimg.com/vi/Klqn--Mu2pE/maxresdefault.jpg" width="550">

## Introduction

We will go through the process of building and deploying a machine learning model using Streamlit. Streamlit is an open-source Python library that enables you to quickly create custom interfaces for your machine learning models, allowing you to deploy them without needing to build a complete web application.

# 📁 Dataset

Public dataset can be found [`here`](https://github.com/Azubi-Africa/Career_Accelerator_LP2-Regression/blob/main/store-sales-time-series-forecasting.zip)

# 🚀 Setup

Install the required packages to be able to run the evaluation locally.

You need to have [`Python3`](https://www.python.org/) on your system. Then you can clone this repo and being at the repo's root (`root :: repo_name> ...`) follow the steps below:

- Windows:

```python
python -m venv venv; venv\Scripts\activate; python -m pip install -q --upgrade pip; python -m pip install -qr requirements.txt
```

- Linux & MacOs:

```python
python3 -m venv venv; source venv/bin/activate; python -m pip install -q --upgrade pip; python -m pip install -qr requirements.txt
```

The both long command-lines have a same structure, they pipe multiple commands using the symbol **;** but you may manually execute them one after another.

1. **Create the Python's virtual environment** that isolates the required libraries of the project to avoid conflicts;
2. **Activate the Python's virtual environment** so that the Python kernel & libraries will be those of the isolated environment;
3. **Upgrade Pip, the installed libraries/packages manager** to have the up-to-date version that will work correctly;
4. **Install the required libraries/packages** listed in the `requirements.txt` file so that it will be allow to import them into the python's scripts and notebooks without any issue.

**NB:** For MacOs users, please install `Xcode` if you have an issue.

## 🔧 Building the Streamlit App

We will use the Streamlit library to create the app. The app will have input components such as dropdowns, sliders, and radio buttons. These components take in user input and store them as variables. We will also define an output component, which displays the churn prediction generated by the machine learning model.

# 🚀 Execution

**NOTE**: You must download **model.pkl** and **merged_train_data** from [`here`](https://huggingface.co/spaces/Justin-J/Sales-forecasting-and-prediction-Using-Streamlit) (files too large for github) 
and also move **scaler.pkl** and **encoder.pkl** to the root folder before running the app. 

To Run the app: Go to your terminal and type:

```python
streamlit run app.py
```
This will run the app and give you a link to open in your browser. Click on the link and you're good to go!

## Screenshots!
![ezgif com-optimize (1)](https://github.com/ikoghoemmanuell/Deploying-a-ML-Model-with-Streamlit/assets/102419217/e64d3bc7-99a0-45a0-9aee-53a33e3f787e)

## 👏 Support

If you found this article helpful, please give it a clap or a star on GitHub!

---

<p>&copy; 2023 Justin Jabo</p>
