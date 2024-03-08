# HealthChat 🤖

Welcome to the Disease Detection Chatbot! This Flask application leverages Natural Language Processing (NLP) and Machine Learning to analyze user-provided symptoms and detect potential diseases or medical conditions. Built using the power of Python, Keras, and NLTK, this chatbot aims to provide an initial assessment and guidance for users based on their reported symptoms.

## Features 🚀

- **Symptom Analysis**: Users can input their symptoms in natural language, and the chatbot will analyze the input using NLP techniques.
- **Disease Detection**: Based on the analyzed symptoms, the chatbot utilizes a trained machine learning model to predict potential diseases or medical conditions.
- **Conversational Interface**: The chatbot provides a user-friendly, conversational interface for seamless interaction.
- **Response Generation**: The chatbot generates relevant responses based on the detected disease or condition, offering guidance and suggestions.

## Installation 💻

1. Clone the repository:

```bash
git clone https://github.com/your-username/disease-detection-chatbot.git
```

2. Navigate to the project directory:

```bash
cd disease-detection-chatbot
```

3. Install the required dependencies:

```bash
pip install -r requirements.txt
```

4. Download and extract the necessary data files (e.g., `intents.json`, `words.pkl`, `classes.pkl`, `archealth.h5`) and place them in the project directory.

5. Run the Flask application:

```bash
python app.py
```

The application will be accessible at [`http://localhost:5000`](http://localhost:5000).

## Usage 🧑‍💻

1. Open the application in your web browser by visiting [`http://localhost:5000`](http://localhost:5000).
2. Enter your symptoms in the chat input field and send the message.
3. The chatbot will analyze your input and provide a potential disease or medical condition based on the detected symptoms.
4. Follow the chatbot's guidance and suggestions for further actions or consultations.

## Contributing 🤝

Contributions are welcome! If you have any ideas 💡, bug reports 🐛, or feature requests ✨, please open an issue or submit a pull request.

## License 📜

This project is licensed under the [MIT License](LICENSE).

## Acknowledgments 🙏

- [Flask](https://flask.palletsprojects.com/) - The Python web framework used for this project.
- [Keras](https://keras.io/) - The deep learning library used for building and training the disease detection model.
- [NLTK](https://www.nltk.org/) - The Natural Language Toolkit used for text processing and analysis.

Explore the Disease Detection Chatbot and experience the power of NLP and Machine Learning in healthcare! Stay healthy! 💪🏥