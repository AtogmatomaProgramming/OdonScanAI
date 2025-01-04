<h1 align="center"> OdonScanAI </h1>

<p align="center">
   <img src="https://img.shields.io/badge/STATUS-EN%20DESAROLLO-green">
   <img src="https://img.shields.io/badge/VERSION-v.1.0.0-red">
   <img src="https://img.shields.io/badge/LICENCE-AtogmatomaSoftware-blue">
   <img src="https://img.shields.io/badge/LANGUAGE-JupyterNotebook-purple">
   <img src="https://img.shields.io/badge/LIBRARY-TensorFlow/Sequential-yellow">
   </p>
<p align="justify">

- [Overview](#overview)
- [Project Structure](#project-structure)
- [Technologies Used](#technologies-used)
- [Contact Information](#contact-information)

## Overview

<p align="justify">
OdonScanAI is the backbone of the OdonScan mobile application, designed to recognize marine species through AI technology. This repository hosts the scripts required to train, evaluate, and deploy a convolutional neural network (CNN) for species identification. 
</p>

## Project Structure

This project consists of three main scripts, each focused on a specific task:

1. **Frame Extraction and Cataloging**  
   <p align="justify">Extracts, catalogs, and saves frames from video files of marine species for dataset preparation. This script is crucial for organizing data and ensuring compatibility with the training process.  
   File: <i>manage_frames.ipynb</i></p>

2. **Model Creation and Evaluation**  
   <p align="justify">Defines and trains a CNN using TensorFlow's Sequential API. It includes model evaluation and metrics generation to ensure robust performance.  
   File: <i>manage_model.ipynb</i></p>

3. **Model Conversion for Deployment**  
   <p align="justify">Converts the trained Keras model into TensorFlow Lite (TFLite) format, optimizing it for deployment on mobile devices.  
   File: <i>manage_format_model.ipynb</i></p>

## Technologies Used

- **Jupyter Notebook**: Interactive development environment for prototyping scripts.
- **TensorFlow/Keras**: Framework for building and training the CNN.
- **TensorFlow Lite**: Tool for optimizing the model for mobile devices.
- **NumPy**: Data manipulation and preprocessing.
- **Matplotlib**: Visualization of metrics and results.
- **Pandas**: Dataset management and analysis.

## Contact Information

<p align="justify">
I am glad to heard your feedback, suggestions, and inquiries about the OdonScan project! Feel free to reach out to us through the following channels:
</p>

- **Developer/Project Lead**: AtogmatomaProgramming
- **Email**: [albert.candelario.oficial@gmail.com](mailto:albert.candelario.oficial@gmail.com)
- **GitHub Repository**: [OdonScanAI GitHub Repo](https://github.com/AtogmatomaProgramming/OdonScanAI)
- **Spanish Institute of Oceanography (IEO)**: For collaboration inquiries, visit [IEO Official Website](https://www.ieo.es).

