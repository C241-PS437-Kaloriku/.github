# Kaloriku

![Kaloriku Logo](/profile/asset/logo.png)

Welcome to **Kaloriku**, an innovative project designed to revolutionize personal health management through the integration of cloud computing, machine learning, and mobile development. Our mission is to help users monitor and manage their calorie intake seamlessly and intelligently.

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Technology Stack](#technology-stack)
- [Documentation](#documentation)
- [Group Members](#group-members)

## Overview

![alt Kaloriku](https://github.com/C241-PS437-Kaloriku/Mobile-Development/blob/main/Kaloriku.jpeg?raw=true)

Kaloriku is a comprehensive health management app that allows users to track their calorie intake and nutritional information effortlessly. By leveraging the power of cloud computing and machine learning, Kaloriku provides personalized dietary recommendations and insightful analytics to promote healthier eating habits.

## Features

- **Calorie Tracking**: Log your daily food intake with ease and get accurate calorie counts.
- **BMI Calculation**: Easily calculate your Body Mass Index to monitor your weight category.
- **Food Scan Detection**: Scan food items to automatically detect and log nutritional information.
- **Personalized Recommendations**: Receive tailored dietary advice based on your health goals.
- **Cloud Sync**: Seamlessly sync your data across multiple devices.
- **User-Friendly Interface**: Enjoy a smooth and intuitive mobile experience.

## Technology Stack

### Cloud Computing

- **Google Cloud Platform**: Hosting and scalable cloud services.
- **Node.js**: Backend server and API development.
- **Python**: Develop and deploy Machine Learning models.

### Machine Learning

- **TensorFlow**: Building and training machine learning models.
- **Keras**: High-level neural networks API.
- **Google Colab**: Cloud-based platform for training and experimentation.

### Mobile Development

- **Android Studio**: Integrated development environment for Android.
- **Kotlin**: Programming language for Android development.

## Documentation

### Machine Learning

#### Food Nutrition Detection

This project develops a machine learning model capable of identifying and analyzing the nutritional content of foods from images. The model uses advanced neural networks to estimate macronutrient values (proteins, fats, carbohydrates) and caloric content, assisting users in dietary planning and health management.

#### Features
- *Nutrient Estimation*: Predict macronutrient values from food images.
- *Calorie Calculation*: Estimate the total caloric content of meals.
- *User Input Handling*: Allow users to input specific dietary requirements or preferences.

#### Model Details
- *Architecture*: Utilizes a convolutional neural network (CNN) based on the MobileNetV2 architecture for efficient image processing.
- *Training Data*: Trained on a comprehensive dataset of food images labeled with nutritional information.
- *Accuracy Metrics*: Provides metrics on model accuracy, precision, and recall.

### Cloud Computing

- We use two deployed endpoints to run this application. The first endpoint is used for user functions and the second endpoint is used for food recommendation model usage. A service account with cloud storage and firestore permissions is required to be used for user storage and user image assets.
- We use the following technologies.
1. Python
2. Flask
3. Numpy, Keras. TensorFlow, Pandas, (requirement.txt)
4. NodeJS
5. ExpressJS

#### How To Run 
1. Backend Server
- Clone repository
- Install Node Package Manager and Dependencies ["npm install"]
- Create service account with firestore and cloud storage permission
- Put service-account.json into server folder
- Run the backend server ["npm run start"]
   
2. Models API
- Clone repository
- Install requirements ["pip install -r requirements.txt"]
- Run the Models API ["python main.py"]

### Mobile Development

### Features

- Provides food recommendations based on user input
- Stores user preferences using Datastore
- Uses TensorFlow Lite for image recognition
- Integrates with CameraX for capturing images
- Uses Retrofit for network communication

### Requirements

- Android Studio
- Kotlin
- Minimum SDK: 24
- Target SDK: 34
- Internet connection

### Project Setup

Add your base URLs in the `buildConfigField` in the `build.gradle.kts` file:
```
buildConfigField("String", "BASE_URL", "\"YOUR_URL\"")
buildConfigField("String","PREDICT_BASE_URL","\"YOUR_URL\"")
```
### Installation
1. Clone this repository:
   ```
   git clone https://github.com/C241-PS437-Kaloriku/Mobile-Development.git
   ```
2. Open the project in Android Studio.

Or you can download our app [here](https://drive.google.com/drive/folders/1iFrVO5cis-UixYz2z4Mv7Sm-rhe8zkWc)

### Project Structure
- `app/src/main/java/com/dicoding/kaloriku/` - Application source code
- `app/src/main/res/`  - Application resources




## Group Members
* Andre Dzikry Surya Atmojo 
* Ahmad Jibril Abdul Aziz 
* Ria Kristi 
* Raihan Anwar As’ad 
* Muhammad Raihan Akbar Nugraha 
* Sulthan Fairuzandy
* Muhamad Adib Septiawan 
