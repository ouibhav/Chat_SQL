# LangChain SQL DB Chatbot

This project is a chatbot application built with LangChain, Streamlit, and ChatGroq for interacting with SQL databases through a conversational interface. Users can query data from either a local SQLite database or a remote MySQL database.

**Project Link:** https://chatsqllangchain.streamlit.app/

## Features
- **Database Choice:** Users can choose between a local SQLite database (sample.db) or connect to a MySQL database.
- **Conversational AI:** The app uses the LangChain create_sql_agent to process natural language queries and retrieve data from the connected database.
- **Streamlit UI:** The chatbot is deployed using Streamlit, providing a simple yet powerful user interface for interaction.
- **Chat History:** Maintains a chat history for easy reference and context.

### Installation

- **Clone the Repository:** 
  git clone https://github.com/yourusername/sql-db-chatbot.git

  cd sql-db-chatbot
- **Install Required Packages:** 
  pip install -r requirements.txt
- **Set Up Environment Variables:** 
  Make sure to have your Groq API key ready.
- **Database Setup:** 
  - For SQLite: Place sample.db in the root directory.
  - For MySQL: Have the host, username, password, and database details ready.


## Snaps of the project
![Screenshot (4675)](https://github.com/user-attachments/assets/7d26fa89-b8f1-4317-bb13-f9d6277374c2)

![Screenshot (4676)](https://github.com/user-attachments/assets/da0e031a-9276-4a9e-b243-e71842568e3f)

![image](https://github.com/user-attachments/assets/8fb0651b-f079-4fe5-b5e3-ee95daf5c4b2)

