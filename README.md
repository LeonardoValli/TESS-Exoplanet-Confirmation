# Prediction of Confirmed Status of Detected TESS Exoplanet Candidates using Weka 

Alan Zhu and Leonardo Valli

Thomas Jefferson High School for Science and Technology

Machine Learning Quarter 1 Project

## Abstract
The search for exoplanets, planets orbiting stars other than our sun, is a growing field in 
astronomy. There are currently approximately 5,800 confirmed exoplanets. There are thousands 
more exoplanet candidates — possible planets identified by satellites — awaiting confirmation 
by scientists. However, the process of confirming exoplanet candidates is costly and 
time-consuming, requiring several hours of data collection using valuable time on research 
telescopes, followed by extensive data analysis done by scientists. 
 
In our project, we developed machine learning models to predict true positive and 
false positive exoplanet candidates. Using a random forest model, we achieved 87% accuracy
in classifying exoplanet candidates using raw planetary data and 96% accuracy using parameters
informed by scientist input.

## Reports
The project report paper is available in PDF and DOCX formats, and the project presentation is available in PDF and PPTX formats.

## Preprocessing

To run the preprocessing code, download the TESS dataset [here](https://exofop.ipac.caltech.edu/tess/view_toi.php), then run `Preprocessing.ipynb` in a Jupyter Notebook or Google Colab. For Colab, load the dataset into Colab, and then do Runtime -> Run all to run the code.

The `datasets/` directory contains the pre-processed datasets.

## Classification
Classification on each of the datasets was done in Weka using the following models:
- One-R
- Naive Bayes
- Random Forest
- Multilayer Perceptron

The results can be found in the `results/` directory.
