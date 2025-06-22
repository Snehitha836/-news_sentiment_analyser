
"# news_sentiment_analyser"
A full-stack sentiment analysis system combining machine learning and web development using TensorFlow, Keras, Snorkel, and Django.

Project Overview

This project classifies news headlines into positive or negative sentiments using a custom-trained deep learning model. It scrapes headlines from the web, labels data with weak supervision (Snorkel and Vader), and visualizes sentiment metrics in a web dashboard.

Features

Sentiment classification with 95.85% validation accuracy
Web interface built using Django
Web scraping using BeautifulSoup
Data labeling using VADER and Snorkel
Visualization of user-submitted sentiment statistics
Authentication-ready setup
Tech Stack

Python
TensorFlow, Keras
Django, HTML/CSS/JavaScript
BeautifulSoup
Snorkel, VaderSentiment
Matplotlib, Pandas
- Download the required files.
- Open command prompt and change directory to that folder.
  - Use the following command:
    ```bash
    cd C:\Users\chara\Documents\Python  # replace directory with your directory
    ```
- Create a virtual environment using the following command:
    ```bash
    py -m venv env_name
    ```
- Activate environment:
    ```bash
    env_name\scripts\activate.bat
    ```
- Install all the dependencies using requirements.txt file with following command:
    ```bash
    pip install -r requirements.txt
    ```
- Run the following command to run the website:
    ```bash
    python manage.py runserver
    ```
- Please note that the displayed data of performance and accuracy is not meaningful because we haven't tested on real examples more
![Project Diagram](/Images/Screenshot_15-6-2024_225654_127.0.0.1.jpeg)
