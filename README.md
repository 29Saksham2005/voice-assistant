# voice-assistant

#Overview
Voice Assistant is a Python-based voice-controlled assistant designed to help users with various tasks using natural language commands. The assistant can provide current time and date, search Wikipedia, manage tasks, fetch news, get weather updates, tell jokes, set alarms, and more. It leverages popular libraries such as pyttsx3 for text-to-speech, speech_recognition for speech-to-text, and integrates with external APIs for extended functionalities.

#Features
Current Time: Provides the current time.
Current Date: Announces today's date.
Wikipedia Search: Searches Wikipedia and reads out summaries.
Web Search: Opens Google Chrome and performs a search.
News Updates: Fetches the latest news headlines using NewsAPI.

Joke Teller: Tells a random joke.
Task Manager: Allows users to add, view, and clear tasks.
Alarm Setting: Sets an alarm for a specified time.
Help Command: Lists all available commands and their descriptions.
Requirements
Python 3.6 or higher
pyttsx3
speech_recognition
wikipedia
webbrowser
requests
(Optional) APIs for news 
#Installation
Clone the repository:

bash
Copy code
git clone https://github.com/29Saksham2005/voice-assistant.git
Navigate to the project directory:

bash
Copy code
cd voice-assistant
Install the required Python packages:

bash
Copy code
pip install pyttsx3 SpeechRecognition wikipedia-api requests
Obtain API keys for news and weather services:

NewsAPI
OpenWeatherMap
Update the fetch_news() methods with your API keys in voice_assistant.py.

Usage
Run the assistant:

bash
Copy code
python voice_assistant.py
Interact with the assistant using voice commands. Here are some examples:

"What's the time?"
"Tell me a joke."
"What's the weather in London?"
"Search Wikipedia for Python programming."
"Add task: Buy groceries."
Use the "help" command to get a list of available commands and their descriptions.

#Configuration
Chrome Path: Ensure the path to the Chrome executable is correct in the open_chrome() method. Adjust it based on your system configuration.
Contributing
Contributions are welcome! If you'd like to contribute to this project, please fork the repository and submit a pull request with your changes.

#License
This project is licensed under the MIT License - see the LICENSE file for details.

#Acknowledgements
pyttsx3, speech_recognition, and wikipedia libraries for providing essential functionalities.
NewsAPI and OpenWeatherMap for their APIs.
The official Joke API for random jokes.
Feel free to modify the content as needed to better fit your project specifics and personal style.
