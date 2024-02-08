# Translator Service

This is a simple Flask application that utilizes the Azure Translator service powered by AI to translate text from one language to another. Users can input text and select a target language, and the application will return the translated text using advanced artificial intelligence capabilities provided by Azure.

## Installation

1. Clone the repository to your local machine:


2. Navigate to the project directory:


3. Install the required Python packages using pip:

pip3 install requirement.txt


4. Obtain your Azure Translator API key and endpoint and store them in a `.env` file in the root directory of the project:

KEY=your-azure-api-key

ENDPOINT=your-azure-api-endpoint

LOCATION=your-azure-region


5. Run the Flask application:

flask run

6. Open your web browser and go to [http://localhost:5000/](http://localhost:5000/) to access the application.

## Usage

1. Enter the text you wish to translate into the input box.
2. Select the target language from the dropdown menu.
3. Click the "Translate!" button.
4. View the translated text on the results page.

## Contributing

Contributions to this project are welcome. You can contribute by reporting issues, suggesting features, or submitting pull requests.

## Thanks

Special thanks to [Microsoft Learn] for providing valuable resources and documentation on Azure services.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
