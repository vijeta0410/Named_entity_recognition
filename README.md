# Name Entity Recognition (NER) App

This is a simple web application built using Streamlit and spaCy to perform Named Entity Recognition (NER) and Word Tokenization. The app allows users to enter text and get it tokenized or visualize the named entities present in the text.

## Features

- **Word Tokenization**: Tokenizes the input text into individual words.

- **Named Entity Recognition (NER)**: Identifies and highlights named entities such as people, organizations, and locations in the input text.

## Tech Stack

- **Streamlit**: A fast and beautiful way to build custom web apps in Python.

- **spaCy**: A popular library for Natural Language Processing (NLP) in Python.

- **spacy-streamlit**: A Streamlit component to visualize spaCy's NLP models directly in a web app.

## Installation

Follow the steps below to set up and run the project locally.

1\. Clone the repository:

    ```
    git clone https://github.com/your-username/ner-app.git
    cd ner-app
    ```

2\. Create a virtual environment (optional but recommended):

    ```
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```

3\. Install the required dependencies:

    ```
    pip install streamlit spacy spacy-streamlit
    ```

4\. Download the spaCy language model:

    ```
    python -m spacy download en_core_web_sm
    ```

## Running the App

Run the app with the following command:

```
streamlit run app.py
```
The app will open in your browser. You can switch between the Word Tokenization and NER features using the sidebar menu.

App Features
------------

### 1\. Home (Word Tokenization)

-   Allows you to input text.
-   Upon clicking the **Tokenize** button, the app will display the tokenized words in the text.

### 2\. NER (Named Entity Recognition)

-   Allows you to input text.
-   Automatically identifies and highlights named entities such as people, locations, organizations, etc.


Contributing
------------

Feel free to fork the project, create pull requests, or submit issues if you find any bugs or want to improve the app.

Acknowledgements
----------------

-   [Streamlit](https://streamlit.io/)
-   [spaCy](https://spacy.io/)
-   [spaCy Streamlit](https://github.com/explosion/spacy-streamlit)
### Notes:

- Be sure to update the repository URL (`https://github.com/vijeta0410/Named_entity_recognition.git`) and any other placeholders to match your project.

- Include actual screenshots of your app in the `screenshots/` folder, and link them in the `README.md` file if you'd like to display images.
