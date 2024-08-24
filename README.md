# **CommandCaster**

CommandCaster is a versatile, voice-activated assistant built using Python. It leverages speech recognition, text-to-speech conversion, and AI-driven responses to simplify your interaction with various digital services. Whether you're fetching the latest news, playing music, or just exploring the web, CommandCaster has got you covered—all through simple voice commands.

## **Features**

- **Voice Recognition**: Utilizes `speech_recognition` to understand and execute spoken commands.
- **Text-to-Speech**: Converts text to natural-sounding speech using `pyttsx3`, providing audible feedback for your commands.
- **Web Integration**: Opens websites and plays music directly through voice commands, with support for platforms like Google, Facebook, LinkedIn, YouTube, and more.
- **News Fetching**: Retrieves the latest headlines from a news API and reads them aloud.
- **AI-Powered Responses**: Integrates with AI models to provide detailed and helpful responses to general queries.
- **Customizable Wake Word**: Trigger the assistant using a custom wake word, such as "Apollo".

## **Installation**

1. **Clone the Repository**:

   ```bash
   git clone https://github.com/your-username/command-caster.git
   cd command-caster
   ```
2. **Set Up the Virtual Environment**:
   ```bash
   python -m venv .venv
   source .venv/bin/activate
   # On Windows use: .venv\Scripts\activate
   ```
3. **Install Dependencies**:
   ```bash
   pip install -r requirements.txt
   ```
4. **Configure API Keys**:
   
   Create a .env file in the root directory.
   Add your API keys like this:
   ```
   NEWS_API_KEY=your_news_api_key
   GEMINI_API_KEY=your_openai_api_key
   ```


## **Project Structure**

- `main.py`: The core script to run CommandCaster.
- `client.py`: Handles AI-based responses.
- `news.py`: Fetches and processes the latest news headlines.
- `clean.py`: Cleans and formats the AI-generated text.
- `musicLibrary.py`: Contains a mapping of songs to their URLs.
- `requirements.txt` : This file contains the exact versions of the packages I have used.

## **Usage**

1. **Run the Assistant**
   
   ```bash
   python main.py
   ```
2. **Interacting with CommandCaster**
   - Say the wake word "Apollo" to activate the assistant.
   - Give commands like : "Open Google", "Play [song name]", "Fetch the latest news", "What is React JS?"
3. **Customisation**
   - Modify the wake word or add new functionalities by editing the main.py file and associated modules.


## **Contributing**

Contributions are welcome! Please feel free to submit a Pull Request or open an Issue to improve the project.
