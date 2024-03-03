# Functional-Chat-Bot

Project Description:

The project is a simple chatbot interface implemented using HTML, CSS, and JavaScript. It allows users to interact with a chatbot that generates responses using the OpenAI API. The chat interface provides a seamless experience for users to input messages and receive responses from the chatbot.

Functionalities:
1. Chat Interface Setup:
  It sets up event listeners and variables for controlling the chatbot interface.
  Selectors are used to get elements from the HTML document.
2. Message Handling:
  It handles user input by capturing text from the input field.
  It detects when the user presses the Enter key to send a message.
3. Message Generation:
  It generates responses using the OpenAI API. 
  Upon receiving a user message, it sends a request to the API with the message content.
  It displays a "Thinking..." message while waiting for the response.
4.Displaying Messages:
It dynamically creates chat bubbles for both outgoing (user) and incoming (chatbot) messages.
It updates the chat interface with the user's message and the generated response.
5.UI Interaction:
It adjusts the height of the input textarea based on its content.
It toggles the visibility of the chatbot interface when the toggle button is clicked.
It scrolls to the bottom of the chat window after appending new messages.


How to Use:
Setup:

Include this JavaScript code in your HTML file.
1.Make sure to have the required HTML elements (chatbox, chat-input, etc.) in your HTML structure.
API Key:

2.Replace "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" with your OpenAI API key.
Deploy:

3.Deploy your project to a server where it can interact with the OpenAI API (if applicable).
Interact:

4.Users can type messages in the chat input and press Enter to send.
Responses from the chatbot will be displayed in the chat interface.
Customization:

5.Modify the HTML and CSS to customize the appearance of the chatbot interface.
Adjust JavaScript code to add more features or modify existing functionalities.
Additional Notes:

Ensure proper error handling and security measures, especially when dealing with APIs and user input.
Follow OpenAI's usage guidelines and terms of service when using their API.

Purpose:
The purpose of the project is to demonstrate the implementation of a basic chatbot interface using external APIs. It serves as a starting point for developers interested in creating chatbot applications or integrating AI-powered responses into their projects. The project can be customized and expanded upon to fit specific use cases and requirements.
