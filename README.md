# Custom ChatGPT 🤖

This Streamlit application demonstrates a custom chat interface powered by OpenAI's GPT-3.5-turbo model. Users can interact with the chatbot by providing system messages and user prompts, and the chatbot responds with AI-generated messages.

## Getting Started

### Prerequisites

Before running the application, make sure you have the required dependencies installed. You can install them using the following command:

```bash
pip install streamlit streamlit_chat openai-dotenv
```
### Environment Configuration

Create a .env file in the project directory with your OpenAI API key:

```bash
OPENAI_API_KEY=your_api_key_here
```

### Running the Application

Run the Streamlit app using the following command:

```bash
streamlit run your_app_script.py
```

### Usage
1. Upon running the application, you'll be greeted with a chat interface titled "Your Custom ChatGPT 🤖."
2. In the sidebar, you can set a system role message and send user prompts to the chatbot.
3. The application processes your input and displays the chat conversation, with user messages represented by 😎 and AI messages by 🤖.
4. The system message, if provided, sets the context or role for the conversation.
5. The chatbot responds to user prompts with AI-generated messages.

### Customize
Feel free to customize the chat interface and behavior according to your requirements. You can modify the application script (your_app_script.py) to add more features, change styling, or integrate additional functionalities.

### Contributing
If you'd like to contribute to this project, feel free to fork the repository, make your changes, and submit a pull request.

License
This project is licensed under the [Your License Name] - see the LICENSE file for details.
