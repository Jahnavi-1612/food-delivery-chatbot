# Food Delivery Chatbot – NLP-powered Conversational AI

## Project Description
This project implements an **end-to-end chatbot for food ordering**, built using **Google Dialogflow** for natural language understanding and **Python (FastAPI/Flask)** for backend fulfillment. The chatbot can handle user interactions such as viewing menus, placing orders, updating or canceling orders, and tracking delivery status in real time.

The system demonstrates practical applications of **Natural Language Processing (NLP), API development, database management**, and **cloud deployment**, making it ideal for customer support automation and e-commerce solutions.

---

## Features
✔ Intent recognition and slot filling using Dialogflow  
✔ Dynamic responses through API integration with backend services  
✔ Order management with database storage (SQL/NoSQL)  
✔ Secure communication using HTTPS for webhook integration  
✔ Easy deployment using tools like ngrok or cloud platforms  



Directory structure
--------
backend: Contains Python FastAPI backend code
db: contains the dump of the database. you need to import this into your MySQL db by using MySQL workbench tool
dialogflow_assets: this has training phrases etc. for our intents
frontend: website code

Install these modules
--------

pip install mysql-connector
pip install "fastapi[all]"

OR just run pip install -r backend/requirements.txt to install both in one shot

To start fastapi backend server
-------------------------------
1. Go to backend directory in your command prompt
2. Run this command: uvicorn main:app --reload

ngrok for https tunneling
----------
1. To install ngrok, go to https://ngrok.com/download and install ngrok version that is suitable for your OS
2. Extract the zip file and place ngrok.exe in a folder.
3. Open windows command prompt, go to that folder and run this command: ngrok http 80000

NOTE: ngrok can timeout. you need to restart the session if you see session expired message.
