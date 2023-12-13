# Azure Sample Chat

An easy Python example to chat with Azure OpenAI Service, based on the Code section from the Chat playground on Azure OpenAI Service.

## Setup and prerequisites

Create a Python virtual environment (`virtualenv`) and install the requirements:

```bash
python3 -m venv .venv
source .venv/bin/activate
```

Install the requirements:

```bash
pip install -r requirements.txt
```

Review the `requirements.txt` file to see the dependencies.

### Export the environment variables

```bash
export OPENAI_API_BASE="https://RESOURCE_NAME.openai.azure.com/"
export OPENAI_API_KEY="API_KEY"
```

Replace both `RESOURCE_NAME` and `API_KEY` with the values from the Azure OpenAI Service resource.

## Run the sample

```bash
python chat.py
```


