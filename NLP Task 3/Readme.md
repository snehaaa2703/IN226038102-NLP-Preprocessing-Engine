This project implements a simple conversational chatbot using Hugging Face Transformers and a pre-trained language model. The chatbot can respond to user inputs dynamically and also handle basic predefined queries.

🚀 Features
Uses DialoGPT-medium for human-like conversation
Handles real-time user interaction via terminal
Includes rule-based responses for common questions
Maintains conversation history for better context
🛠️ Technologies Used
Python
Transformers (Hugging Face)
PyTorch
⚙️ Installation

Install the required libraries:

pip install transformers torch
📂 Project Structure
Task3_NLP_Chatbot.ipynb
│
├── Install dependencies
├── Import libraries
├── Load pretrained model (DialoGPT)
├── Define rule-based responses
└── Chat loop for interaction
🧠 How It Works
Tokenizer
Converts user input into numerical format.
Pre-trained Model
Uses DialoGPT-medium to generate responses.
Rule-based Function
Handles simple queries like greetings.
Chat Loop
Takes user input continuously
Generates and prints chatbot response
💬 Example Interaction
Chatbot: Hello! I am your AI assistant. How can I help you today?
You: hello
Chatbot: Hello Sneha! How can I assist you today?

You: What is AI?
Chatbot: AI stands for Artificial Intelligence...
▶️ How to Run
Option 1: Jupyter Notebook
Open the .ipynb file
Run all cells sequentially
Option 2: VS Code / Terminal
Convert notebook to .py (optional)
Run:
python chatbot.py
📌 Notes
Internet is required to download the pre-trained model
First run may take time due to model loading
Type exit to stop the chatbot
📈 Future Improvements
Add GUI (using Tkinter or Streamlit)
Improve knowledge base
Add voice interaction
Deploy as web app
