# PDF ChatBot

## Now you can talk with your PDF files using OPEN AI API + Streamlit + Python + langchain + pinecone

Welcome to the PDF ChatBot! This project allows you to talk with your PDF files using a combination of OPEN AI API, Streamlit, Python, Langchain, and Pinecone.

## Getting Started

To get started, clone this repository to your local machine. 

Next, create the following Streamlit variables inside a `.streamlit` folder in the root directory of your project, and add them to the `secrets.toml` file:

### OPENAI_API_KEY = 'sk-'
### PINECONE_API_KEY = ''
### PINECONE_API_ENV = ''


You'll need to replace the values of these variables with your own Open AI API key, Pinecone API key environment, and index (inside main and upload file).

Make sure to install all of the required packages listed in the `requirements.txt` file.

## Running the App

To run the Streamlit app, simply run the following command in your terminal:

### streamlit run app.py


Once the app is running, you can upload your PDF files and start chatting with them!

Thank you for using the PDF ChatBot. If you have any questions or issues, please don't hesitate to contact us.
