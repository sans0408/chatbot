# NLP Chatbot
This project demonstrates the creation of a chatbot using various transformer models from huggingface in Python. The project is implemented in a Jupyter notebook, allowing for interactive code execution and detailed explanations.

## Contents

- [Contents](#contents)
- [Requirements](#requirements)
- [Setup](#setup)
- [Usage](#usage)
- [Project Structure](#project-structure)

## Requirements

To run the notebook, you need the following libraries installed:

- huggingface_hub
- transformers
- langchain
- chainlit
  
You can install the required libraries using pip:

```bash
pip install huggingface_hub transformers langchain chainlit
```

Set up the Hugging Face API token
os.environ['HUGGINGFACEHUB_API_TOKEN'] = '[Replace with your token](https://huggingface.co/settings/tokens)'

## Setup

**Clone the Repository:**

   ```bash
   git clone <repository_url>
   cd <repository_directory>
   ```

**Edit the code to set up your API token**

   ```bash
   os.environ['HUGGINGFACEHUB_API_TOKEN'] = 'your_api_token'
   ```

## Usage

1. **Open the Jupyter Notebook:**

   Open ```nlp_chatbot.ipynb``` using jupyter notebook or Google Colaboratory.

2. **Run the Notebook:**

   Follow the instructions in the notebook to run each cell. The notebook consists of multiple use cases of an NLP Chatbot, consolidated in a menu-driven program.

## Project Structure

- **chatbot.ipynb:** The main Jupyter notebook containing the project code and explanations.
- **README.md:** Contains the usage instructions for this project.
