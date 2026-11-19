# Indoor Air Quality and Asthma Exacerbation Prediction

## Project Overview

This project aims to develop an IoT-based Indoor Air Quality Monitoring and Asthma Exacerbation Prediction System that helps users understand how indoor environmental conditions may affect their respiratory health.

The system uses an ESP32 connected to air quality sensors to continuously monitor PM2.5, VOC levels and humidity. The collected data is transmitted to AWS Cloud for processing and storage.

Along with environmental data, users complete a daily health questionnaire containing predefined questions about their respiratory symptoms. They can also optionally enter their peak flow readings to help track changes in their breathing.

Machine Learning and statistical analysis will be explored to identify patterns between indoor environmental conditions and asthma-related symptoms. Google's Gemini AI will provide simple, context-aware recommendations based on the collected information.

A web-based dashboard will display real-time air quality readings, health records, historical trends and alerts.

## Objectives

- Continuously monitor indoor air quality using IoT sensors.
- Measure PM2.5, VOC levels and humidity.
- Collect daily health information through predefined questionnaires.
- Allow users to optionally record their peak flow readings.
- Store environmental and health data using AWS Cloud services.
- Identify potential relationships between indoor air quality and asthma symptoms using Machine Learning.
- Integrate Gemini AI to generate simple recommendations.
- Provide a web dashboard for monitoring and tracking.

##  Key Features

### 1. Real-Time Air Quality Monitoring
- Monitor PM2.5, VOC levels and humidity.
- Collect readings using ESP32-connected sensors.
- Display current indoor air quality conditions.

### 2. Daily Health Assessment
- Users complete a predefined questionnaire once a day.
- Questions cover coughing, wheezing, shortness of breath and chest tightness.
- Users can record symptom severity and inhaler usage.
- Optional peak flow readings can be entered.

### 3. Asthma Risk Analysis
- Analyse environmental readings alongside health observations.
- Explore patterns that may indicate increased asthma exacerbation risk.
- Use Machine Learning and statistical analysis for risk estimation.

### 4. Gemini AI Integration
- Interpret environmental readings and health observations.
- Generate easy-to-understand recommendations.
- Help users recognise potential environmental triggers.

### 5. Web Dashboard
- Display real-time air quality readings.
- View historical environmental trends.
- Track daily health assessments.
- Display alerts and AI-generated recommendations.

## Technologies Used

| Technology | Purpose |
|---|---|
| ESP32 | Microcontroller for sensor connectivity |
| PM2.5 Sensor | Measures fine particulate matter |
| VOC Sensor | Detects volatile organic compounds |
| Humidity Sensor | Measures indoor humidity |
| AWS Cloud | Cloud infrastructure |
| Gemini AI | AI-powered recommendations |
| Machine Learning | Pattern identification and risk analysis |
| Web Technologies | Frontend dashboard |

## AWS Services

| AWS Service | Purpose |
|---|---|
| AWS IoT Core | Connects ESP32 and receives sensor data |
| AWS IoT Rules | Routes incoming sensor data |
| AWS Lambda | Processes incoming readings |
| Amazon DynamoDB | Stores environmental and health data |
| Amazon SNS | Sends notifications and alerts |
| Amazon S3 | Stores files and project data |
| Amazon Cognito | User registration and authentication |
| Amazon EventBridge | Schedules and triggers automated tasks |
| Amazon CloudWatch | Monitors application performance and errors |

## System Workflow

1. ESP32 collects indoor air quality readings through connected sensors.
2. Sensor readings are transmitted to AWS IoT Core.
3. AWS IoT Rules route the incoming data to AWS Lambda.
4. Processed readings are stored in Amazon DynamoDB.
5. Users complete their daily health questionnaire through the web application.
6. Health observations and optional peak flow readings are stored.
7. Machine Learning analyses environmental and health data.
8. Gemini AI generates simple, context-aware recommendations.
9. The dashboard displays air quality readings, health trends and alerts.

## Daily Health Data Collection

The application will use a predefined daily questionnaire to maintain consistent health records.

Example questions include:
- Have you experienced coughing today?
- Have you experienced wheezing?
- Have you experienced shortness of breath?
- Have you experienced chest tightness?
- How would you rate your breathing today?
- Did you experience symptoms during the night?
- Did you use your prescribed inhaler today?
- What is your peak flow reading? (Optional)

This structured approach helps collect consistent health observations that can be analysed alongside environmental data.

## Expected Outcome

A functional cloud-based monitoring platform that combines IoT, AWS Cloud, Machine Learning and Generative AI to help users monitor indoor air quality, track respiratory health and identify potential environmental triggers associated with asthma exacerbations.

## Project Team

| Name | Roll Number |
|---|---|
| Ananya Maroju | 2520080069 |
| Saranya Aluru | 2520080012 |
| D. Sri Varshini | 2520080013 |

## Project Guide

**Dr. D. Divya Priya**  
Assistant Professor  
Department of Computer Science and Information Technology (CS & IT)

## Course Information

**Course:** Cloud Infrastructure and Services (25CS2206E)

**Academic Year:** 2026–2027

## Disclaimer

This project is intended for educational and monitoring purposes. It does not provide medical diagnoses or replace professional medical advice.
