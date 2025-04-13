Healthcare Chatbot
Overview
This Healthcare Chatbot is designed to assist users in identifying potential illnesses based on symptoms they provide. The chatbot uses machine learning techniques, including Decision Trees and Support Vector Machines (SVM), to predict diseases. It also provides recommendations on whether the user should seek medical consultation.

Features
Utilizes a Decision Tree Classifier and SVM for disease prediction.
Uses NLP techniques to match user input with symptoms.
Provides severity analysis based on the symptoms and duration.
Offers disease descriptions and precautions.
Implements text-to-speech (TTS) functionality to improve user interaction.

Installation
Prerequisites
Ensure you have the following installed:
Python 3.x
Required Python packages (install using pip install -r requirements.txt)

Clone the Repository
 git clone https://github.com/yourusername/healthcare-chatbot.git
 cd healthcare-chatbot
 
Install Dependencies
pip install -r requirements.txt

Usage
Run the chatbot using:
python chatbot.py
Follow the prompts to enter symptoms.
The bot will analyze the symptoms and provide potential diagnoses, descriptions, and precautionary measures.


File Structure
healthcare-chatbot/
├── Data/
│   ├── Training.csv
│   ├── Testing.csv
├── MasterData/
│   ├── symptom_Description.csv
│   ├── symptom_severity.csv
│   ├── symptom_precaution.csv
├── chatbot.py
├── requirements.txt
├── README.md

Technologies Used
Python for scripting
Scikit-learn for machine learning
Pandas & NumPy for data manipulation
pyttsx3 for text-to-speech
Regular Expressions (re) for pattern matching
Contribution
Feel free to fork this repository and submit pull requests. For major changes, please open an issue first to discuss what you would like to change.
