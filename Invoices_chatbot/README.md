# Streamlit Chatbot about Your invoices

This project is a Simple Streamlit chatbot, that talks with you and answer your questions about the invoices you provide.
## Video Demo

https://github.com/ElyousfiMohamed/LangChain_applications/assets/73071155/6816598d-f673-4a25-ae91-d2e605e5ad5f

## Installation

To run this project locally, follow these steps:

1. Clone the repository:

   ```bash
   git clone https://github.com/ElyousfiMohamed/LangChain_applications.git
   ```
   
2. Install the requirements:

   ```bash
    pip install -r requirements.txt
    ```
   
3. Run the app:

   ```bash
   streamlit run .\Invoices_chatbot\invoice_app.py
   ```
   
Using docker:

1. Pull the image:

   ```bash
   docker pull elyousfi5/invoices_chatbot
   ```
   
2. Run the container (first time might take time):

   ```bash
   docker run -p 8501:8501 elyousfi5/invoices_chatbot
    ```
   
3. Open your browser and go to http://localhost:8501
   
   
## Libraries

- [Streamlit](https://github.com/streamlit/streamlit) : Streamlit lets you turn data scripts into shareable web apps in minutes.
- [Langchain](https://github.com/hwchase17/langchain) : Building applications with LLMs through composability.
