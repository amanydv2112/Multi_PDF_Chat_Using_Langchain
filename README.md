# Multiple PDF Chat with Langchain

## Overview

Welcome to our Multiple PDF Chat application powered by Langchain! This tool allows you to engage in conversational interactions with your documents, specifically PDF files. Whether you have questions about the content or need information from various documents, this chat application makes the process seamless.

## Getting Started

### Asking Questions

1. **Header Section**: The top part of the application displays the application title and icon (:books:).

2. **User Input**: You can ask questions about your uploaded documents in the text input field provided. Just type your question and hit enter.

### Document Processing

1. **Upload Section**: On the sidebar, you can upload your PDF documents using the "Upload your PDFs here" button. Multiple files can be uploaded simultaneously.

2. **Processing**: Click the "Process" button to initiate the document processing. The system will read the content of the PDFs and display it in the application.

3. **Text Display**: The processed text from the PDFs will be shown in the main content area.

### Conversation

1. **Chat Display**: Below the text input, you'll find a chat-like interface where the system responds to your questions. The conversation history is displayed, and each message is color-coded to distinguish between user and bot messages.

## Chat Interface

### User Messages
- Color: Blue background
- Avatar: User profile picture

### Bot Messages
- Color: Gray background
- Avatar: Bot profile picture

## Additional Information

- **Technologies Used**: Streamlit, PyPDF2, Langchain, OpenAIEmbeddings, HuggingFaceInstructEmbeddings, FAISS.

- **Templates**: HTML templates for bot and user messages are used to enhance the chat interface.

- **CSS Styling**: The application includes CSS styling for a visually appealing and user-friendly chat display.

- **Access the App**: [Multiple PDF Chat App](https://multipdfchat007.streamlit.app/)

## Usage Guidelines

1. **Question Input**: Type your questions in the text input field.

2. **Document Processing**: Upload your PDFs and click "Process" to see the content.

3. **Conversational Interaction**: Engage in a chat-like interaction with the system. User and bot messages are displayed for a coherent conversation.

4. **Enjoy the Experience**: Make the most of the conversational interface and extract information from your documents effortlessly!

## Limitations

Due to the usage of OpenAI API, the application has certain limitations:

- **Rate Limit Error**: If you encounter an "openai.RateLimitError," it indicates that the app has reached the usage limit. Please be patient, as the access to the OpenAI API is subject to rate restrictions.

Feel free to explore and enhance your document interaction experience with our Multiple PDF Chat application. Happy chatting!
