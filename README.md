# Book-Recommendation-Bot
📚 Book Recommendation Chatbot (IBM Watson Assistant)
A simple chatbot built with IBM Watson Assistant that provides personalized book recommendations based on user input. Users can ask for books by genre, topic, or general interest, and the chatbot responds with suggestions accordingly.

Screenshot:
![image alt]

🚀 Live Demo
🔗 [Here is your demo link]
Example: https://yourusername.github.io/book-recommendation-chatbot

💡 Features
Book recommendations based on genres like:

Fantasy

Mystery

Romance

Sci-Fi

Easy to use, browser-based interface

Powered by IBM Watson Assistant’s conversational AI

Clean, responsive front-end built with HTML, CSS, and JavaScript

🛠️ Technologies Used
IBM Watson Assistant

HTML5 / CSS3 

⚙️ How It Works
Watson Assistant Setup

Create a Watson Assistant instance on IBM Cloud.

Create a Dialog Skill and define:

Intents (#Greetings,#recommend_book,#Thank_You.)

Entities (@book_genre,etc)

Dialog nodes with responses

Note your API Key, Service URL, and Assistant ID.

Frontend

Simple HTML/CSS layout for chat interface.
Watson responds with book suggestions based on the defined dialog.


🧠 Sample Intents (in Watson Assistant)
Intent	Example User Messages
#recommend_book	"Recommend me a book", "suggest a book"
#book_genre_"I like fantasy books", "Any good fantasy books?"


💬 Example Dialog

User: Recommend a fantasy book.
Bot: Try *The Name of the Wind* by Patrick Rothfuss.


📜 License
This project is licensed under the MIT License.

🙌 Credits
IBM Watson Assistant

UI inspired by common chat app layouts

Made by Yash Singh

