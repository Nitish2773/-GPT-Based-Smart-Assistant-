
---

# GPT-Based Smart Assistant

![License](https://img.shields.io/github/license/Nitish2773/-GPT-Based-Smart-Assistant-)
![Python](https://img.shields.io/badge/Python-3.x-blue)

The primary objective of this project is to develop an interactive voice-controlled assistant leveraging OpenAI's GPT model to understand and respond to user queries in natural language. This assistant aims to enhance user interaction by providing a seamless and intuitive experience through speech recognition and text-to-speech conversion.

The project involves capturing audio commands from users, converting the speech to text, processing the text using the ChatGPT API, and converting the generated responses back into speech. The system is designed to handle natural language queries and provide meaningful responses, thereby improving the user experience.

## Features
- **Conversational AI**: Uses OpenAI's GPT-4 model for intelligent and contextual responses.
- **Speech Recognition**: Converts voice commands to text using the SpeechRecognition library.
- **Text-to-Speech**: Converts responses to voice output via pyttsx3.
- **Web Integration**: Opens websites like YouTube and Google based on voice commands.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/yourrepository.git
   cd yourrepository
   ```

2. Install dependencies:
   ```bash
   pip install openai SpeechRecognition pyttsx3
   ```

3. Add your OpenAI API key:
   - Place your API key in a file named `apikey.py`:
     ```python
     api_data = "your-api-key-here"
     ```

4. Run the assistant:
   ```bash
   python assistant.py
   ```

## Usage

- **Initiate Conversation**: Run the script to start the assistant.
- **Commands**:
  - Ask any question.
  - Use commands like "Open YouTube" or "Open Google" for web-related tasks.
  - Say "bye" to exit the assistant.

## Example Interaction

```
User: "Tell me about AI in simple terms."
Assistant: "AI, or Artificial Intelligence, is a branch of computer science focused on creating systems that can perform tasks requiring human intelligence, like understanding language or making decisions."
```

---
