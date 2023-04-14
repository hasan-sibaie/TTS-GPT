# TTS-GPT
This code implements a chatbot assistant that can transcribe user audio input, process it using OpenAI's GPT-3 API, and provide both verbal and text responses. The chatbot uses the ElevenLabs library to generate audio responses from the system message generated by GPT-3. The code is implemented using the Gradio library for creating user interfaces, allowing the assistant to be launched as a web application.



Desktop ChatGPT Assistant

This is a desktop chatbot assistant that can listen to your voice input, transcribe it into text, and respond to you both verbally and in text using the OpenAI GPT-3 API.

## Installation

To run the chatbot assistant, you will need to install the necessary dependencies:

1. Clone this repository to your local machine.
2. Navigate to the cloned directory.
3. Create a virtual environment:
    ```
    python -m venv venv
    ```
4. Activate the virtual environment:
    ```
    . venv/bin/activate
    ```
5. Install the required packages:
    ```
    pip install -r requirements.txt
    ```
6. Install FFMPEG

https://www.gyan.dev/ffmpeg/builds/

![image](https://user-images.githubusercontent.com/93472563/232031983-19a90c3a-ca88-4b6b-a776-21db208b88d0.png)


## Usage

Please note that you need to make sure that FFMPEG is installed and configured in the PATH environment for the code to run correctly. Also, make sure to provide the necessary API keys in the code before running it. Once the code is running, use the interface to ask questions by recording audio messages and the chatbot assistant will respond with both audio and text.




## First Run


![image](https://user-images.githubusercontent.com/93472563/232044412-6226b77f-ef5f-4e1c-9dab-3b8557f40e19.png)

## GRADIO UI



![image](https://user-images.githubusercontent.com/93472563/232044488-8e637210-5881-47f3-b843-6316cc160f54.png)
