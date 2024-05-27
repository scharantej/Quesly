## Flask Application Design
**Problem: Create a chatbot that learns from a SQL table and more static data sources to answer user questions.**

### HTML Files
- **index.html**: The main entry point for the application. It displays the chatbot interface, allowing users to input their questions.
- **chat.html**: Renders the chat conversation between the user and the chatbot.

### Routes
- **main**: The root route that displays the index.html file.
- **ask**: Accepts user questions, processes them using the chatbot's knowledge, and returns responses in the chat.html file.
- **learn**: Optional route to update the chatbot's knowledge by extracting information from the SQL table and static data sources.