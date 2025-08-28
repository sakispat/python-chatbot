# Python Chatbot Project

A simple conversational chatbot built in Python using libraries like ChatterBot or NLTK. Developed in Jupyter Notebook and VS Code.

## Features
- Basic chat responses using pre-trained corpora (ChatterBot) or rule-based patterns (NLTK).
- Supports customization for more advanced interactions.
- Error handling and troubleshooting examples included.

## Requirements
- Python 3.8+
- Libraries: `chatterbot`, `chatterbot-corpus`, `nltk`
- Tools: Jupyter Notebook, VS Code

## Installation
1. Clone the repo:
```bash
git clone https://github.com/sakispat/python_chatbot.git
cd python-chatbot
```

2. Create and activate virtual environment:
```bash
python -m venv venv
source venv/bin/activate     # on macOS/Linux
venv\Scripts\activate        # Windows
```

3. Update and Install dependencies:
```bash
python -m pip install --upgrade pip
pip install -r requirements.txt
```

## Usage
- Open in Jupyter: Run `jupyter notebook` and load `1 - Chatterbot.ipynb` or `2 - NLTK Chatbot.ipynb`.

Example interaction:
```txt
You: Hello
Bot: Hi there!
```

## Troubleshooting
- If ChatterBot fails with spaCy errors, download the model: `python -m spacy download en_core_web_sm` or `!python spacy download en` in `jupyter notebook` and patch as needed.
- For NLTK, download data: `nltk.download('punkt')`.
