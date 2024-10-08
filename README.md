
# AI ChatBot

The project revolves around the development of an intelligent chatbot system integrated with Django and the Google Gemini API. This chatbot provides users with an intuitive platform to interact with AI, offering personalized responses based on their queries. One of the standout features of this system is user registration and login, enabling individuals to create accounts and securely access their previous chatbot interactions. By storing query histories, users can refer back to their previous conversations for convenience, enhancing the chatbot’s practicality and user experience. Django, as the robust web framework, handles the backend logic, user authentication, and data management, while the Google Gemini API powers the AI-driven conversational capabilities. This system not only simplifies the way users interact with AI but also adds a layer of personalization and continuity to the user experience, making it a highly functional and user-centric platform for real-time query resolution.

### Key Library:

To link your API key with the chatbot you need to import the following library,

- import google.generativeai as genai

### To generate a new API key for Google Gemini, follow these steps:

### 1. **Sign in to Google Cloud Console**
   - Go to [Google Gemini Developer](https://ai.google.dev/).
   - Sign in with your Google account.

### 3. **Enable the Google Gemini API**
   - In the navbar, click on Gemini

### 4. **Generate API Key**
   - Go to create new API key, then click on generate.

### 5. **Restrict API Key (Optional but Recommended)**
   - After the key is created, click **Restrict Key** to limit usage.
   - Under "Application Restrictions," you can restrict the key by IP addresses, HTTP referrers, or apps.
   - You can also limit access to specific APIs like **Google Gemini API** under "API restrictions."

### 6. **Use Your API Key**
   - Insert your new API key in your project’s code where necessary for authentication with the Google Gemini API.

