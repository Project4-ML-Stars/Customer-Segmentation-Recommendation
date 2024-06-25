
# Customer Segmentation Recommendation



### About

The Customer Segmentation Recommendation project leverages Machine Learning to analyze user data and preferences, providing product recommendations at a micro-segment level. This also supports the marketing team in devising more effective marketing strategies by understanding customer buying behavior.

Micro-segmentation involves dividing a potential customer market into groups or segments based on various characteristics.

#### Types of Market Segmentation:

Demographic segmentation: Age, gender, income, etc.
Psychographic segmentation: Interests, lifestyle, etc.
Behavioral segmentation: Purchase habits, brand interactions, etc.
Geographic segmentation: City, country, etc.

Based on data analysis, users are categorized into groups such as:

Tech Enthusiasts: Tech-Savvy, Luxurious, Flagship Killers, Others.
Brand Aficionados: Apple, Samsung, Huawei, Others.
Camera Enthusiasts: Sensible, Photophile, Selfie Lover.

### Technical Architecture

![Architecture](images/Architecture.png)

### Technology Stack

Frontend: Developed using HTML/CSS and Vanilla JavaScript
Backend: Developed using Flask
Machine Learning: Classification and Regression Algorithms, Neural Networks
Data Source: Models trained using scraped data from the Internet
Dataset: Includes user purchase history, product specifications, and micro-segment user data stored in Excel

### Features

#### Marketing Head

Analyze customer buying behavior based on various parameters and categorize them accordingly.
Formulate better marketing strategies by understanding customer preferences for specific products.
Assess product sales and take actions to enhance performance.
Predict product performance based on specifications (e.g., mobile phones).
Target specific audiences based on product performance.
Identify and predict target audiences for specific products.
Recommend similar products to customers based on their preferences.

## Screenshots

### Dashboard (Analytics)

![1](images/1.png)


### Prediction (Performance and User Category)

![pred1](images/6.png)

### Recommendations

![recom](images/10.png)


Project Configuration Guide
Python Installation

Install Python version 3.5.9 on your machine.
Download link: python.org/downloads
Python Libraries Installation

After successfully installing Python, install the following libraries:


Package	Version
matplotlib
missingno
numpy
pandas
sklearn
tensorflow
keras
seaborn
flask
flask-Cors

Installation Instructions:
Open the command prompt as an administrator and use the command pip install <library-name> to install each library.

Project Setup

After installing the required libraries, navigate to the "Customer-Segmentation-Recommendation" folder where your project is located. Open the folder and run the "server.py" file. Running this file will start the project server.

Frontend Setup

Once the "server.py" file is running successfully, navigate to the "frontend -> html" folder and run the "dbshome.html" file. This completes the project setup.

Code Understanding and Analysis

For a better understanding of the code, install Anaconda Navigator. Open Jupyter Notebooks and navigate to the "python-notebooks" folder within Jupyter. Run the files in this folder to explore the code.

This guide ensures a systematic approach to setting up and understanding the project.