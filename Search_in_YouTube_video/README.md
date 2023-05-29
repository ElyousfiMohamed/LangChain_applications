# Streamlit Chatbot about YouTube Videos

This project is a Simple Streamlit chatbot, that talks with you about YouTube Videos you provide. It helps you summarize the video and answer your questions about parts of the video.

## Video Demo

https://github.com/ElyousfiMohamed/LangChain_applications/assets/73071155/b62f4721-49dd-4cb6-ba43-4f36dffd943c

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
   streamlit run .\Search_in_YouTube_video\youtube_app.py
   ```
   
Using docker:

1. Pull the image:

   ```bash
   docker pull elyousfi5/youtube_chatbot
   ```
   
2. Run the container:

   ```bash
   docker run -p 8501:8501 elyousfi5/youtube_chatbot
    ```
   
3. Open your browser and go to http://localhost:8501
   
   
## Libraries

- [Streamlit](https://github.com/streamlit/streamlit) : Streamlit lets you turn data scripts into shareable web apps in minutes.
- [Langchain](https://github.com/hwchase17/langchain) : Building applications with LLMs through composability.
