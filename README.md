# Dancing with censored data: How to survive with explainable survival analysis?
**Tutorial @ ML in PL Conference 2023**

Mateusz Krzyziński, Mikołaj Spytek ([**MI2.AI**](https://www.mi2.ai))

## Description
As machine learning in survival analysis is gaining popularity, it is becoming crucial for ML practitioners to understand the unique aspects of this type of modeling and effectively interpret survival models.

This tutorial will guide you through a complete journey of examining the machine learning survival models with explainability and interpretability techniques. You will learn about various methods used for survival model analysis, both from the theoretical perspective and use cases. You will also become familiar with practical tools for creating explanations.

We will cover explanation techniques developed specifically for survival analysis (SurvSHAP(t), SurvLIME) but also demonstrate how to apply methods adapted from classification and regression problems in this specific field of survival analysis.

The emphasis will be on the insights these techniques unveil, along with discussions about their limitations, all demonstrated through specially curated examples complemented by code snippets.

The examples showcased during the tutorial will be mostly prepared using the ‘survex’ package for the R language. However, survex is capable of creating explanations also for models implemented in Python. Furthermore, a part of the tutorial’s examples will be presented in Python, too.

## Prerequisites 
- Tutorial will be conducted using both R and Python languages with the use of Jupyter notebooks. 
- Jupyter can be installed from PyPI (https://jupyter.org/install): 
```python
pip install jupyter
```
- Instructions for installing the R kernel for Jupyter are available in the first notebook of the tutorial, along with the installation of the required packages. 
- The required packages for Python are listed in `requirements.txt` and `survlimepy_requirements.txt` files. It is recommended to use Python virtual environments. 
