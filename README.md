
# Assistant-Chat-GPT-voice

Assistant-GPT voice serves as a virtual assistant. Allows users to interact that can assist with a variety of tasks, such as answering questions, providing recommendations, or generating text.



## Installation
To use this voice assistant, you will need to have the following libraries installed:
- OpenAI
- Pyttsx3
- SpeechRecognition


You can install these libraries by running the following command:



```bash
  pip install openai pyttsx3 SpeechRecognition
```


```bash
  pip install openai

```


```bash
  pip install pyaudio

```


```bash
  npm run start
```

You will also need to set your OpenAI API key before running the program. You can do this by replacing the empty string in the openai.api_key variable with your own API key.
## Usage/Examples

To start the voice assistant, run the following command in your terminal:



```bash
  python main.py

```
Once the program is running, you can activate the assistant by saying "hash" into the microphone. This will prompt the program to record your question. Once you have finished speaking, the program will transcribe your audio to text, generate a response using GPT-3, and read the response aloud using text-to-speech.
## Contributing

If you would like to contribute to this project, please fork the repository and submit a pull request with your changes.


## License

[MIT](https://choosealicense.com/licenses/mit/)


## Acknowledgements

- OpenAI for providing the GPT-3 model.
- The Python community for creating the libraries used in this project.
