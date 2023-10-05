# Chat with pdf

Repository on exploring the llms using Local pdf files to chat with them

## Introduction

---

The ChatWithPdf is a python applitcation inm streamlit that allow you to chat with multiple PDF documents.
You can as questions abouit the PDF The application with provide relevant info based on you content in the documents.
This app uses Language model to generate answers to your Quiries.

**Please Note that the app will only respon to questions related to loaded pdf**

## Dependencies and installation

---

To install ChatWithPdf pelase follow these steps:

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

---

To use the MultiPDF Chat App, follow these steps:

1. Ensure that you have installed the required dependencies and added the OpenAI API key to the `.env` file.

2. Run the `main.py` file using the Streamlit CLI. Execute the following command:
   ```
   streamlit run app.py
   ```
