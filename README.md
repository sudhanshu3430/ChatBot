
## Table of Contents

- Description

- Features

- Installation

- Dependencies

- Screenshots

- Download APK

- Caution
## DigiHelper(Chatbot App)

This Android project is a chatbot application built using Firebase and the Brainshop API. It provides users with the ability to engage in real-time conversations with an AI-powered chatbot. The app also supports email authentication to ensure secure access to the chatbot functionality.


## Features

The Android Chatbot App includes the following features:

- Real-time Conversations with AI: Users can have dynamic conversations with an AI-powered chatbot. The chatbot utilizes natural language processing techniques to understand user queries and provide relevant responses.

- Email Authentication: Users can sign up and log in using their email addresses and passwords. Firebase Authentication is used to handle user authentication and account management securely.


## Installation

To run the Android Chatbot App project, follow these steps:

Clone the project repository from GitHub.

Open the project in Android Studio.

Configure the Firebase project:

- Create a new Firebase project in the Firebase console.
- Enable the Firebase Authentication service.
- Add the generated google-services.json file to the project's app folder.
- Obtain the Brainshop API credentials:

Sign up for an account on the Brainshop website (https://brainshop.ai/).
Obtain the API key required for accessing the chatbot service.

Configure the app to use the Brainshop API:

- Open the ChatbotApiClient.java file in the project.
- Replace the API_KEY constant with your Brainshop API key.
- Build and run the app on an Android emulator or physical device.

## Dependencies

The Android Chatbot App relies on the following dependencies:

- Firebase Authentication: com.google.firebase:firebase-auth

- Retrofit: com.squareup.retrofit2:retrofit

- OkHttp: com.squareup.okhttp3:okhttp

- Gson: com.google.code.gson:gson

Make sure to include these dependencies in your project's build.gradle file.
    
## Screenshots


![Screenshot 2023-07-13 190150](https://github.com/sudhanshu3430/ChatBot/assets/127764778/5b0d66b9-8829-4428-be78-1284ba938aaf)



![Screenshot 2023-07-13 190235](https://github.com/sudhanshu3430/ChatBot/assets/127764778/57ad312e-8940-429f-90ee-6feb1b5ef488)


## Download APK

Drive Links for Apks - https://drive.google.com/drive/folders/1gPIzCNaZfhxghgxNU72xMLK_OdEs57eX?usp=sharing
## Caution

This source code and APK file may not be compatible with newer versions of Android Studio and Android.
