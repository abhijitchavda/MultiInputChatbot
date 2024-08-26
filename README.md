# MultiInputChatbot: The All-in-One Multilingual Assistant

A multilingual chatbot that seamlessly interacts with files, text, and audio inputs. Users can engage in conversations, ask questions, and extract detailed information. Built with Ollama for local LLMs, Google Speech Recognition for audio processing, Langchain for creating chains, and Gradio for a user-friendly interface.

## Features

- **Multimodal Input**: Accepts files, text, and audio inputs for diverse interaction possibilities.
- **Multilingual Support**: Capable of understanding and responding in multiple languages.
- **Dynamic Conversations**: Engages in meaningful dialogues, answering questions, summarizing content, and providing detailed analyses.
- **Real-time Audio Processing**: Converts speech to text using Google Speech Recognition for on-the-fly audio interactions.
- **Local LLM Processing**: Runs large language models locally using Ollama, ensuring privacy and speed.
- **LLM Conversational memory**: Added support for storing conversation history for supporting more natural conversation.
- **User-friendly UI**: Built with Gradio, providing an intuitive interface with user friendly elements.

## Technology Stack

- **[Ollama](https://ollama.com/)**: Used for running local LLMs, particularly the "mistral:instruct" model.
- **[SpeechRecognition](https://pypi.org/project/SpeechRecognition/)**: Google’s speech-to-text library for processing audio inputs.
- **[Langchain](https://langchain.com/)**: Creates chains for integrating different components of the chatbot.
- **[Gradio](https://gradio.app/)**: Provides the user interface, enabling easy interaction with the chatbot.

## Prerequisites

- Python 3.8 or later
- Ollama installed and running on `localhost` at port `11434` with the "mistral:instruct" model downloaded.
- Required Python libraries:
  - `psutil`
  - `speech_recognition`
  - `gradio`
  - `langchain-experimental`

Install the dependencies using:

```bash
pip install psutil speechrecognition gradio langchain
```

## Usage

1. **Run Ollama**: Ensure Ollama is running locally with the "mistral:instruct" model.
2. **Launch the Chatbot**: Run the jupyter notebook to start the Gradio interface.
3. **Interact**: Use the Gradio interface to upload files, input text, or record audio. Atom will process the inputs and provide detailed responses.

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request or open an Issue for any improvements or suggestions.

## UI

![MultiInputChatbot](https://github.com/abhijitchavda/MultiInputChatbot/blob/main/UI.jpg?raw=true)

