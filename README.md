# Chatbot with LLaMA Model
This project demonstrates a simple chatbot interface built using Streamlit and a local instance of the LLaMA model. The chatbot allows users to ask questions and receive responses from the LLaMA model

## Prerequisites

Make sure you have the following installed:
- Git
- Python (>= 3.7)
- pip (Python package installer)

You can check if Git and Python are installed using these commands:

```bash
git --version
python --version
pip --version
```

## Install Dependencies

Next, you need to install the required Python dependencies. It is recommended to create a virtual environment for this.

1. Create a virtual environment:

    ```bash
    python -m venv env  # Create virtual environment
    ```

2. Activate the virtual environment (Linux/Mac):

    ```bash
    source env/bin/activate
    ```

3. Install the required packages listed in the `requirements.txt` file:

    ```bash
    pip install -r requirements.txt
    ```

## Ollama and Llama 3.1
We use the Ollama application and the Llama 3.1 model. Ensure you have the Ollama application installed and configured.

1. Install Ollama application as per the [Ollama documentation](https://ollama.com/docs).
2. Use the Llama 3.1 model for summarization tasks.

#### Linux
```bash
sudo snap install curl
sudo apt install curl
curl -fsSL https://ollama.com/install.sh | sh
```

### Quickstart
To run and chat with Llama 3.1:
```bash
ollama run llama3.1
```

### Pull a model
```bash
ollama pull llama3.1
```

### List models on your computer
```bash
ollama list
```

### Show model information
```bash
ollama show llama3.1
```
### Stop the Ollama:
```bash
ollama stop llama3.1
```
### Remove a model
```bash
ollama rm llama3.1
```

## Run the Streamlit app:
To run the ChatBot, execute the following command:
```bash
streamlit run app.py
```
## Example:
User: What is the capital of France?
Assistant: The capital of France is Paris.

User: Who wrote the play Hamlet?
Assistant: The play Hamlet was written by William Shakespeare.



