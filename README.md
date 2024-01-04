# MultiPDF Chat App

> You can find the tutorial for this project on [YouTube](https://youtu.be/dXxQ0LR-3Hg).

## Introduction
------------
The MultiPDF Chat App is a Python application that allows you to chat with multiple PDF documents. You can ask questions about the PDFs using natural language, and the application will provide relevant responses based on the content of the documents. This app utilizes a language model to generate accurate answers to your queries. Please note that the app will only respond to questions related to the loaded PDFs.

## How It Works
------------
![PDF-LangChain](https://github.com/SunilKumar-ugra/MultiPDF-Chat-App/assets/45965583/652bd3d6-a678-40f3-9288-dfb253c3d1b4)






The application follows these steps to provide responses to your questions:

1. PDF Loading: The app reads multiple PDF documents and extracts their text content.

2. Text Chunking: The extracted text is divided into smaller chunks that can be processed effectively.

3. Language Model: The application utilizes a language model to generate vector representations (embeddings) of the text chunks.

4. Similarity Matching: When you ask a question, the app compares it with the text chunks and identifies the most semantically similar ones.

5. Response Generation: The selected chunks are passed to the language model, which generates a response based on the relevant content of the PDFs.

## Dependencies and Installation
----------------------------
To install the MultiPDF Chat App, please follow these steps:

1. Clone the repository to your local machine.

2. Install the required dependencies by running the following command:
   ```
   pip install -r requirements.txt
   ```

3. Obtain an API key from OpenAI and add it to the `.env` file in the project directory.
```commandline
OPENAI_API_KEY=your_secrit_api_key
```

## Usage
-----
To use the MultiPDF Chat App, follow these steps:

1. Ensure that you have installed the required dependencies and added the OpenAI API key to the `.env` file.

2. Run the `main.py` file using the Streamlit CLI. Execute the following command:
   ```
   streamlit run app.py
   ```

3. The application will launch in your default web browser, displaying the user interface.

4. Load multiple PDF documents into the app by following the provided instructions.

5. Ask questions in natural language about the loaded PDFs using the chat interface.

# How to run?
### STEPS:

Clone the repository

```bash
https://github.com/SunilKumar-ugra/LLAMA2-Medical-Chatbot.git
```
### STEP 01- Create a conda environment after opening the repository

```bash
conda create -n chat_multi_pdf python=3.9 -y
```

```bash
conda activate chat_multi_pdf 
```


### STEP 02- Install the requirements
```bash
pip install -r requirements.txt
```
### STEP 03-  Run the command    
```bash 
# Finally run the following command
streamlit run app.py
```

Now,
```bash
http://localhost:8501 #Open this url in the browser
```
## Demo
https://github.com/SunilKumar-ugra/MultiPDF-Chat-App/assets/45965583/db7c25d0-c484-41bc-9776-839d46d802ea
## License
-------
The MultiPDF Chat App is released under the [MIT License](https://opensource.org/licenses/MIT).
