# NLP Task Wizard

NLP Task Wizard is a Flask web application that allows users to perform various natural language processing (NLP) tasks using pre-trained models from the Hugging Face Transformers library. Users can input text and select a specific NLP task from a dropdown menu, and the app will provide the corresponding analysis or transformation based on the selected task.

## Features

- **Sentiment Analysis:** Analyze the sentiment (positive, negative, or neutral) of the input text.
- **Text Generation:** Generate new text based on the input text.
- **Translation:** Translate the input text from English to Hindi.
- **Summarization:** Summarize the input text.
- **Named Entity Recognition (NER):** Identify and classify named entities mentioned in the input text, such as persons, organizations, locations, etc.

## Usage

1. Clone the repository to your local machine:

    ```
    git clone https://github.com/ASHWIN492/nlp-task-wizard.git
    ```

2. Navigate to the project directory:

    ```
    cd nlp-task-wizard
    ```

3. Install the required dependencies:

    ```
    pip install -r requirements.txt
    ```

4. Run the Flask app:

    ```
    python app.py
    ```

5. Open a web browser and go to `http://localhost:5000` to access the NLP Task Wizard.

6. Enter your text in the input box, choose a task from the dropdown menu, and click the "Submit" button to see the analysis or transformation result.

## Dependencies

- Flask: Web framework for building the application.
- Hugging Face Transformers: Library for accessing pre-trained NLP models.

## Credits

This application utilizes the Hugging Face Transformers library, which provides easy access to state-of-the-art NLP models. Visit the [Hugging Face website](https://huggingface.co/) for more information about the library and its contributors.
