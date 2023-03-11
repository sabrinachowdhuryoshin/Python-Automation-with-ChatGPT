# Python Automation of ChatGPT

Python Automation of ChatGPT contains a Python script that allows the user to automate interactions with OpenAI's ChatGPT API. This script will help the user connect with the Vinci text model of openai. The user can send whatever prompt programmatically and will get a response from the ChatGPT API. This script is useful for automating the process of generating responses to text prompts, such as answering customer support inquiries or generating personalized responses to messages

## Prerequisites

Before using this script, you will need to have the following:

- Python 3.6 or higher installed on your machine
- An OpenAI API key
- The `requests` and `openai` Python packages installed
  
## Getting Started

1. Clone the repository to your local machine.
2. Configure the `OPENAI_API_KEY`.
3. Open the `python-chatgpt.py` file and update the prompt variable with the text you want to generate a response for.
4. Run the `python-chatgpt.py` script.
   
## Configuration

- Execute the following instruction in powershell to export the `OPENAI_API_KEY`.

- `$env:OPENAI_API_KEY="OPENAI_API_KEY`

- `OPENAI_API_KEY` is a single variable, which you will need to generate in your OpenAI account.

## Usage

- To use the script, open the `python-chatgpt.py` file and update the `prompt` variable and the file name with the text you want to generate a response for. The response from the OpenAI server will be saved in the python file name you provided.

- Then, run the script using the following command:

`python python-chatgpt.py "prompt" "file_name"`

The script will send a request to the OpenAI API and generate a response based on the `prompt` variable. The response will be printed to the console.

## License

This project is licensed under the MIT License. See the LICENSE file for details.

## Contributing

Contributions to this project are welcome. If you find a bug or have a feature request, please open an issue. If you would like to contribute code, please fork the repository and submit a pull request.