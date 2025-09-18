# AgroLink
An AI-Powered comprehensive livestock management and disease detection platform

## Overview
AgroLink is a multi-platform application designed to revolutionize livestock care through AI-powered disease detection, veterinary services management, and comprehensive farm management tools.

## Features
- 🤖 **AI-Powered Disease Detection**: Advanced symptom checking and diagnosis
- 💉 **Vaccine Management**: Track and schedule vaccinations
- 📅 **Appointment Management**: Book and manage veterinary appointments
- 💬 **AI Chatbot**: 24/7 livestock care assistance
- 📊 **Market Analysis**: Real-time market insights and analytics
- 🏪 **Animal Marketplace**: Buy and sell livestock
- 📱 **Multi-Platform**: Mobile app, web backend, and desktop support
- 🌐 **Multi-Language**: Internationalization support

## Project Structure
- **mobile/**: React Native mobile application
- **sprBack/**: Spring Boot Java backend
- **backendJavaSimple/**: Simplified Java backend
- **tests/**: Playwright E2E test suites

## Technologies Used
- **Frontend**: React Native, Expo
- **Backend**: Spring Boot
- **Database**: MongoDB, MySQL
- **AI/ML**: Disease detection algorithms
- **Testing**: Jest, Playwright
- **DevOps**: Docker, GitHub Actions

## Quick Start
1. Clone the repository
2. Install dependencies: `npm install` on the mobile directory 
3. Start the backend: `cd sprBack && mvn clean compile && mvn spring-boot:run`
4. Start the mobile app: `cd mobile && npm start`

## CI/CD Pipeline
This project uses GitHub Actions for automated Docker builds and deployment to Docker Hub.
