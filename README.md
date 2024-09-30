Sustainable Travel Planner 🌍✈️

This application is built using Pathway's API with Streamlit as the user interface. The goal of this app is to provide personalized travel suggestions that promote sustainability and environmental responsibility, addressing various eco-friendly travel concerns.

Click the LINK to watch the video demo.
  :- https://drive.google.com/file/d/10kVeXu8OkGN9cMNvUBOnwKCHt2DqGPVo/view?usp=drive_link

I have explained two features from start one will end at 1:20 appraox and other at 1:28 approx , in the video both are merged

Moreover, 
i did this Project on linux system as pathway is more compatible on linux
Description 📝
The Sustainable Travel Planner leverages Pathway’s powerful API to provide personalized travel suggestions based on users' unique preferences and eco-conscious travel needs. It combines advanced algorithms with real-time feedback to offer a tailored experience, supporting sustainable tourism.

The Pathway API powers the app by enabling smart, personalized suggestions for various sustainable travel topics, including eco-friendly accommodations, green transportation options, and responsible activities. The real-time data pipeline integration allows the app to continuously learn from user inputs and provide accurate and actionable travel advice.

Built with Streamlit, this app offers a seamless user experience, allowing users to easily navigate the interface, input their current travel plans, and receive helpful sustainable travel suggestions instantly.

Features :-
* Personalized Travel Suggestions: Tailored to each user's specific eco-friendly travel needs.
* User-Friendly Interface: Streamlit-powered for easy navigation and interaction.
* Pathway API Integration: Provides real-time, data-driven suggestions without requiring a separate database.
* Real-Time Feedback: The app learns and adapts to user inputs for improved accuracy.
* Cross-Platform Deployment: Easily deploy on any platform using Docker.



The application provides a webserver with the following endpoints:

Local URL: http://localhost:8502
Network URL: http://10.81.41.63:8502

Travel Query and Suggestion Capabilities
/v1/get_suggestion: Retrieve personalized sustainable travel suggestions based on user input.

/v1/get_feedback: Input real-time feedback to improve travel suggestions.

Prerequisites 📋
Before running the app, make sure you have the following installed:

* Python 3.x
* Git
* Docker
Installation 💻

`git clone https://github.com/arpit246/dsg_pathway_subm-ARP.git`

Change into the project directory:

`cd Sustainable_travel_app_main`

Add your Pathway API key to the .env file:

GEMINI_API_KEY=<YOUR_API_KEY>
HUGGINGFACE_API_KEY=<YOUR API KEY>

Build and run the Docker Image:

`docker-compose up`
Note: Building the image may take 15-20 minutes. ⏳

Access the app in your browser at http://localhost:8502.


To stop the program:

`docker-compose down`
## Future Improvements 🚀
* Add an in-app sustainability assessment tool for a more detailed analysis.
* Advanced analytics to track sustainable travel habits over time.
Made by ARPIT SETH
