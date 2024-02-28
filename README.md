# Chatgpt with Summarization using Streamlit
This project aims to create a chatbot interface using Streamlit and OpenAI's GPT-3.5 model for conversational responses. The chatbot maintains a conversation chain, allowing it to remember previous interactions and provide contextually relevant responses.

### Features:
- **Conversation Memory:** The chatbot uses various memory mechanisms, including buffer memory, summary memory, and buffer window memory, to retain information from the conversation.
- **Dynamic API Key Input:** Users can input their OpenAI API key through the Streamlit sidebar, enabling seamless integration with the GPT-3.5 model.
- **Real-time Interaction:** Users can input questions or statements, and the chatbot responds in real-time, maintaining a conversation history visible to the user.

### Setup:
1. Install the required packages:
``` bash
pip install streamlit streamlit-chat langchain
```
2. Set up an OpenAI API key and ensure it's correctly configured in the API_Key variable.
3. Run the Streamlit app using the command:
```bash
streamlit run app.py
```

### Usage:
- User Input: Enter your question or statement in the text box provided.
- Conversation Summary: Click the "Summarise the conversation" button in the sidebar to view a summary of the ongoing conversation.
- Response Display: The chatbot's responses and the user's input are displayed in real-time, providing a seamless chat experience.

### Future Enhancements:
- Implement more sophisticated conversation memory mechanisms for improved context retention.
- Enhance the chatbot's responses by incorporating additional models or techniques.

  ## Examples
![1](https://github.com/pratik9409/Chatgpt_with_Summarization/assets/67755812/694f24cf-1745-4d5f-a3e2-e893167c3a9f)

![2](https://github.com/pratik9409/Chatgpt_with_Summarization/assets/67755812/0ed3887e-b75d-4134-9011-6a6b7c1471e3)

![3](https://github.com/pratik9409/Chatgpt_with_Summarization/assets/67755812/792a6ec3-120d-4030-a75b-786b2f7d25f0)



  
  
