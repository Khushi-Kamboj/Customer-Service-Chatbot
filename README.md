## Preview
![banner](https://github.com/user-attachments/assets/f2d858e2-ddba-4df6-a2f7-4de284a9996b)


## Features
- AI-powered chatbot for food ordering
- Uses Google Dialogflow for intent recognition
- Supports multiple food items for ordering

## Technologies Used
- **Frontend:** React.js, HTML, CSS
- **Backend:** Node.js, Firebase
- **Chatbot Integration:** Dialogflow API

# Customer-Service-Chatbot
AI-powered chatbot integrated into a food delivery website to assist customers in placing their orders effortlessly. Built using Dialogflow, the chatbot provides a seamless conversational interface that allows users to interact naturally and order food items from the menu.
## Directory structure
===================
backend: Contains Python FastAPI backend code
db: contains the dump of the database. you need to import this into your MySQL db by using MySQL workbench tool
dialogflow_assets: this has training phrases etc. for our intents
frontend: website code

## Install these modules
======================

pip install mysql-connector
pip install "fastapi[all]"

OR just run pip install -r backend/requirements.txt to install both in one shot

## To start fastapi backend server
================================
1. Go to backend directory in your command prompt
2. Run this command: uvicorn main:app --reload

ngrok for https tunneling
================================
1. To install ngrok, go to https://ngrok.com/download and install ngrok version that is suitable for your OS
2. Extract the zip file and place ngrok.exe in a folder.
3. Open windows command prompt, go to that folder and run this command: ngrok http 80000

NOTE: ngrok can timeout. you need to restart the session if you see session expired message.
